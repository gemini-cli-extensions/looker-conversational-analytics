# Gemini CLI Extension - Looker Conversational Analytics

> [!NOTE]
> This extension is currently in beta (pre-v1.0), and may see breaking changes until the first stable release (v1.0).

This Gemini CLI extension provides a set of tools to interact with [Looker](https://cloud.google.com/looker/docs) instances. It allows you to manage your Looks, dashboards, and explores directly from the [Gemini CLI](https://google-gemini.github.io/gemini-cli/), using natural language prompts.

Learn more about [Gemini CLI Extensions](https://github.com/google-gemini/gemini-cli/blob/main/docs/extensions/index.md).
> [!IMPORTANT]
> **We Want Your Feedback!**
> Please share your thoughts with us by filling out our feedback [form][form]. 
> Your input is invaluable and helps us improve the project for everyone.

[form]: https://docs.google.com/forms/d/e/1FAIpQLSfEGmLR46iipyNTgwTmIDJqzkAwDPXxbocpXpUbHXydiN1RTw/viewform?usp=pp_url&entry.157487=looker

## Why Use the Looker Extension?

* **Seamless Workflow:** Stay in your CLI. No need to constantly switch contexts.
* **Connect to Looker:** Securely connect to your Looker instances.
* **Natural Language Usage:** Stop wrestling with complex commands. List models, explores, and dimensions, and run Looks and queries by describing what you want in plain English.


## Prerequisites

Before you begin, ensure you have the following:

* [Gemini CLI](https://github.com/google-gemini/gemini-cli) installed with version **+v0.6.0**.
* Setup Gemini CLI [Authentication](https://github.com/google-gemini/gemini-cli/tree/main?tab=readme-ov-file#-authentication-options).
* A Looker instance with API access enabled.
* A Google Cloud project with the appropriate APIs enabled.


## Getting Started

### Installation

To install the extension, use the command:

```bash
gemini extensions install https://github.com/gemini-cli-extensions/looker-conversational-analytics
```

### Configuration

You will need a Looker Client Id and Client Secret. These can be obtained by
following the directions at [Looker API authentication](https://cloud.google.com/looker/docs/api-auth#authentication_with_an_sdk). If you
don't have access to the Admin pages of the Looker system, you will need to ask
your administrator to get the Id and Secret for you.

You will need a Google Cloud project with the appropriate APIS enabled. Use the following command to enable those APIs:
```
gcloud services enable geminidataanalytics.googleapis.com --project=$PROJECT_ID
gcloud services enable cloudaicompanion.googleapis.com --project=$PROJECT_ID
```

In addition to [setting the ADC for your server][set-adc], you need to ensure
the IAM identity has been given the following IAM roles (or corresponding
permissions):

- `roles/looker.instanceUser`
- `roles/cloudaicompanion.user`
- `roles/geminidataanalytics.dataAgentStatelessUser`

To initialize the application default credential run `gcloud auth login --update-adc`
in your environment before starting MCP Toolbox.

[set-adc]: https://cloud.google.com/docs/authentication/provide-credentials-adc

Set the following environment variables before starting the Gemini CLI. These variables can be loaded from a `.env` file.

```bash
export LOOKER_BASE_URL="<your-looker-instance-url>"  # e.g. `https://looker.example.com`. You may need to add the port, i.e. `:19999`.
export LOOKER_CLIENT_ID="<your-looker-client-id>"
export LOOKER_CLIENT_SECRET="<your-looker-client-secret>"
export LOOKER_VERIFY_SSL="true" # Optional, defaults to true
export LOOKER_PROJECT="<your-google-cloud-project-id>"
export LOOKER_LOCATION="<your-google-cloud-location-id>"
```

### Start Gemini CLI

To start the Gemini CLI, use the following command:

```bash
gemini
```

## Usage
You can ask questions and give commands such as these:

1. What models are available in my Looker instance?
2. What explores are available in *model_name*?
2. What questions can I ask of the explore *explore_name* in model *model_name*?

## Supported Tools

* `get_models`: Use this tool to list the LookML models in Looker.
* `get_explores`: Use this tool to list the explores in a given model.
* `ask_data_insights`: Use this tool to ask a natural language questions of an explore.

## Additional Extensions

Find additional extensions to support your entire software development lifecycle at [github.com/gemini-cli-extensions](https://github.com/gemini-cli-extensions).

## Troubleshooting

Use `gemini --debug` to enable debugging.

Common issues:

* "failed to find default credentials: google: could not find default credentials.": Ensure [Application Default Credentials](https://cloud.google.com/docs/authentication/gcloud) are available in your environment. See [Set up Application Default Credentials](https://cloud.google.com/docs/authentication/external/set-up-adc) for more information.
* "✖ Error during discovery for server: MCP error -32000: Connection closed": The database connection has not been established. Ensure your configuration is set via environment variables.
* "✖ MCP ERROR: Error: spawn /Users/USER/.gemini/extensions/cloud-sql-sqlserver/toolbox ENOENT": The Toolbox binary did not download correctly. Ensure you are using Gemini CLI v0.6.0+.
* "cannot execute binary file": The Toolbox binary did not download correctly. Ensure the correct binary for your OS/Architecture has been downloaded. See [Installing the server](https://googleapis.github.io/genai-toolbox/getting-started/introduction/#installing-the-server) for more information.
