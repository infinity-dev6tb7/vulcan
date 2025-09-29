# Changelog

## 1.0.0 (2025-09-29)


### ⚠ BREAKING CHANGES

* use results on fs module ([#191](https://github.com/infinity-dev6tb7/vulcan/issues/191))
* use custom types for Results and Error, and use error functions ([#189](https://github.com/infinity-dev6tb7/vulcan/issues/189))
* remove Results from json setters ([#182](https://github.com/infinity-dev6tb7/vulcan/issues/182))
* add results to commands ([#179](https://github.com/infinity-dev6tb7/vulcan/issues/179))

### Features

* add `captureReverts` to `Watcher` ([2834f29](https://github.com/infinity-dev6tb7/vulcan/commit/2834f2966769272b19027b60d44c9ca5f7239a0e))
* add `fileExists` ([b8af1dd](https://github.com/infinity-dev6tb7/vulcan/commit/b8af1dd5e26d53725f26565789a2097bf079e8aa))
* add `firstCall` and `lastCall` ([b5f08ef](https://github.com/infinity-dev6tb7/vulcan/commit/b5f08ef0b77e8b9116cc94570bed63d88dabbc37))
* add `firstCall` and `lastCall` to `Vulcan` ([5972ac1](https://github.com/infinity-dev6tb7/vulcan/commit/5972ac1f6ea32498dec03521c81f21b516eaf6c7))
* add `reset` to `Watcher` ([1642836](https://github.com/infinity-dev6tb7/vulcan/commit/164283604fe434ece36b1154bf239be219fc2aed))
* add `stopWatch` to `Vulcan` ([2d2580e](https://github.com/infinity-dev6tb7/vulcan/commit/2d2580e391d131e61fd1498ad1e478935d031232))
* Add `toString` method to commands ([a268a74](https://github.com/infinity-dev6tb7/vulcan/commit/a268a740c508a7c165bec9efabea6b1bbd3ea410))
* add abbreviations ([034d67c](https://github.com/infinity-dev6tb7/vulcan/commit/034d67c445f23067949b6bd144f96c70aa89b3a9))
* add basic types to pointer casting ([#198](https://github.com/infinity-dev6tb7/vulcan/issues/198)) ([6805978](https://github.com/infinity-dev6tb7/vulcan/commit/680597802fa51cbd0d78b5a964ef53c28585f4ee))
* add createAddress function ([7e0471c](https://github.com/infinity-dev6tb7/vulcan/commit/7e0471cbce7a8e60133382af3a23d20704b5ca24))
* add disableCaptureReverts ([84576a9](https://github.com/infinity-dev6tb7/vulcan/commit/84576a9d50c023682f144d6cfe4049c6fb4cbb47))
* add function to calculate deployment addresses ([fe9157d](https://github.com/infinity-dev6tb7/vulcan/commit/fe9157d1eebf44e957c13cd822c55016abb1cd59))
* add function to create empty command ([602d43c](https://github.com/infinity-dev6tb7/vulcan/commit/602d43cd882abf788ac1b075439bb03d86cb075b))
* add function to parse format string ([2d9b179](https://github.com/infinity-dev6tb7/vulcan/commit/2d9b1791b2f4c4a99819c4562ff3e629b5ecc102))
* add functions to update token balances ([d4b08ac](https://github.com/infinity-dev6tb7/vulcan/commit/d4b08aca51b562f59e491d5c00f5d73478ee752c))
* add gas module ([5cb9219](https://github.com/infinity-dev6tb7/vulcan/commit/5cb921966f150e7786eaf293649fa2aebd7f1296))
* add message to expect utilities ([#231](https://github.com/infinity-dev6tb7/vulcan/issues/231)) ([11c705c](https://github.com/infinity-dev6tb7/vulcan/commit/11c705cdc525155cb2e7e7b97e9c7c5568b23334))
* add missing forge-std functions ([78694e3](https://github.com/infinity-dev6tb7/vulcan/commit/78694e37265d46638fb6e9349c09528ee51be909))
* add placeholder struct ([88dc596](https://github.com/infinity-dev6tb7/vulcan/commit/88dc5964915edab18c3b433f32e6559d81db361f))
* add results to commands ([#179](https://github.com/infinity-dev6tb7/vulcan/issues/179)) ([2385e00](https://github.com/infinity-dev6tb7/vulcan/commit/2385e002d68ab9ba223582abc677bb44bc5a9f15))
* add semver module ([#204](https://github.com/infinity-dev6tb7/vulcan/issues/204)) ([66e5b05](https://github.com/infinity-dev6tb7/vulcan/commit/66e5b05d8e24eaa21e8a0bc320268ec7cc953ae3))
* add toHaveRevertedWith ([de19d1f](https://github.com/infinity-dev6tb7/vulcan/commit/de19d1fa49534e7980fcd0d330a52b9b0ad673f5))
* adds the `setGrasPrice` method without Context ([c4193eb](https://github.com/infinity-dev6tb7/vulcan/commit/c4193eb259ff3aa00ae20d7aa7941a17b09083e4))
* adds the `setPrevrandao` method without context ([62dcadf](https://github.com/infinity-dev6tb7/vulcan/commit/62dcadf7007c6f24618affb181ac5ea021c279f7))
* config module ([3ab4817](https://github.com/infinity-dev6tb7/vulcan/commit/3ab4817041ffe3a5dcddf32da7662d3b7ed934f4))
* export Command struct from script.sol ([9f8a20f](https://github.com/infinity-dev6tb7/vulcan/commit/9f8a20f074b5fdcb45615d9ee5c86de3b77c8d6f))
* extend address to have calls ([b838df4](https://github.com/infinity-dev6tb7/vulcan/commit/b838df471638b4aa25bb9b8fc32d28be38cd798e))
* improved json validation using Results ([#178](https://github.com/infinity-dev6tb7/vulcan/issues/178)) ([4ce2012](https://github.com/infinity-dev6tb7/vulcan/commit/4ce2012eaaa63fa2ac9e7f50ecd8d9ce40cd283e))
* install forge-std@v1.7.6 ([083d500](https://github.com/infinity-dev6tb7/vulcan/commit/083d500867f1a6789f65dd8a72df35b3b8fd2142))
* new project structure ([#220](https://github.com/infinity-dev6tb7/vulcan/issues/220)) ([3262258](https://github.com/infinity-dev6tb7/vulcan/commit/326225811cdc90e5313ccbd1af92fb27924f7d02))
* refactor structure ([1cc343b](https://github.com/infinity-dev6tb7/vulcan/commit/1cc343b630a197f7094fb5931499b8ffc5bcd57c))
* remove Results from json setters ([#182](https://github.com/infinity-dev6tb7/vulcan/issues/182)) ([ee01416](https://github.com/infinity-dev6tb7/vulcan/commit/ee01416f260f3fe1a33d34b64d127b606bcdd66b))
* replace struct storage with mapping ([912989b](https://github.com/infinity-dev6tb7/vulcan/commit/912989b758268f3ce98e78aea3ab6b695b9c4b50))
* request module ([#174](https://github.com/infinity-dev6tb7/vulcan/issues/174)) ([bf26156](https://github.com/infinity-dev6tb7/vulcan/commit/bf261564e098035259f04a373f2a2429cd5a707a))
* rpc module ([#236](https://github.com/infinity-dev6tb7/vulcan/issues/236)) ([0ef2cf9](https://github.com/infinity-dev6tb7/vulcan/commit/0ef2cf9d1165238e70dc79d1436513a810c38613))
* store all call results ([4d54560](https://github.com/infinity-dev6tb7/vulcan/commit/4d54560e7c0056db295faa6d303bbc0e0abe5a62))
* string to json ([#238](https://github.com/infinity-dev6tb7/vulcan/issues/238)) ([0205b96](https://github.com/infinity-dev6tb7/vulcan/commit/0205b9648d8b0021eae7c64e710b17f126ce9ad8))
* update forge-std ([#240](https://github.com/infinity-dev6tb7/vulcan/issues/240)) ([5b9416a](https://github.com/infinity-dev6tb7/vulcan/commit/5b9416a93e48b281311a9cb0d6c1d0988b895e42))
* update forge-std to v1.7.3 ([2bb7b09](https://github.com/infinity-dev6tb7/vulcan/commit/2bb7b09a4a4f0549272f3ac1264d387efa1911ed))
* update Vulcan.watch to return watcher ([6d0c1a1](https://github.com/infinity-dev6tb7/vulcan/commit/6d0c1a1d430d1714169772304c4229494d378daa))
* use `serializeJson` cheatcode ([#196](https://github.com/infinity-dev6tb7/vulcan/issues/196)) ([9ab48d1](https://github.com/infinity-dev6tb7/vulcan/commit/9ab48d13e68e40eb20fe9d9f01dc449dfc80c6ba))
* use custom types for Results and Error, and use error functions ([#189](https://github.com/infinity-dev6tb7/vulcan/issues/189)) ([84645ea](https://github.com/infinity-dev6tb7/vulcan/commit/84645ea872ee1185e95b66a1b8bbbf405a6e9e6b))
* use forge-std@705263c ([#195](https://github.com/infinity-dev6tb7/vulcan/issues/195)) ([3e4ab84](https://github.com/infinity-dev6tb7/vulcan/commit/3e4ab84b9caa85263f04e9b8b8f0641d601ae23f))
* use results on fs module ([#191](https://github.com/infinity-dev6tb7/vulcan/issues/191)) ([dbf8cdc](https://github.com/infinity-dev6tb7/vulcan/commit/dbf8cdcf18e33f5b9941bd2ec23fb9438d93075f))
* watchers namespace ([a8eed04](https://github.com/infinity-dev6tb7/vulcan/commit/a8eed04d3e922bd215b554c5befe7576ffbac84d))
* wrapped address ([442302a](https://github.com/infinity-dev6tb7/vulcan/commit/442302a19a6518a942f5a23ab5b46c20fba2d8a5))


### Bug Fixes

* adapt to new forge-std Vm to remove warnings ([cc779eb](https://github.com/infinity-dev6tb7/vulcan/commit/cc779eb7a80f3fb37a809cac7c637815286aacb1))
* add events to watchers docs ([f4d8e9e](https://github.com/infinity-dev6tb7/vulcan/commit/f4d8e9e90947f1beb08ab55e93aab3e5d344f18a))
* add missing imports on script.sol ([#212](https://github.com/infinity-dev6tb7/vulcan/issues/212)) ([f046381](https://github.com/infinity-dev6tb7/vulcan/commit/f0463811efd5155aacd7c8f6877c71f225e3d0b1))
* fix `firstCall` and `lastCall` on `Vulcan` ([7c3d9fb](https://github.com/infinity-dev6tb7/vulcan/commit/7c3d9fb01e5f3929d9919ae1c6dbd745c80d1dd1))
* fix cast abi-encode command ([#226](https://github.com/infinity-dev6tb7/vulcan/issues/226)) ([ffa427a](https://github.com/infinity-dev6tb7/vulcan/commit/ffa427a428029d29e8141986fab3958f267f26fe))
* fix decimal format ([9d3d39a](https://github.com/infinity-dev6tb7/vulcan/commit/9d3d39aa7df13bd4333a26c06e863d39b32ab276))
* fix disableCaptureReverts ([8181e09](https://github.com/infinity-dev6tb7/vulcan/commit/8181e094aca1f71d0bc0115cb005aef4b59e8396))
* fix docs ([d0946f7](https://github.com/infinity-dev6tb7/vulcan/commit/d0946f7c32262b291ec29c2bf464e0d729eb938f))
* fix docstring ([4941b67](https://github.com/infinity-dev6tb7/vulcan/commit/4941b679593f8efa8ae1de9c2db414cd00205d2e))
* fix docstring ([3754e08](https://github.com/infinity-dev6tb7/vulcan/commit/3754e08d4cfa0abc9713f1aa1ee998354fbc9e04))
* fix docstring ([52d0852](https://github.com/infinity-dev6tb7/vulcan/commit/52d08529023d4b7b1ecc4ef534dd020b2d7d3406))
* fix docstrings ([e0a89d3](https://github.com/infinity-dev6tb7/vulcan/commit/e0a89d30072a4acdbb7275f1256906118444d571))
* fix expect logs ([9caf992](https://github.com/infinity-dev6tb7/vulcan/commit/9caf992f01de56a1853ddb5094e9d1818142423c))
* fix expect revert tests ([f34ef56](https://github.com/infinity-dev6tb7/vulcan/commit/f34ef56e09ea88823f6443ac612030eca851496c))
* fix file exists ([#228](https://github.com/infinity-dev6tb7/vulcan/issues/228)) ([8ea5e24](https://github.com/infinity-dev6tb7/vulcan/commit/8ea5e24bdf9b7bd467be1950903c372dbff799fd))
* fix import ([485bd01](https://github.com/infinity-dev6tb7/vulcan/commit/485bd01ffee4cb9ee2f02e091750795a1155544e))
* fix indentation ([75a68b8](https://github.com/infinity-dev6tb7/vulcan/commit/75a68b8f7c3d3984d2582b0a590b54c2f6cc9aa9))
* fix loop ([b9f61dd](https://github.com/infinity-dev6tb7/vulcan/commit/b9f61dd56d5246cdf2a7475ba275b6c2b66d9689))
* fix merge ([3d87d4f](https://github.com/infinity-dev6tb7/vulcan/commit/3d87d4fd9fed4dcfac0278901571782ddebba158))
* fix return natspect documentation ([6825707](https://github.com/infinity-dev6tb7/vulcan/commit/6825707016703f8d9cf8db0a0e9bbf6672b04b7a))
* fix stack too deep error ([7bab225](https://github.com/infinity-dev6tb7/vulcan/commit/7bab225693af894c8eb8fe699a50953aa2bdf3eb))
* fix start and end ([a7eea1b](https://github.com/infinity-dev6tb7/vulcan/commit/a7eea1b4d8602232fb47cfd5d4c697a9f286350d))
* fix warning ([d0b8a62](https://github.com/infinity-dev6tb7/vulcan/commit/d0b8a6215f46190e05b2506f4fc7dd04d9589be8))
* remove duplicated check ([b045b52](https://github.com/infinity-dev6tb7/vulcan/commit/b045b52ba9429c95c06a55510c0bb11cb485bdbe))
* remove isStaticCall example ([5f994d2](https://github.com/infinity-dev6tb7/vulcan/commit/5f994d25ecee60f5531e1bfd58e4dec253508dc7))
* remove selfdestruct ([a8f2832](https://github.com/infinity-dev6tb7/vulcan/commit/a8f283241dcca28ec686a4c79b26b861af17d15f))
* remove some warnings ([5476535](https://github.com/infinity-dev6tb7/vulcan/commit/5476535fd4a8c4eb7db319f7a7beae7c3bcbe276))
* remove warnings ([4d5903e](https://github.com/infinity-dev6tb7/vulcan/commit/4d5903ef0ee2f7fc6280451b6964734c42a547dd))
* remove warnings ([6ed5cb3](https://github.com/infinity-dev6tb7/vulcan/commit/6ed5cb3b404161f7e388795d2dea6f0f6135edea))
* set watcher code to empty on stop ([97707ae](https://github.com/infinity-dev6tb7/vulcan/commit/97707ae24286888689d0efa346f9e6b599302d41))
* shorter comments ([9f6283d](https://github.com/infinity-dev6tb7/vulcan/commit/9f6283d4d1a002a105ce6039a3bde4f759523e35))
* swap write/read ([632200a](https://github.com/infinity-dev6tb7/vulcan/commit/632200a4c4f9d250007d6de4b937408df29a8b5b))
* tabs ([3734019](https://github.com/infinity-dev6tb7/vulcan/commit/3734019bf0094e551569d9b8d9bd1525fd2c9baf))
* typo ([9c54139](https://github.com/infinity-dev6tb7/vulcan/commit/9c54139bfe2e4e9160f93be1cc363ad9ba91c7ce))
* update code examples ([91ce2ec](https://github.com/infinity-dev6tb7/vulcan/commit/91ce2ec799d13c50f640e7f993c0bfdc6aa2d24a))
* update forge-std ([#214](https://github.com/infinity-dev6tb7/vulcan/issues/214)) ([fa15aea](https://github.com/infinity-dev6tb7/vulcan/commit/fa15aeadb4942ccbedbdf8705f288e3154d73424))
* update import ([24861bb](https://github.com/infinity-dev6tb7/vulcan/commit/24861bb2f4f02eebb1bf7cdd0a160a4d9dbb8108))
* use an address &gt;= 10 for setCode test ([570a55a](https://github.com/infinity-dev6tb7/vulcan/commit/570a55aca2604d512d05da987b9f7f7a50d1cf50))
* use forge@v1.6.1 ([#210](https://github.com/infinity-dev6tb7/vulcan/issues/210)) ([83243e5](https://github.com/infinity-dev6tb7/vulcan/commit/83243e54b12a31a20614b425df3aa4d678d94f10))
* use shorter comments on accounts ([faf0c0c](https://github.com/infinity-dev6tb7/vulcan/commit/faf0c0ccac0459ed33652c6ac6afa591fc9cfb2a))
* use try/catch on `stopPrank` ([9831acb](https://github.com/infinity-dev6tb7/vulcan/commit/9831acb74c4317708279965a3d1279c2c58c7db6))

## [0.4.7](https://github.com/nomoixyz/vulcan/compare/v0.4.6...v0.4.7) (2024-02-23)


### Features

* install forge-std@v1.7.6 ([6a102f5](https://github.com/nomoixyz/vulcan/commit/6a102f5f99c11f923e70cf40be1c70dc50953cb9))
* string to json ([#238](https://github.com/nomoixyz/vulcan/issues/238)) ([f67740f](https://github.com/nomoixyz/vulcan/commit/f67740f8a9c846a543aebf29433ad69c3f0ff337))
* update forge-std ([#240](https://github.com/nomoixyz/vulcan/issues/240)) ([943b0d3](https://github.com/nomoixyz/vulcan/commit/943b0d33b0111caf18fae3594f1ca89e925bac58))

## [0.4.6](https://github.com/nomoixyz/vulcan/compare/v0.4.5...v0.4.6) (2023-11-27)


### Features

* rpc module ([#236](https://github.com/nomoixyz/vulcan/issues/236)) ([d02a2ac](https://github.com/nomoixyz/vulcan/commit/d02a2ac5cb8bf3d64e014d8a55ab2f475712c65b))
* update forge-std to v1.7.3 ([95ce186](https://github.com/nomoixyz/vulcan/commit/95ce1863037a91a7c8db5f9d631ecc625243f4c9))

## [0.4.5](https://github.com/nomoixyz/vulcan/compare/v0.4.4...v0.4.5) (2023-11-07)


### Features

* add message to expect utilities ([#231](https://github.com/nomoixyz/vulcan/issues/231)) ([7e0754a](https://github.com/nomoixyz/vulcan/commit/7e0754a8c6e5e21852895d5dd5981b4a794f0b9b))

## [0.4.4](https://github.com/nomoixyz/vulcan/compare/v0.4.3...v0.4.4) (2023-11-07)


### Bug Fixes

* fix file exists ([#228](https://github.com/nomoixyz/vulcan/issues/228)) ([c02feb1](https://github.com/nomoixyz/vulcan/commit/c02feb19aa34449376f52805663414aefafdc06a))

## [0.4.3](https://github.com/nomoixyz/vulcan/compare/v0.4.2...v0.4.3) (2023-10-26)


### Features

* new project structure ([#220](https://github.com/nomoixyz/vulcan/issues/220)) ([2d45c4c](https://github.com/nomoixyz/vulcan/commit/2d45c4c9b5072f218514997e6e656d3c2a10262e))


### Bug Fixes

* fix cast abi-encode command ([#226](https://github.com/nomoixyz/vulcan/issues/226)) ([b340aaf](https://github.com/nomoixyz/vulcan/commit/b340aafad4b2efcdb4d0c983ee6d02c79c1c1dea))

## [0.4.2](https://github.com/nomoixyz/vulcan/compare/v0.4.1...v0.4.2) (2023-10-10)


### Bug Fixes

* update forge-std ([#214](https://github.com/nomoixyz/vulcan/issues/214)) ([8e3fb60](https://github.com/nomoixyz/vulcan/commit/8e3fb600b34b8ece7e2ff43b2f59ce01919ad611))

## [0.4.1](https://github.com/nomoixyz/vulcan/compare/v0.4.0...v0.4.1) (2023-10-03)


### Bug Fixes

* add missing imports on script.sol ([#212](https://github.com/nomoixyz/vulcan/issues/212)) ([294c9d9](https://github.com/nomoixyz/vulcan/commit/294c9d9079b8d0045bbe2b33e7021665c6e0fe53))
* use forge@v1.6.1 ([#210](https://github.com/nomoixyz/vulcan/issues/210)) ([bda8bf0](https://github.com/nomoixyz/vulcan/commit/bda8bf0df6daf609ec03bae7ebbaed099438a396))

## [0.4.0](https://github.com/nomoixyz/vulcan/compare/v0.3.1...v0.4.0) (2023-10-02)


### ⚠ BREAKING CHANGES

* use results on fs module ([#191](https://github.com/nomoixyz/vulcan/issues/191))
* use custom types for Results and Error, and use error functions ([#189](https://github.com/nomoixyz/vulcan/issues/189))
* remove Results from json setters ([#182](https://github.com/nomoixyz/vulcan/issues/182))
* add results to commands ([#179](https://github.com/nomoixyz/vulcan/issues/179))

### Features

* add basic types to pointer casting ([#198](https://github.com/nomoixyz/vulcan/issues/198)) ([5f96f7b](https://github.com/nomoixyz/vulcan/commit/5f96f7b254c12684e579666a7a05f8bce7a3afce))
* add results to commands ([#179](https://github.com/nomoixyz/vulcan/issues/179)) ([9770c9e](https://github.com/nomoixyz/vulcan/commit/9770c9ef2f58c638a4d25c33487cee5bf11ce103))
* add semver module ([#204](https://github.com/nomoixyz/vulcan/issues/204)) ([b4a687b](https://github.com/nomoixyz/vulcan/commit/b4a687b1fd2d6d355e11bf4581ef1cc7fb2bec27))
* improved json validation using Results ([#178](https://github.com/nomoixyz/vulcan/issues/178)) ([50b1d14](https://github.com/nomoixyz/vulcan/commit/50b1d14439866ac1cf76a4be959b5631184c88aa))
* remove Results from json setters ([#182](https://github.com/nomoixyz/vulcan/issues/182)) ([6a601ae](https://github.com/nomoixyz/vulcan/commit/6a601ae623a3aa6c84b42270636c2d46ef630ba6))
* request module ([#174](https://github.com/nomoixyz/vulcan/issues/174)) ([63b58b4](https://github.com/nomoixyz/vulcan/commit/63b58b4803d50ad62e131ba344046bb054adb52f))
* use `serializeJson` cheatcode ([#196](https://github.com/nomoixyz/vulcan/issues/196)) ([6a90b1b](https://github.com/nomoixyz/vulcan/commit/6a90b1bea3a14b87c59ddf8edc2721d463b43d22))
* use custom types for Results and Error, and use error functions ([#189](https://github.com/nomoixyz/vulcan/issues/189)) ([4e69e1c](https://github.com/nomoixyz/vulcan/commit/4e69e1cd7f9beadcfead37fafc0d0ea5ee37599f))
* use forge-std@705263c ([#195](https://github.com/nomoixyz/vulcan/issues/195)) ([392d99e](https://github.com/nomoixyz/vulcan/commit/392d99e4525c642cae1da577e274326fcefa4de2))
* use results on fs module ([#191](https://github.com/nomoixyz/vulcan/issues/191)) ([f2998a1](https://github.com/nomoixyz/vulcan/commit/f2998a1821132d9fbb8fda8ef807de61d6dc0bf3))

## [0.3.1](https://github.com/nomoixyz/vulcan/compare/v0.3.0...v0.3.1) (2023-09-01)


### Bug Fixes

* adapt to new forge-std Vm to remove warnings ([e83ebd4](https://github.com/nomoixyz/vulcan/commit/e83ebd403e1e46d3cbf684343e967478bf0a8e29))

## [0.3.0](https://github.com/nomoixyz/vulcan/compare/v0.2.0...v0.3.0) (2023-09-01)


### Features

* add function to create empty command ([2c31886](https://github.com/nomoixyz/vulcan/commit/2c31886075fae5a5177410739309ff38ed834f2a))
* export Command struct from script.sol ([c88883a](https://github.com/nomoixyz/vulcan/commit/c88883a402ccfae6aa2d0de674936ba22e3d3514))


### Bug Fixes

* fix return natspect documentation ([5da4ad1](https://github.com/nomoixyz/vulcan/commit/5da4ad14fbe07b35d29260fe2cb97ffb2cb95de3))
* tabs ([1d4c0b9](https://github.com/nomoixyz/vulcan/commit/1d4c0b9d350445825d84198c7b242f5e432ffb39))
* update code examples ([953d661](https://github.com/nomoixyz/vulcan/commit/953d661e1a84e84b9a40b8f8178980ea32d0ef96))
