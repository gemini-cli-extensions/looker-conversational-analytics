# Changelog

## [0.3.8](https://github.com/gemini-cli-extensions/looker-conversational-analytics/compare/0.3.7...0.3.8) (2026-08-21)


### Features

* **groups:** Add ttlMs and cacheScope customization to config ([mcp-toolbox#​3805](https://redirect.github.com/googleapis/mcp-toolbox/issues/3805)) ([a5d4947](https://redirect.github.com/googleapis/mcp-toolbox/commit/a5d49472bad85e8955dc83852e65c5cd92f351a3)) ([6c6e869](https://github.com/gemini-cli-extensions/looker-conversational-analytics/commit/6c6e869ddb810d575b646641dacd43e123c10b09))
* **migrate:** Convert toolset to group kind during migration ([mcp-toolbox#​3704](https://redirect.github.com/googleapis/mcp-toolbox/issues/3704)) ([0adeaa5](https://redirect.github.com/googleapis/mcp-toolbox/commit/0adeaa51c4e132fe36553b24f88e8f62df90bfaa)) ([6c6e869](https://github.com/gemini-cli-extensions/looker-conversational-analytics/commit/6c6e869ddb810d575b646641dacd43e123c10b09))
* **server/mcp:** Introduce generic client extension registry ([mcp-toolbox#​3723](https://redirect.github.com/googleapis/mcp-toolbox/issues/3723)) ([016245c](https://redirect.github.com/googleapis/mcp-toolbox/commit/016245c21c254a05409a41845e0a8799518363a0)) ([6c6e869](https://github.com/gemini-cli-extensions/looker-conversational-analytics/commit/6c6e869ddb810d575b646641dacd43e123c10b09))
* **skill:** Add review-prs skill for mcp-toolbox ([mcp-toolbox#​3743](https://redirect.github.com/googleapis/mcp-toolbox/issues/3743)) ([5b7bacc](https://redirect.github.com/googleapis/mcp-toolbox/commit/5b7bacc73b9284160b73c4c3f7a53214c653e64a)) ([6c6e869](https://github.com/gemini-cli-extensions/looker-conversational-analytics/commit/6c6e869ddb810d575b646641dacd43e123c10b09))
* **tools:** Add cloud-sql-connect-gce for pg, mysql, mssql ([mcp-toolbox#​3740](https://redirect.github.com/googleapis/mcp-toolbox/issues/3740)) ([ca58fa4](https://redirect.github.com/googleapis/mcp-toolbox/commit/ca58fa4b525d6726b9792a9f6303fbcc26c9ca3f)) ([6c6e869](https://github.com/gemini-cli-extensions/looker-conversational-analytics/commit/6c6e869ddb810d575b646641dacd43e123c10b09))
* **tools/looker:** Add additional tools to allow dashboards to be modified, and their layouts altered. ([mcp-toolbox#​3597](https://redirect.github.com/googleapis/mcp-toolbox/issues/3597)) ([b2b80fb](https://redirect.github.com/googleapis/mcp-toolbox/commit/b2b80fbea64b6284f68b49c0ad3270ed79655282)) ([6c6e869](https://github.com/gemini-cli-extensions/looker-conversational-analytics/commit/6c6e869ddb810d575b646641dacd43e123c10b09))
* adopt Agent Plugin spec and generate harness manifests ([#95](https://github.com/gemini-cli-extensions/looker-conversational-analytics/issues/95)) ([5c1da76](https://github.com/gemini-cli-extensions/looker-conversational-analytics/commit/5c1da767ab54114bc281abdc6e395520c131e9d4))


### Bug Fixes

* **auth/mcp:** Derive PRM URL from Toolbox URL ([mcp-toolbox#​3765](https://redirect.github.com/googleapis/mcp-toolbox/issues/3765)) ([aa30842](https://redirect.github.com/googleapis/mcp-toolbox/commit/aa308422ad6dd73a014722c3ebf9628d7aa9cc8f)) ([6c6e869](https://github.com/gemini-cli-extensions/looker-conversational-analytics/commit/6c6e869ddb810d575b646641dacd43e123c10b09))
* **config:** Ignore environment variables in YAML comments ([mcp-toolbox#​3807](https://redirect.github.com/googleapis/mcp-toolbox/issues/3807)) ([79aa732](https://redirect.github.com/googleapis/mcp-toolbox/commit/79aa73247d35286e1cc4309883d539cf9a470686)), refs [mcp-toolbox#​3793](https://redirect.github.com/googleapis/mcp-toolbox/issues/3793) ([6c6e869](https://github.com/gemini-cli-extensions/looker-conversational-analytics/commit/6c6e869ddb810d575b646641dacd43e123c10b09))
* **mcp:** Return Tool execution error for invalid input param ([mcp-toolbox#​3799](https://redirect.github.com/googleapis/mcp-toolbox/issues/3799)) ([8120197](https://redirect.github.com/googleapis/mcp-toolbox/commit/81201978a7a1d2a786eb3707ddaa7b090dd1c454)) ([6c6e869](https://github.com/gemini-cli-extensions/looker-conversational-analytics/commit/6c6e869ddb810d575b646641dacd43e123c10b09))
* **prebuilt/cloud-storage:** Declare tool collections as groups ([mcp-toolbox#​3764](https://redirect.github.com/googleapis/mcp-toolbox/issues/3764)) ([7d468be](https://redirect.github.com/googleapis/mcp-toolbox/commit/7d468be107dfe476d77bd7f937b5dd9c61e5cdc8)) ([6c6e869](https://github.com/gemini-cli-extensions/looker-conversational-analytics/commit/6c6e869ddb810d575b646641dacd43e123c10b09))
* **server:** Avoid a nil-flusher panic in the SSE handler ([mcp-toolbox#​3520](https://redirect.github.com/googleapis/mcp-toolbox/issues/3520)) ([947f42f](https://redirect.github.com/googleapis/mcp-toolbox/commit/947f42f3e8a07362466566043045491d2318db29)) ([6c6e869](https://github.com/gemini-cli-extensions/looker-conversational-analytics/commit/6c6e869ddb810d575b646641dacd43e123c10b09))
* **server/mcp:** Disallow client overriding URL bound parameters ([mcp-toolbox#​3798](https://redirect.github.com/googleapis/mcp-toolbox/issues/3798)) ([f15a9c7](https://redirect.github.com/googleapis/mcp-toolbox/commit/f15a9c7082215bd8e9990395d01b5e4fa3b36c69)) ([6c6e869](https://github.com/gemini-cli-extensions/looker-conversational-analytics/commit/6c6e869ddb810d575b646641dacd43e123c10b09))
* **tools/looker:** Scope the filters quoting rule to values in query description ([mcp-toolbox#​3788](https://redirect.github.com/googleapis/mcp-toolbox/issues/3788)) ([78eb0b8](https://redirect.github.com/googleapis/mcp-toolbox/commit/78eb0b8580b0eebf781ba74e4cc12d1f94a7b65b)) ([6c6e869](https://github.com/gemini-cli-extensions/looker-conversational-analytics/commit/6c6e869ddb810d575b646641dacd43e123c10b09))
* **util:** Convert exponent-form JSON numbers in ConvertNumbers ([mcp-toolbox#​3730](https://redirect.github.com/googleapis/mcp-toolbox/issues/3730)) ([e9713ee](https://redirect.github.com/googleapis/mcp-toolbox/commit/e9713eec3acea912e0b6a254b845bd9da04f8192)) ([6c6e869](https://github.com/gemini-cli-extensions/looker-conversational-analytics/commit/6c6e869ddb810d575b646641dacd43e123c10b09))

## [0.3.7](https://github.com/gemini-cli-extensions/looker-conversational-analytics/compare/0.3.6...0.3.7) (2026-08-04)


### Features

* **prebuilt:** Migrate skills-repo toolsets to `kind: group` with descriptions ([mcp-toolbox#​3595](https://redirect.github.com/googleapis/mcp-toolbox/issues/3595)) ([b895b36](https://redirect.github.com/googleapis/mcp-toolbox/commit/b895b36b10eb81dc609216fc5f76ae800d1c65f4)) ([0f50093](https://github.com/gemini-cli-extensions/looker-conversational-analytics/commit/0f5009337db94cae6f587c7d364ff13f0ef158bb))
* **server:** Add `/healthz` endpoint for container health checks ([mcp-toolbox#​3060](https://redirect.github.com/googleapis/mcp-toolbox/issues/3060)) ([d5aefbc](https://redirect.github.com/googleapis/mcp-toolbox/commit/d5aefbc9e9bd914042224daaf0d4f9257ac01c88)) ([0f50093](https://github.com/gemini-cli-extensions/looker-conversational-analytics/commit/0f5009337db94cae6f587c7d364ff13f0ef158bb))
* **skills:** Add `--group` flag to generate a skill from one group ([mcp-toolbox#​3585](https://redirect.github.com/googleapis/mcp-toolbox/issues/3585)) ([c1abd4f](https://redirect.github.com/googleapis/mcp-toolbox/commit/c1abd4fc4fcdfa52ba20aaf7d92424ca189c7282)) ([0f50093](https://github.com/gemini-cli-extensions/looker-conversational-analytics/commit/0f5009337db94cae6f587c7d364ff13f0ef158bb))
* **skills:** Default `--name` to `--group`, `--toolset`, or single `--prebuilt` name ([mcp-toolbox#​3586](https://redirect.github.com/googleapis/mcp-toolbox/issues/3586)) ([2b33b08](https://redirect.github.com/googleapis/mcp-toolbox/commit/2b33b08c3a220657c8ab6a3e0ce1274badc2fe15)) ([0f50093](https://github.com/gemini-cli-extensions/looker-conversational-analytics/commit/0f5009337db94cae6f587c7d364ff13f0ef158bb))
* **skills:** Make description optional during skills gen ([mcp-toolbox#​3584](https://redirect.github.com/googleapis/mcp-toolbox/issues/3584)) ([d0a8f14](https://redirect.github.com/googleapis/mcp-toolbox/commit/d0a8f14cbec1f9770da7f82a07b4e480f5a4c6a7)) ([0f50093](https://github.com/gemini-cli-extensions/looker-conversational-analytics/commit/0f5009337db94cae6f587c7d364ff13f0ef158bb))
* **tool/looker:** Add `get_field_value_suggestions` tool ([mcp-toolbox#​3696](https://redirect.github.com/googleapis/mcp-toolbox/issues/3696)) ([3debe81](https://redirect.github.com/googleapis/mcp-toolbox/commit/3debe8113fe2c9af012a7369658bb7a9e64f40f4)) ([0f50093](https://github.com/gemini-cli-extensions/looker-conversational-analytics/commit/0f5009337db94cae6f587c7d364ff13f0ef158bb))
* Add `groups` support ([mcp-toolbox#​3605](https://redirect.github.com/googleapis/mcp-toolbox/issues/3605)) ([e75ec3b](https://redirect.github.com/googleapis/mcp-toolbox/commit/e75ec3b5c84dfad5b69f2d42ec2d3408f22e2463)) ([0f50093](https://github.com/gemini-cli-extensions/looker-conversational-analytics/commit/0f5009337db94cae6f587c7d364ff13f0ef158bb))
* Update draft specs to 2026-07-28 ([mcp-toolbox#​3699](https://redirect.github.com/googleapis/mcp-toolbox/issues/3699)) ([cf128ff](https://redirect.github.com/googleapis/mcp-toolbox/commit/cf128ff94c4d39aea1eb17caa706ff0b73d8c780)) ([0f50093](https://github.com/gemini-cli-extensions/looker-conversational-analytics/commit/0f5009337db94cae6f587c7d364ff13f0ef158bb))


### Bug Fixes

* **server:** Sort default toolset alphabetically for stable ordering ([mcp-toolbox#​3539](https://redirect.github.com/googleapis/mcp-toolbox/issues/3539)) ([e5da24c](https://redirect.github.com/googleapis/mcp-toolbox/commit/e5da24c5dfd2208c7e947a20e58a2e2c82236241)) ([0f50093](https://github.com/gemini-cli-extensions/looker-conversational-analytics/commit/0f5009337db94cae6f587c7d364ff13f0ef158bb))
* **tools/looker:** Enhance looker-run-dashboard to handle result maker structures and merge queries ([mcp-toolbox#​3698](https://redirect.github.com/googleapis/mcp-toolbox/issues/3698)) ([7666bc0](https://redirect.github.com/googleapis/mcp-toolbox/commit/7666bc08debdc4f81e1c6f95f41a1dbd9db3b365)) ([0f50093](https://github.com/gemini-cli-extensions/looker-conversational-analytics/commit/0f5009337db94cae6f587c7d364ff13f0ef158bb))
* **tools/looker:** Log request/response traces at debug, not error ([mcp-toolbox#​3552](https://redirect.github.com/googleapis/mcp-toolbox/issues/3552)) ([c3ad445](https://redirect.github.com/googleapis/mcp-toolbox/commit/c3ad4451e8592606ce686d042623f9aa8142317f)) ([0f50093](https://github.com/gemini-cli-extensions/looker-conversational-analytics/commit/0f5009337db94cae6f587c7d364ff13f0ef158bb))
* Re-add name validation to tools name ([mcp-toolbox#​3654](https://redirect.github.com/googleapis/mcp-toolbox/issues/3654)) ([944f6ce](https://redirect.github.com/googleapis/mcp-toolbox/commit/944f6ce97bc77a92a052de92b88f0fc09ac7578c)) ([0f50093](https://github.com/gemini-cli-extensions/looker-conversational-analytics/commit/0f5009337db94cae6f587c7d364ff13f0ef158bb))
* Re-add tool validation during startup ([mcp-toolbox#​3705](https://redirect.github.com/googleapis/mcp-toolbox/issues/3705)) ([25ce953](https://redirect.github.com/googleapis/mcp-toolbox/commit/25ce953559a201183f066f566dca5fb597efca39)) ([0f50093](https://github.com/gemini-cli-extensions/looker-conversational-analytics/commit/0f5009337db94cae6f587c7d364ff13f0ef158bb))

## [0.3.6](https://github.com/gemini-cli-extensions/looker-conversational-analytics/compare/0.3.5...0.3.6) (2026-07-21)


### Features

* **arcadedb:** Add arcadedb source and tools ([mcp-toolbox#​2961](https://redirect.github.com/googleapis/mcp-toolbox/issues/2961)) ([351de00](https://redirect.github.com/googleapis/mcp-toolbox/commit/351de00781a08999e735356624370ea1e7414419)) ([5008fd8](https://github.com/gemini-cli-extensions/looker-conversational-analytics/commit/5008fd8fc6ee7b5e627124cd965b1f3f99dfaea0))
* **cmd/internal,docs:** Add warning log that prebuilt tools are for developer use ([mcp-toolbox#​3451](https://redirect.github.com/googleapis/mcp-toolbox/issues/3451)) ([8cffcef](https://redirect.github.com/googleapis/mcp-toolbox/commit/8cffcef2b109ba913bd63b87a61f75db9e957d2f)) ([5008fd8](https://github.com/gemini-cli-extensions/looker-conversational-analytics/commit/5008fd8fc6ee7b5e627124cd965b1f3f99dfaea0))
* Add `quotaProject` support for BigQuery and Looker conversational analytics ([mcp-toolbox#​2610](https://redirect.github.com/googleapis/mcp-toolbox/issues/2610)) ([f3e7ca9](https://redirect.github.com/googleapis/mcp-toolbox/commit/f3e7ca9a8f49ce79f5b6fbef23c45a643c4e9d44)) ([5008fd8](https://github.com/gemini-cli-extensions/looker-conversational-analytics/commit/5008fd8fc6ee7b5e627124cd965b1f3f99dfaea0))


### Bug Fixes

* **parameters:** Report the offending value in array/map type errors ([mcp-toolbox#​3512](https://redirect.github.com/googleapis/mcp-toolbox/issues/3512)) ([4034d6f](https://redirect.github.com/googleapis/mcp-toolbox/commit/4034d6f7b820962495622dbedc64fea968c14963)) ([5008fd8](https://github.com/gemini-cli-extensions/looker-conversational-analytics/commit/5008fd8fc6ee7b5e627124cd965b1f3f99dfaea0))
* **parameters:** Return an error instead of panicking on a non-string type field ([mcp-toolbox#​3516](https://redirect.github.com/googleapis/mcp-toolbox/issues/3516)) ([66a0d53](https://redirect.github.com/googleapis/mcp-toolbox/commit/66a0d53b9fd11d6ee90b28ae1c411fc8685ab990)) ([5008fd8](https://github.com/gemini-cli-extensions/looker-conversational-analytics/commit/5008fd8fc6ee7b5e627124cd965b1f3f99dfaea0))
* **source/looker:** Dynamically resolve public host URL ([mcp-toolbox#​3603](https://redirect.github.com/googleapis/mcp-toolbox/issues/3603)) ([0428afd](https://redirect.github.com/googleapis/mcp-toolbox/commit/0428afd3e75339701a9dedb5199b89a001457349)) ([5008fd8](https://github.com/gemini-cli-extensions/looker-conversational-analytics/commit/5008fd8fc6ee7b5e627124cd965b1f3f99dfaea0))
* **tool/looker-run-dashboard:** Add support for SQL Runner query tiles ([mcp-toolbox#​3594](https://redirect.github.com/googleapis/mcp-toolbox/issues/3594)) ([0975d0a](https://redirect.github.com/googleapis/mcp-toolbox/commit/0975d0ac8bc5042f51a8b01eb5514d3ea138f145)) ([5008fd8](https://github.com/gemini-cli-extensions/looker-conversational-analytics/commit/5008fd8fc6ee7b5e627124cd965b1f3f99dfaea0))

## [0.3.5](https://github.com/gemini-cli-extensions/looker-conversational-analytics/compare/0.3.4...0.3.5) (2026-07-01)


### Features

* **release:** Add digital signature to Toolbox binaries ([mcp-toolbox#​3528](https://redirect.github.com/googleapis/mcp-toolbox/issues/3528)) ([3f0f0af](https://redirect.github.com/googleapis/mcp-toolbox/commit/3f0f0af29007929b01e95ee2caef4fd2015d5f12)) ([fbfb83c](https://github.com/gemini-cli-extensions/looker-conversational-analytics/commit/fbfb83c7d5ee998654189cd21e7fbb9f6c271672))
* **tools/looker:** Support complex filter\_expression parameter in queries ([mcp-toolbox#​3494](https://redirect.github.com/googleapis/mcp-toolbox/issues/3494)) ([997fb8c](https://redirect.github.com/googleapis/mcp-toolbox/commit/997fb8c39a4cb60173bcc8543118057e77e0fce4)) ([fbfb83c](https://github.com/gemini-cli-extensions/looker-conversational-analytics/commit/fbfb83c7d5ee998654189cd21e7fbb9f6c271672))
* **tools/looker:** Support dynamic\_fields parameter in queries ([mcp-toolbox#​3507](https://redirect.github.com/googleapis/mcp-toolbox/issues/3507)) ([cd22b89](https://redirect.github.com/googleapis/mcp-toolbox/commit/cd22b893573f87c0d5406490b71ddf317a07dc7b)) ([fbfb83c](https://github.com/gemini-cli-extensions/looker-conversational-analytics/commit/fbfb83c7d5ee998654189cd21e7fbb9f6c271672))
* Support MCP 2026 draft specs ([mcp-toolbox#​3544](https://redirect.github.com/googleapis/mcp-toolbox/issues/3544)) ([d12eaa8](https://redirect.github.com/googleapis/mcp-toolbox/commit/d12eaa856bad70b49ba2b7b9f2882cffbf81220f)) ([fbfb83c](https://github.com/gemini-cli-extensions/looker-conversational-analytics/commit/fbfb83c7d5ee998654189cd21e7fbb9f6c271672))


### Bug Fixes

* **tool/looker-create-view-from-table:** Correct Looker API payload structure ([mcp-toolbox#​3515](https://redirect.github.com/googleapis/mcp-toolbox/issues/3515)) ([18c539c](https://redirect.github.com/googleapis/mcp-toolbox/commit/18c539c5935c2a496e7e5da68241b4307d8f3e6e)) ([fbfb83c](https://github.com/gemini-cli-extensions/looker-conversational-analytics/commit/fbfb83c7d5ee998654189cd21e7fbb9f6c271672))
* **tools/looker-conversational-analytics:** Validate explore\_references shape instead of panicking ([mcp-toolbox#​3531](https://redirect.github.com/googleapis/mcp-toolbox/issues/3531)) ([b67419d](https://redirect.github.com/googleapis/mcp-toolbox/commit/b67419d34bfc437b6eace5abaaf02ae1339d83ee)) ([fbfb83c](https://github.com/gemini-cli-extensions/looker-conversational-analytics/commit/fbfb83c7d5ee998654189cd21e7fbb9f6c271672))

## [0.3.4](https://github.com/gemini-cli-extensions/looker-conversational-analytics/compare/0.3.3...0.3.4) (2026-06-22)


### Features

* **auth/google:** Require audience or clientId for mcpEnabled ([mcp-toolbox#​3450](https://redirect.github.com/googleapis/mcp-toolbox/issues/3450)) ([59f7b6e](https://redirect.github.com/googleapis/mcp-toolbox/commit/59f7b6e8eaceffca042cb7e2f2b6e5e9284b6bc3)) ([3df7c8f](https://github.com/gemini-cli-extensions/looker-conversational-analytics/commit/3df7c8f7123805e668c973d6e338b610cef37efe))
* **mcp:** Add URL parameter binding for HTTP transport ([mcp-toolbox#​3112](https://redirect.github.com/googleapis/mcp-toolbox/issues/3112)) ([0cc7b37](https://redirect.github.com/googleapis/mcp-toolbox/commit/0cc7b37b733b6a99dad5281af4024b26d730106a)) ([3df7c8f](https://github.com/gemini-cli-extensions/looker-conversational-analytics/commit/3df7c8f7123805e668c973d6e338b610cef37efe))
* **scylladb:** Adding support for ScyllaDB source and tool ([mcp-toolbox#​3119](https://redirect.github.com/googleapis/mcp-toolbox/issues/3119)) ([2dada83](https://redirect.github.com/googleapis/mcp-toolbox/commit/2dada8306c8737e445c4f8cd3d213b72713c1834)) ([3df7c8f](https://github.com/gemini-cli-extensions/looker-conversational-analytics/commit/3df7c8f7123805e668c973d6e338b610cef37efe))
* **server:** Add support for toolset filtering in prebuilt CLI flag ([mcp-toolbox#​3245](https://redirect.github.com/googleapis/mcp-toolbox/issues/3245)) ([7cc4f65](https://redirect.github.com/googleapis/mcp-toolbox/commit/7cc4f65a8e767e0da37cf21f0ff2568b38d32b8e)) ([3df7c8f](https://github.com/gemini-cli-extensions/looker-conversational-analytics/commit/3df7c8f7123805e668c973d6e338b610cef37efe))
* **skills:** Generate skills offline without live source connections ([mcp-toolbox#​3388](https://redirect.github.com/googleapis/mcp-toolbox/issues/3388)) ([4c860b6](https://redirect.github.com/googleapis/mcp-toolbox/commit/4c860b66b03f0ebf86205e73cd8521ad90ccebe4)) ([3df7c8f](https://github.com/gemini-cli-extensions/looker-conversational-analytics/commit/3df7c8f7123805e668c973d6e338b610cef37efe))
* **skills:** Tolerate missing env vars during offline skills-generate ([mcp-toolbox#​3399](https://redirect.github.com/googleapis/mcp-toolbox/issues/3399)) ([ea5d3e5](https://redirect.github.com/googleapis/mcp-toolbox/commit/ea5d3e5b9e60bf808e10d21b522954d76f7741b6)) ([3df7c8f](https://github.com/gemini-cli-extensions/looker-conversational-analytics/commit/3df7c8f7123805e668c973d6e338b610cef37efe))
* **tools:** Decouple tool initialization from sources ([mcp-toolbox#​3355](https://redirect.github.com/googleapis/mcp-toolbox/issues/3355)) ([32a24e3](https://redirect.github.com/googleapis/mcp-toolbox/commit/32a24e35b5bf107bcf5e89af2a9b7af3740747ee)) ([3df7c8f](https://github.com/gemini-cli-extensions/looker-conversational-analytics/commit/3df7c8f7123805e668c973d6e338b610cef37efe))
* Enable per source level flags for sql commenter ([mcp-toolbox#​3465](https://redirect.github.com/googleapis/mcp-toolbox/issues/3465)) ([ecce6b7](https://redirect.github.com/googleapis/mcp-toolbox/commit/ecce6b7bb551b947b0951cd684cce627a4b6cf1b)) ([3df7c8f](https://github.com/gemini-cli-extensions/looker-conversational-analytics/commit/3df7c8f7123805e668c973d6e338b610cef37efe))


### Bug Fixes

* **auth/dataplex:** Fix failing source with service account credentials ([mcp-toolbox#​3369](https://redirect.github.com/googleapis/mcp-toolbox/issues/3369)) ([ba4deef](https://redirect.github.com/googleapis/mcp-toolbox/commit/ba4deef140358e5876d73d355d664f629f7aeccc)) ([3df7c8f](https://github.com/gemini-cli-extensions/looker-conversational-analytics/commit/3df7c8f7123805e668c973d6e338b610cef37efe))
* **bigquery:** Wire maximumBytesBilled into prebuilt config ([mcp-toolbox#​3385](https://redirect.github.com/googleapis/mcp-toolbox/issues/3385)) ([4abbf6e](https://redirect.github.com/googleapis/mcp-toolbox/commit/4abbf6e82cc4af4c1903d9143337c965987475a9)) ([3df7c8f](https://github.com/gemini-cli-extensions/looker-conversational-analytics/commit/3df7c8f7123805e668c973d6e338b610cef37efe))
* **config:** Add doc/line context to parse errors ([mcp-toolbox#​2957](https://redirect.github.com/googleapis/mcp-toolbox/issues/2957)) ([4b097da](https://redirect.github.com/googleapis/mcp-toolbox/commit/4b097daa2143817e55a9e557e8c1dea054bfc7b8)) ([3df7c8f](https://github.com/gemini-cli-extensions/looker-conversational-analytics/commit/3df7c8f7123805e668c973d6e338b610cef37efe))
* **npm:** Source binary version from cmd/version.txt ([mcp-toolbox#​3417](https://redirect.github.com/googleapis/mcp-toolbox/issues/3417)) ([6ffbdec](https://redirect.github.com/googleapis/mcp-toolbox/commit/6ffbdecaea98db5c16dc9eeca8fb73e4bbc48102)) ([3df7c8f](https://github.com/gemini-cli-extensions/looker-conversational-analytics/commit/3df7c8f7123805e668c973d6e338b610cef37efe))
* **prebuilt/alloydb-omni:** Require password env var explicitly ([mcp-toolbox#​3398](https://redirect.github.com/googleapis/mcp-toolbox/issues/3398)) ([fcbe3e7](https://redirect.github.com/googleapis/mcp-toolbox/commit/fcbe3e70d3d4e671e97e424187dba907d7c5b10b)) ([3df7c8f](https://github.com/gemini-cli-extensions/looker-conversational-analytics/commit/3df7c8f7123805e668c973d6e338b610cef37efe))
* **server:** Fail if MCP auth is enabled together with enable-api ([mcp-toolbox#​3435](https://redirect.github.com/googleapis/mcp-toolbox/issues/3435)) ([a6ff910](https://redirect.github.com/googleapis/mcp-toolbox/commit/a6ff910a602adece11f0a6581d6211e5927f7182)) ([3df7c8f](https://github.com/gemini-cli-extensions/looker-conversational-analytics/commit/3df7c8f7123805e668c973d6e338b610cef37efe))
* **server:** Return errors instead of panicking in InitializeConfigs ([mcp-toolbox#​3397](https://redirect.github.com/googleapis/mcp-toolbox/issues/3397)) ([f48b01d](https://redirect.github.com/googleapis/mcp-toolbox/commit/f48b01dc1775e4583a06689a2e67fb06e5dd3c68)) ([3df7c8f](https://github.com/gemini-cli-extensions/looker-conversational-analytics/commit/3df7c8f7123805e668c973d6e338b610cef37efe))
* Bound MCP HTTP body size ([mcp-toolbox#​3216](https://redirect.github.com/googleapis/mcp-toolbox/issues/3216)) ([d4f4342](https://redirect.github.com/googleapis/mcp-toolbox/commit/d4f434251392fb597779a90a12c63d21533ea187)) ([3df7c8f](https://github.com/gemini-cli-extensions/looker-conversational-analytics/commit/3df7c8f7123805e668c973d6e338b610cef37efe))
* Escape delimiter characters in applyEscape to prevent SQL injection ([932519a](https://redirect.github.com/googleapis/mcp-toolbox/commit/932519a9551861bf5f18787dc43b20d06350343f)) ([3df7c8f](https://github.com/gemini-cli-extensions/looker-conversational-analytics/commit/3df7c8f7123805e668c973d6e338b610cef37efe))

## [0.3.3](https://github.com/gemini-cli-extensions/looker-conversational-analytics/compare/0.3.2...0.3.3) (2026-06-05)


### Features

* **deps:** update dependency googleapis/mcp-toolbox to v1.4.0 ([#75](https://github.com/gemini-cli-extensions/looker-conversational-analytics/issues/75)) ([45f5dd7](https://github.com/gemini-cli-extensions/looker-conversational-analytics/commit/45f5dd7df4407d4fa8c8c68c21524a177cc4be26))

## [0.3.2](https://github.com/gemini-cli-extensions/looker-conversational-analytics/compare/0.3.1...0.3.2) (2026-05-22)


### Features

* **auth:** Implement MCP auth tool-level scopes validation ([mcp-toolbox#​3049](https://redirect.github.com/googleapis/mcp-toolbox/issues/3049)) ([c528985](https://redirect.github.com/googleapis/mcp-toolbox/commit/c528985149060adb648f85b5486391bd72d6727e)) ([83ddb65](https://github.com/gemini-cli-extensions/looker-conversational-analytics/commit/83ddb651a560ee2e765b535d02ecb3df98081cf7))
* **looker:** Propagate client IP from incoming MCP requests to downstream SDK calls ([mcp-toolbox#​3253](https://redirect.github.com/googleapis/mcp-toolbox/issues/3253)) ([75da6c2](https://redirect.github.com/googleapis/mcp-toolbox/commit/75da6c21dd29d7e8e70eac1b747e3946097e7459)) ([83ddb65](https://github.com/gemini-cli-extensions/looker-conversational-analytics/commit/83ddb651a560ee2e765b535d02ecb3df98081cf7))
* Setup SQLCommenter and allow client metadata  ([mcp-toolbox#​3064](https://redirect.github.com/googleapis/mcp-toolbox/issues/3064)) ([9f1f9b3](https://redirect.github.com/googleapis/mcp-toolbox/commit/9f1f9b321dcd05cce55dbff1bbaebfc44a4c9907)) ([83ddb65](https://github.com/gemini-cli-extensions/looker-conversational-analytics/commit/83ddb651a560ee2e765b535d02ecb3df98081cf7))


### Bug Fixes

* **auth/generic:** Fix generic auth expiration field and integration with `authRequired` ([mcp-toolbox#​3251](https://redirect.github.com/googleapis/mcp-toolbox/issues/3251)) ([f4d16c0](https://redirect.github.com/googleapis/mcp-toolbox/commit/f4d16c09b12c4d3297a9aedca706c9830382a4e3)) ([83ddb65](https://github.com/gemini-cli-extensions/looker-conversational-analytics/commit/83ddb651a560ee2e765b535d02ecb3df98081cf7))
* **tools:** Initialize query result slices to empty array ([mcp-toolbox#​3250](https://redirect.github.com/googleapis/mcp-toolbox/issues/3250)) ([60ddf48](https://redirect.github.com/googleapis/mcp-toolbox/commit/60ddf487468bfd11c7f9346f16a33a8986f89f84)) ([83ddb65](https://github.com/gemini-cli-extensions/looker-conversational-analytics/commit/83ddb651a560ee2e765b535d02ecb3df98081cf7))
* **tools/looker:** Return a 401 error to MCP client when Looker returns a 401 ([mcp-toolbox#​3233](https://redirect.github.com/googleapis/mcp-toolbox/issues/3233)) ([4f409a3](https://redirect.github.com/googleapis/mcp-toolbox/commit/4f409a3283d533bddcf4756a1d58c228744b3931)) ([83ddb65](https://github.com/gemini-cli-extensions/looker-conversational-analytics/commit/83ddb651a560ee2e765b535d02ecb3df98081cf7))
* **tools/looker:** Strip wrapping quotes from filter values for unquoted parameters ([mcp-toolbox#​3273](https://redirect.github.com/googleapis/mcp-toolbox/issues/3273)) ([1e3de96](https://redirect.github.com/googleapis/mcp-toolbox/commit/1e3de96daa9bc06253d05b0caf63d499878fb70e)) ([83ddb65](https://github.com/gemini-cli-extensions/looker-conversational-analytics/commit/83ddb651a560ee2e765b535d02ecb3df98081cf7))

## [0.3.1](https://github.com/gemini-cli-extensions/looker-conversational-analytics/compare/0.3.0...0.3.1) (2026-05-11)


### Features

* **deps:** update dependency googleapis/mcp-toolbox to v1.2.0 ([#67](https://github.com/gemini-cli-extensions/looker-conversational-analytics/issues/67)) ([26f5f42](https://github.com/gemini-cli-extensions/looker-conversational-analytics/commit/26f5f42953ece7d0f9fab9738291ad84617ca115))

## [0.3.0](https://github.com/gemini-cli-extensions/looker-conversational-analytics/compare/0.2.5...0.3.0) (2026-04-10)


### ⚠ BREAKING CHANGES

* **tools/looker:** refactor looker-git-branch tool into 5 separate tools ([mcp-toolbox#​2976](https://redirect.github.com/googleapis/mcp-toolbox/issues/2976))

### Features

* **auth:** Support opaque token validation for `generic` authService ([mcp-toolbox#​2944](https://redirect.github.com/googleapis/mcp-toolbox/issues/2944)) ([c924701](https://redirect.github.com/googleapis/mcp-toolbox/commit/c924701adede95877594423d78b7ae72fe0b9c82)) ([69ffb72](https://github.com/gemini-cli-extensions/looker-conversational-analytics/commit/69ffb72d3609dbea66e0e404f7aaf63ac794ac44))
* **cloudsqlpg:** Run `SELECT 1` after successful connection attempt ([mcp-toolbox#​2997](https://redirect.github.com/googleapis/mcp-toolbox/issues/2997)) ([6ed9700](https://redirect.github.com/googleapis/mcp-toolbox/commit/6ed9700e15f08b31e65eb0afa605f4a8ea937e66)) ([69ffb72](https://github.com/gemini-cli-extensions/looker-conversational-analytics/commit/69ffb72d3609dbea66e0e404f7aaf63ac794ac44))
* **tools/looker:** refactor looker-git-branch tool into 5 separate tools ([mcp-toolbox#​2976](https://redirect.github.com/googleapis/mcp-toolbox/issues/2976)) ([69ffb72](https://github.com/gemini-cli-extensions/looker-conversational-analytics/commit/69ffb72d3609dbea66e0e404f7aaf63ac794ac44))
* **tools/looker:** Refactor looker-git-branch tool into 5 separate tools ([mcp-toolbox#​2976](https://redirect.github.com/googleapis/mcp-toolbox/issues/2976)) ([b2472d4](https://redirect.github.com/googleapis/mcp-toolbox/commit/b2472d4926dacc496fc6956185fb281b5e75f56f)) ([69ffb72](https://github.com/gemini-cli-extensions/looker-conversational-analytics/commit/69ffb72d3609dbea66e0e404f7aaf63ac794ac44))

## [0.2.5](https://github.com/gemini-cli-extensions/looker-conversational-analytics/compare/0.2.4...0.2.5) (2026-04-08)


### Features

* **deps:** update dependency googleapis/mcp-toolbox to v0.32.0 ([#59](https://github.com/gemini-cli-extensions/looker-conversational-analytics/issues/59)) ([10d3fa1](https://github.com/gemini-cli-extensions/looker-conversational-analytics/commit/10d3fa1499a9b2678d114b0c36b7256e2003f468))

## [0.2.4](https://github.com/gemini-cli-extensions/looker-conversational-analytics/compare/0.2.3...0.2.4) (2026-03-27)


### Features

* **deps:** update dependency googleapis/mcp-toolbox to v0.31.0 ([#55](https://github.com/gemini-cli-extensions/looker-conversational-analytics/issues/55)) ([8e96880](https://github.com/gemini-cli-extensions/looker-conversational-analytics/commit/8e96880a7cab353d86ad118f58fe73aae88a361d))

## [0.2.3](https://github.com/gemini-cli-extensions/looker-conversational-analytics/compare/0.2.2...0.2.3) (2026-03-20)


### Features

* **cli:** Add migrate subcommand ([#2679](https://redirect.github.com/googleapis/mcp-toolbox/issues/2679)) ([12171f7](https://redirect.github.com/googleapis/mcp-toolbox/commit/12171f7a02bcd34ce647db10abdb79bb2dac7ace)) ([03cbce5](https://github.com/gemini-cli-extensions/looker-conversational-analytics/commit/03cbce58f9e1f1bb639558d0fba28f271c3a3964))
* **cli:** Add serve subcommand ([#2550](https://redirect.github.com/googleapis/mcp-toolbox/issues/2550)) ([1e2c7c7](https://redirect.github.com/googleapis/mcp-toolbox/commit/1e2c7c7804c67bebf5e2ee9b67c6feb6f05292fd)) ([03cbce5](https://github.com/gemini-cli-extensions/looker-conversational-analytics/commit/03cbce58f9e1f1bb639558d0fba28f271c3a3964))
* **skill:** One skill per toolset ([#2733](https://redirect.github.com/googleapis/mcp-toolbox/issues/2733)) ([5b85c65](https://redirect.github.com/googleapis/mcp-toolbox/commit/5b85c65960dba9bfaf4cadca6d44532a153976e1)) ([03cbce5](https://github.com/gemini-cli-extensions/looker-conversational-analytics/commit/03cbce58f9e1f1bb639558d0fba28f271c3a3964))
* **tools/looker:** Support git\_branch tools for looker. ([#2718](https://redirect.github.com/googleapis/mcp-toolbox/issues/2718)) ([70ed8a0](https://redirect.github.com/googleapis/mcp-toolbox/commit/70ed8a0dcb8e654b748a6e3e1c5ef283c26006da)) ([03cbce5](https://github.com/gemini-cli-extensions/looker-conversational-analytics/commit/03cbce58f9e1f1bb639558d0fba28f271c3a3964))


### Bug Fixes

* **ci:** Implement conditional sharding logic in integration tests ([#2763](https://redirect.github.com/googleapis/mcp-toolbox/issues/2763)) ([1528d7c](https://redirect.github.com/googleapis/mcp-toolbox/commit/1528d7c38dfaa30bdecbe59c79ba926fa6d18356)) ([03cbce5](https://github.com/gemini-cli-extensions/looker-conversational-analytics/commit/03cbce58f9e1f1bb639558d0fba28f271c3a3964))
* **cloudloggingadmin:** Increase log injesting time and add auth test ([#2772](https://redirect.github.com/googleapis/mcp-toolbox/issues/2772)) ([50b4457](https://redirect.github.com/googleapis/mcp-toolbox/commit/50b4457095ec4ac881b3b12719da24d35141f65d)) ([03cbce5](https://github.com/gemini-cli-extensions/looker-conversational-analytics/commit/03cbce58f9e1f1bb639558d0fba28f271c3a3964))
* **oracle:** Normalize encoded proxy usernames in go-ora DSN ([#2469](https://redirect.github.com/googleapis/mcp-toolbox/issues/2469)) ([b1333cd](https://redirect.github.com/googleapis/mcp-toolbox/commit/b1333cd27117655f8ab09f222721e14bea74b487)) ([03cbce5](https://github.com/gemini-cli-extensions/looker-conversational-analytics/commit/03cbce58f9e1f1bb639558d0fba28f271c3a3964))
* **postgres:** Update execute-sql tool to avoid multi-statements parameter ([#2707](https://redirect.github.com/googleapis/mcp-toolbox/issues/2707)) ([58bc772](https://redirect.github.com/googleapis/mcp-toolbox/commit/58bc772f882f0d9e00f403e73fbec812dd8a03ac)) ([03cbce5](https://github.com/gemini-cli-extensions/looker-conversational-analytics/commit/03cbce58f9e1f1bb639558d0fba28f271c3a3964))
* **skills:** Improve flag validation and silence unit test output ([#2759](https://redirect.github.com/googleapis/mcp-toolbox/issues/2759)) ([f3da6aa](https://redirect.github.com/googleapis/mcp-toolbox/commit/f3da6aa5e23b609a1ac9ecc098bccea02f2388ab)) ([03cbce5](https://github.com/gemini-cli-extensions/looker-conversational-analytics/commit/03cbce58f9e1f1bb639558d0fba28f271c3a3964))
* **test:** Address flaky healthcare integration test run ([#2742](https://redirect.github.com/googleapis/mcp-toolbox/issues/2742)) ([9590821](https://redirect.github.com/googleapis/mcp-toolbox/commit/9590821bc7d86c5cbacd29b21d4f85b427a87db4)) ([03cbce5](https://github.com/gemini-cli-extensions/looker-conversational-analytics/commit/03cbce58f9e1f1bb639558d0fba28f271c3a3964))

## [0.2.2](https://github.com/gemini-cli-extensions/looker-conversational-analytics/compare/0.2.1...0.2.2) (2026-03-17)


### Features

* **deps:** update dependency googleapis/mcp-toolbox to v0.29.0 ([#50](https://github.com/gemini-cli-extensions/looker-conversational-analytics/issues/50)) ([0d8ece9](https://github.com/gemini-cli-extensions/looker-conversational-analytics/commit/0d8ece996e4322771c8758b38d8ed5bb53f4c4d2))

## [0.2.1](https://github.com/gemini-cli-extensions/looker-conversational-analytics/compare/0.2.0...0.2.1) (2026-03-03)


### Features

* **dataproc:** Add dataproc source and list/get clusters/jobs tools ([#2407](https://redirect.github.com/googleapis/mcp-toolbox/issues/2407)) ([cc05e57](https://redirect.github.com/googleapis/mcp-toolbox/commit/cc05e5745d1c25a6088702b827cd098250164b7e)) ([9e55081](https://github.com/gemini-cli-extensions/looker-conversational-analytics/commit/9e550815e9efee8dd66cd915b4b5a76e6558a4e8))
* **tools/looker:** Enable Get All Lookml Tests, Run LookML Tests, and Create View From Table tools for Looker ([#2522](https://redirect.github.com/googleapis/mcp-toolbox/issues/2522)) ([e01139a](https://redirect.github.com/googleapis/mcp-toolbox/commit/e01139a90268f8587b9823be1157259c1bcbfd66)) ([9e55081](https://github.com/gemini-cli-extensions/looker-conversational-analytics/commit/9e550815e9efee8dd66cd915b4b5a76e6558a4e8))
* **tools/looker:** Tools to list/create/delete directories ([#2488](https://redirect.github.com/googleapis/mcp-toolbox/issues/2488)) ([0036d8c](https://redirect.github.com/googleapis/mcp-toolbox/commit/0036d8c35844c3de2079cb5b2479781e8938525b)) ([9e55081](https://github.com/gemini-cli-extensions/looker-conversational-analytics/commit/9e550815e9efee8dd66cd915b4b5a76e6558a4e8))
* **ui:** Make tool list panel resizable ([#2253](https://redirect.github.com/googleapis/mcp-toolbox/issues/2253)) ([276cf60](https://redirect.github.com/googleapis/mcp-toolbox/commit/276cf604a2bb41861639ed6881557e38dd97a614)) ([9e55081](https://github.com/gemini-cli-extensions/looker-conversational-analytics/commit/9e550815e9efee8dd66cd915b4b5a76e6558a4e8))
* Add polling system to dynamic reloading ([#2466](https://redirect.github.com/googleapis/mcp-toolbox/issues/2466)) ([fcaac9b](https://redirect.github.com/googleapis/mcp-toolbox/commit/fcaac9bb957226ee3db1baea24330f337ba88ab7)) ([9e55081](https://github.com/gemini-cli-extensions/looker-conversational-analytics/commit/9e550815e9efee8dd66cd915b4b5a76e6558a4e8))
* Added basic template for sdks doc migrate ([#1961](https://redirect.github.com/googleapis/mcp-toolbox/issues/1961)) ([87f2eaf](https://redirect.github.com/googleapis/mcp-toolbox/commit/87f2eaf79cdecca7b939151e1543eccf2f812a69)) ([9e55081](https://github.com/gemini-cli-extensions/looker-conversational-analytics/commit/9e550815e9efee8dd66cd915b4b5a76e6558a4e8))


### Bug Fixes

* **ci:** Add path for forked PR unit test runs ([#2540](https://redirect.github.com/googleapis/mcp-toolbox/issues/2540)) ([04dd2a7](https://redirect.github.com/googleapis/mcp-toolbox/commit/04dd2a77603c7babf01da724dfb77808e3f25fe5)) ([9e55081](https://github.com/gemini-cli-extensions/looker-conversational-analytics/commit/9e550815e9efee8dd66cd915b4b5a76e6558a4e8))
* **docs/adk:** Resolve dependency duplication ([#2418](https://redirect.github.com/googleapis/mcp-toolbox/issues/2418)) ([4d44abb](https://redirect.github.com/googleapis/mcp-toolbox/commit/4d44abb4638926ca50b0fa4dcf10a03e7fab657f)) ([9e55081](https://github.com/gemini-cli-extensions/looker-conversational-analytics/commit/9e550815e9efee8dd66cd915b4b5a76e6558a4e8))
* **docs/langchain:** Fix core at 0.3.0 and align compatible dependencies ([#2426](https://redirect.github.com/googleapis/mcp-toolbox/issues/2426)) ([36edfd3](https://redirect.github.com/googleapis/mcp-toolbox/commit/36edfd3d506e839c092d04cbca1799b5ebc38160)) ([9e55081](https://github.com/gemini-cli-extensions/looker-conversational-analytics/commit/9e550815e9efee8dd66cd915b4b5a76e6558a4e8))
* **oracle:** Enable DML operations and resolve incorrect array type error ([#2323](https://redirect.github.com/googleapis/mcp-toolbox/issues/2323)) ([72146a4](https://redirect.github.com/googleapis/mcp-toolbox/commit/72146a4b1605bcdd3e1038106bfb1f899e677e39)) ([9e55081](https://github.com/gemini-cli-extensions/looker-conversational-analytics/commit/9e550815e9efee8dd66cd915b4b5a76e6558a4e8))
* **server/mcp:** Guard nil dereference in sseManager.get ([#2557](https://redirect.github.com/googleapis/mcp-toolbox/issues/2557)) ([e534196](https://redirect.github.com/googleapis/mcp-toolbox/commit/e534196303c2b8d9b6e599ac25add337e6fc9b8f)), closes [#2548](https://redirect.github.com/googleapis/mcp-toolbox/issues/2548) ([9e55081](https://github.com/gemini-cli-extensions/looker-conversational-analytics/commit/9e550815e9efee8dd66cd915b4b5a76e6558a4e8))
* **tests:** Resolve LlamaIndex dependency conflict in JS quickstart ([#2597](https://redirect.github.com/googleapis/mcp-toolbox/issues/2597)) ([ac11f5a](https://redirect.github.com/googleapis/mcp-toolbox/commit/ac11f5af9c7bcf228d667e1b8e08b5dc49ad91a0)) ([9e55081](https://github.com/gemini-cli-extensions/looker-conversational-analytics/commit/9e550815e9efee8dd66cd915b4b5a76e6558a4e8))
* **tests/postgres:** Implement uuid-based isolation and reliable resource cleanup ([#2377](https://redirect.github.com/googleapis/mcp-toolbox/issues/2377)) ([8a96fb1](https://redirect.github.com/googleapis/mcp-toolbox/commit/8a96fb1a8874baa3688e566f3dea8a0912fcf2df)) ([9e55081](https://github.com/gemini-cli-extensions/looker-conversational-analytics/commit/9e550815e9efee8dd66cd915b4b5a76e6558a4e8))
* **tests/postgres:** Restore list\_schemas test and implement dynamic owner ([#2521](https://redirect.github.com/googleapis/mcp-toolbox/issues/2521)) ([7041e79](https://redirect.github.com/googleapis/mcp-toolbox/commit/7041e797347f337d6f7f44ca051ae31acd58babe)) ([9e55081](https://github.com/gemini-cli-extensions/looker-conversational-analytics/commit/9e550815e9efee8dd66cd915b4b5a76e6558a4e8))
* Deflake alloydb omni ([#2431](https://redirect.github.com/googleapis/mcp-toolbox/issues/2431)) ([62b8309](https://redirect.github.com/googleapis/mcp-toolbox/commit/62b830987d65c3573214d04e50742476097ee9e9)) ([9e55081](https://github.com/gemini-cli-extensions/looker-conversational-analytics/commit/9e550815e9efee8dd66cd915b4b5a76e6558a4e8))
* Enforce required validation for explicit null parameter values ([#&2519](https://redirect.github.com/googleapis/mcp-toolbox/issues/2519)) ([d5e9512](https://redirect.github.com/googleapis/mcp-toolbox/commit/d5e9512a237e658f9b9127fdd8c174ec023c3310)) ([9e55081](https://github.com/gemini-cli-extensions/looker-conversational-analytics/commit/9e550815e9efee8dd66cd915b4b5a76e6558a4e8))

## [0.2.0](https://github.com/gemini-cli-extensions/looker-conversational-analytics/compare/0.1.9...0.2.0) (2026-02-20)


### ⚠ BREAKING CHANGES

* Update/add detailed telemetry for mcp endpoint compliant with OTEL semantic convention ([#1987](https://redirect.github.com/googleapis/mcp-toolbox/issues/1987)) ([478a0bd](https://redirect.github.com/googleapis/mcp-toolbox/commit/478a0bdb59288c1213f83862f95a698b4c2c0aab))
* Update configuration file v2 ([#2369](https://redirect.github.com/googleapis/mcp-toolbox/issues/2369))([293c1d6](https://redirect.github.com/googleapis/mcp-toolbox/commit/293c1d6889c39807855ba5e01d4c13ba2a4c50ce))

### Features

* **cli/invoke:** Add support for direct tool invocation from CLI ([#2353](https://redirect.github.com/googleapis/mcp-toolbox/issues/2353)) ([6e49ba4](https://redirect.github.com/googleapis/mcp-toolbox/commit/6e49ba436ef2390c13feaf902b29f5907acffb57)) ([96c5cb6](https://github.com/gemini-cli-extensions/looker-conversational-analytics/commit/96c5cb622dc7db60597ee215034d44a9ae86cd40))
* **cli/skills:** Add support for generating agent skills from toolset ([#2392](https://redirect.github.com/googleapis/mcp-toolbox/issues/2392)) ([80ef346](https://redirect.github.com/googleapis/mcp-toolbox/commit/80ef34621453b77bdf6a6016c354f102a17ada04)) ([96c5cb6](https://github.com/gemini-cli-extensions/looker-conversational-analytics/commit/96c5cb622dc7db60597ee215034d44a9ae86cd40))
* **cloud-logging-admin:** Add source, tools, integration test and docs ([#2137](https://redirect.github.com/googleapis/mcp-toolbox/issues/2137)) ([252fc30](https://redirect.github.com/googleapis/mcp-toolbox/commit/252fc3091af10d25d8d7af7e047b5ac87a5dd041)) ([96c5cb6](https://github.com/gemini-cli-extensions/looker-conversational-analytics/commit/96c5cb622dc7db60597ee215034d44a9ae86cd40))
* **cockroachdb:** Add CockroachDB integration with cockroach-go ([#2006](https://redirect.github.com/googleapis/mcp-toolbox/issues/2006)) ([1fdd99a](https://redirect.github.com/googleapis/mcp-toolbox/commit/1fdd99a9b609a5e906acce414226ff44d75d5975)) ([96c5cb6](https://github.com/gemini-cli-extensions/looker-conversational-analytics/commit/96c5cb622dc7db60597ee215034d44a9ae86cd40))
* **prebuiltconfigs/alloydb-omni:** Implement Alloydb omni dataplane tools ([#2340](https://redirect.github.com/googleapis/mcp-toolbox/issues/2340)) ([e995349](https://redirect.github.com/googleapis/mcp-toolbox/commit/e995349ea0756c700d188b8f04e9459121219f0c)) ([96c5cb6](https://github.com/gemini-cli-extensions/looker-conversational-analytics/commit/96c5cb622dc7db60597ee215034d44a9ae86cd40))
* **server:** Add Tool call error categories ([#2387](https://redirect.github.com/googleapis/mcp-toolbox/issues/2387)) ([32cb4db](https://redirect.github.com/googleapis/mcp-toolbox/commit/32cb4db712d27579c1bf29e61cbd0bed02286c28)) ([96c5cb6](https://github.com/gemini-cli-extensions/looker-conversational-analytics/commit/96c5cb622dc7db60597ee215034d44a9ae86cd40))
* **tools/looker:** support `looker-validate-project` tool ([#2430](https://redirect.github.com/googleapis/mcp-toolbox/issues/2430)) ([a15a128](https://redirect.github.com/googleapis/mcp-toolbox/commit/a15a12873f936b0102aeb9500cc3bcd71bb38c34)) ([96c5cb6](https://github.com/gemini-cli-extensions/looker-conversational-analytics/commit/96c5cb622dc7db60597ee215034d44a9ae86cd40))
* Update configuration file v2 ([#2369](https://redirect.github.com/googleapis/mcp-toolbox/issues/2369))([293c1d6](https://redirect.github.com/googleapis/mcp-toolbox/commit/293c1d6889c39807855ba5e01d4c13ba2a4c50ce)) ([96c5cb6](https://github.com/gemini-cli-extensions/looker-conversational-analytics/commit/96c5cb622dc7db60597ee215034d44a9ae86cd40))
* Update/add detailed telemetry for mcp endpoint compliant with OTEL semantic convention ([#1987](https://redirect.github.com/googleapis/mcp-toolbox/issues/1987)) ([478a0bd](https://redirect.github.com/googleapis/mcp-toolbox/commit/478a0bdb59288c1213f83862f95a698b4c2c0aab)) ([96c5cb6](https://github.com/gemini-cli-extensions/looker-conversational-analytics/commit/96c5cb622dc7db60597ee215034d44a9ae86cd40))


### Bug Fixes

* **dataplex:** Capture GCP HTTP errors in MCP Toolbox ([#2347](https://redirect.github.com/googleapis/mcp-toolbox/issues/2347)) ([1d7c498](https://redirect.github.com/googleapis/mcp-toolbox/commit/1d7c4981164c34b4d7bc8edecfd449f57ad11e15)) ([96c5cb6](https://github.com/gemini-cli-extensions/looker-conversational-analytics/commit/96c5cb622dc7db60597ee215034d44a9ae86cd40))
* Surface Dataplex API errors in MCP results ([#2347](https://redirect.github.com/googleapis/mcp-toolbox/pull/2347))([1d7c498](https://redirect.github.com/googleapis/mcp-toolbox/commit/1d7c4981164c34b4d7bc8edecfd449f57ad11e15)) ([96c5cb6](https://github.com/gemini-cli-extensions/looker-conversational-analytics/commit/96c5cb622dc7db60597ee215034d44a9ae86cd40))

## [0.1.9](https://github.com/gemini-cli-extensions/looker-conversational-analytics/compare/0.1.8...0.1.9) (2026-01-28)


### Features

* add Configuration settings ([#33](https://github.com/gemini-cli-extensions/looker-conversational-analytics/issues/33)) ([10170c4](https://github.com/gemini-cli-extensions/looker-conversational-analytics/commit/10170c4e45ddea6231ca5284bf3984230d26f4ce))
* **deps:** update dependency googleapis/mcp-toolbox to v0.26.0 ([#32](https://github.com/gemini-cli-extensions/looker-conversational-analytics/issues/32)) ([9c69dd8](https://github.com/gemini-cli-extensions/looker-conversational-analytics/commit/9c69dd8841cbe66b03c8e6ecbd97a754aa47f7f6))

## [0.1.8](https://github.com/gemini-cli-extensions/looker-conversational-analytics/compare/0.1.7...0.1.8) (2026-01-22)


### Features

* **deps:** update dependency googleapis/mcp-toolbox to v0.25.0 ([#28](https://github.com/gemini-cli-extensions/looker-conversational-analytics/issues/28)) ([50ff2b0](https://github.com/gemini-cli-extensions/looker-conversational-analytics/commit/50ff2b08bfa1e956e4d538a075beaf957b2cf935))

## [0.1.7](https://github.com/gemini-cli-extensions/looker-conversational-analytics/compare/0.1.6...0.1.7) (2025-12-19)


### Features

* **deps:** update dependency googleapis/mcp-toolbox to v0.24.0 ([#26](https://github.com/gemini-cli-extensions/looker-conversational-analytics/issues/26)) ([4330828](https://github.com/gemini-cli-extensions/looker-conversational-analytics/commit/4330828f7300d4516d1251861afc2020cdd14d9c))

## [0.1.6](https://github.com/gemini-cli-extensions/looker-conversational-analytics/compare/0.1.5...0.1.6) (2025-12-12)


### Features

* **deps:** update dependency googleapis/mcp-toolbox to v0.23.0 ([#23](https://github.com/gemini-cli-extensions/looker-conversational-analytics/issues/23)) ([f76fd37](https://github.com/gemini-cli-extensions/looker-conversational-analytics/commit/f76fd376f2c63d84a6a5729ff16e97ab3bf9c3ed))

## [0.1.5](https://github.com/gemini-cli-extensions/looker-conversational-analytics/compare/0.1.4...0.1.5) (2025-12-05)


### Features

* **deps:** update dependency googleapis/mcp-toolbox to v0.22.0 ([#21](https://github.com/gemini-cli-extensions/looker-conversational-analytics/issues/21)) ([d0abaa2](https://github.com/gemini-cli-extensions/looker-conversational-analytics/commit/d0abaa2746507a02c8e5ad1caef743416775a669))

## [0.1.4](https://github.com/gemini-cli-extensions/looker-conversational-analytics/compare/0.1.3...0.1.4) (2025-11-20)


### Features

* **deps:** update dependency googleapis/mcp-toolbox to v0.21.0 ([#17](https://github.com/gemini-cli-extensions/looker-conversational-analytics/issues/17)) ([bbd6318](https://github.com/gemini-cli-extensions/looker-conversational-analytics/commit/bbd631817ba4dd6cb6e865aa9fa8ead6d3ba5c4a))

## [0.1.3](https://github.com/gemini-cli-extensions/looker-conversational-analytics/compare/0.1.2...0.1.3) (2025-11-14)


### Features

* **tool/looker-generate-embed-url:** Adding generate embed url tool ([#1877](https://redirect.github.com/googleapis/mcp-toolbox/issues/1877)) ([ef63860](https://redirect.github.com/googleapis/mcp-toolbox/commit/ef63860559798fbad54c1051d9f53bce42d66464)) ([13fda6b](https://github.com/gemini-cli-extensions/looker-conversational-analytics/commit/13fda6b47ab217e87aa56f22a24c64d5b7b0e4fb))
* Added prompt support for toolbox ([#1798](https://redirect.github.com/googleapis/mcp-toolbox/issues/1798)) ([cd56ea4](https://redirect.github.com/googleapis/mcp-toolbox/commit/cd56ea44fbdd149fcb92324e70ee36ac747635db)) ([13fda6b](https://github.com/gemini-cli-extensions/looker-conversational-analytics/commit/13fda6b47ab217e87aa56f22a24c64d5b7b0e4fb))

## [0.1.2](https://github.com/gemini-cli-extensions/looker-conversational-analytics/compare/0.1.1...0.1.2) (2025-11-09)


### Features

* **cloud-healthcare:** Add support for healthcare source, tool and prebuilt config ([#1853](https://redirect.github.com/googleapis/mcp-toolbox/issues/1853)) ([1f833fb](https://redirect.github.com/googleapis/mcp-toolbox/commit/1f833fb1a124e23819ddfec476f2e63ef31dd22f)) ([5288e58](https://github.com/gemini-cli-extensions/looker-conversational-analytics/commit/5288e5826404e255000f6b66572bba74418d9d79))
* **elasticsearch:** Add Elasticsearch source and tools ([#1109](https://redirect.github.com/googleapis/mcp-toolbox/issues/1109)) ([5367285](https://redirect.github.com/googleapis/mcp-toolbox/commit/5367285e91ddda99ae7261d8ed4b025f975d1453)) ([5288e58](https://github.com/gemini-cli-extensions/looker-conversational-analytics/commit/5288e5826404e255000f6b66572bba74418d9d79))
* **mindsdb:** Add MindsDB Source and Tools  ([#878](https://redirect.github.com/googleapis/mcp-toolbox/issues/878)) ([1b2cca9](https://redirect.github.com/googleapis/mcp-toolbox/commit/1b2cca9faa6f7bacbeb5d25634ce3bf61067de16)) ([5288e58](https://github.com/gemini-cli-extensions/looker-conversational-analytics/commit/5288e5826404e255000f6b66572bba74418d9d79))
* **singlestore:** Add SingleStore Source and Tools ([#1333](https://redirect.github.com/googleapis/mcp-toolbox/issues/1333)) ([40b9dba](https://redirect.github.com/googleapis/mcp-toolbox/commit/40b9dbab088add05a66995abb1c71a9345b8f7e5)) ([5288e58](https://github.com/gemini-cli-extensions/looker-conversational-analytics/commit/5288e5826404e255000f6b66572bba74418d9d79))
* **tools/looker-run-dashboard:** New `run_dashboard` tool ([#1858](https://redirect.github.com/googleapis/mcp-toolbox/issues/1858)) ([30857c2](https://redirect.github.com/googleapis/mcp-toolbox/commit/30857c2294bb14961d3be49e2c368c69ecf844ec)) ([5288e58](https://github.com/gemini-cli-extensions/looker-conversational-analytics/commit/5288e5826404e255000f6b66572bba74418d9d79))
* **tools/looker-run-look:** Modify run\_look to show query origin ([#1860](https://redirect.github.com/googleapis/mcp-toolbox/issues/1860)) ([991e539](https://redirect.github.com/googleapis/mcp-toolbox/commit/991e539f9c7978fa618ada3179a0b656c33ff501)) ([5288e58](https://github.com/gemini-cli-extensions/looker-conversational-analytics/commit/5288e5826404e255000f6b66572bba74418d9d79))
* **tools/looker:** Tools to retrieve the connections, schemas, databases, and column metadata from a looker system. ([#1804](https://redirect.github.com/googleapis/mcp-toolbox/issues/1804)) ([d7d1b03](https://redirect.github.com/googleapis/mcp-toolbox/commit/d7d1b03f3b746ed748d67f67e833457d55c846ab)) ([5288e58](https://github.com/gemini-cli-extensions/looker-conversational-analytics/commit/5288e5826404e255000f6b66572bba74418d9d79))
* Support `excludeValues` for parameters ([#1818](https://redirect.github.com/googleapis/mcp-toolbox/issues/1818)) ([a8e98dc](https://redirect.github.com/googleapis/mcp-toolbox/commit/a8e98dc99d208e8b37a3bc4d1ab4749b5154ed36)) ([5288e58](https://github.com/gemini-cli-extensions/looker-conversational-analytics/commit/5288e5826404e255000f6b66572bba74418d9d79))


### Bug Fixes

* **cloudmonitoring:** Populate `authRequired` in tool manifest ([#1800](https://redirect.github.com/googleapis/mcp-toolbox/issues/1800)) ([954152c](https://redirect.github.com/googleapis/mcp-toolbox/commit/954152c7928bf0da9be221e011e32f74bc4cebbc)) ([5288e58](https://github.com/gemini-cli-extensions/looker-conversational-analytics/commit/5288e5826404e255000f6b66572bba74418d9d79))
* Bigquery execute\_sql to assign values to array ([#1884](https://redirect.github.com/googleapis/mcp-toolbox/issues/1884)) ([559e2a2](https://redirect.github.com/googleapis/mcp-toolbox/commit/559e2a22e0db20bb947702e13140ce869b5865a7)) ([5288e58](https://github.com/gemini-cli-extensions/looker-conversational-analytics/commit/5288e5826404e255000f6b66572bba74418d9d79))
* Instructions to quote filters that include commas ([#1794](https://redirect.github.com/googleapis/mcp-toolbox/issues/1794)) ([4b01720](https://redirect.github.com/googleapis/mcp-toolbox/commit/4b0172083c0dd4c71098d4e0ab5fa0b16ea0d830)) ([5288e58](https://github.com/gemini-cli-extensions/looker-conversational-analytics/commit/5288e5826404e255000f6b66572bba74418d9d79))
* Update debug logs statements ([#1828](https://redirect.github.com/googleapis/mcp-toolbox/issues/1828)) ([3cff915](https://redirect.github.com/googleapis/mcp-toolbox/commit/3cff915e22c3a5e4e296607f83ae6409b896c9a9)) ([5288e58](https://github.com/gemini-cli-extensions/looker-conversational-analytics/commit/5288e5826404e255000f6b66572bba74418d9d79))

## [0.1.1](https://github.com/gemini-cli-extensions/looker-conversational-analytics/compare/0.1.0...0.1.1) (2025-10-23)


### Features

* **tools/looker:** Tools to allow the agent to retrieve, create, modify, and delete LookML project files. ([#1673](https://redirect.github.com/googleapis/mcp-toolbox/issues/1673)) ([089081f](https://redirect.github.com/googleapis/mcp-toolbox/commit/089081feb0e32f9eb65d00df5987392d413a4081)) ([b829371](https://github.com/gemini-cli-extensions/looker-conversational-analytics/commit/b829371e3961e4939b0dd49aedd0aca1eac952b3))
* Support `allowedValues`, `escape`, `minValue` and `maxValue` for parameters ([#1770](https://redirect.github.com/googleapis/mcp-toolbox/issues/1770)) ([eaf7740](https://redirect.github.com/googleapis/mcp-toolbox/commit/eaf77406fd386c12315d67eb685dc69e0415c516)) ([b829371](https://github.com/gemini-cli-extensions/looker-conversational-analytics/commit/b829371e3961e4939b0dd49aedd0aca1eac952b3))


### Bug Fixes

* **tools/looker:** Looker file content calls should not use url.QueryEscape ([#1758](https://redirect.github.com/googleapis/mcp-toolbox/issues/1758)) ([336de1b](https://redirect.github.com/googleapis/mcp-toolbox/commit/336de1bd04b869d322c0fd1f4667eb652159d791)) ([b829371](https://github.com/gemini-cli-extensions/looker-conversational-analytics/commit/b829371e3961e4939b0dd49aedd0aca1eac952b3))
