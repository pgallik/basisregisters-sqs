## [2.1.3](https://github.com/informatievlaanderen/basisregisters-sqs/compare/v2.1.2...v2.1.3) (2023-04-18)


### Bug Fixes

* Updated ticketing service abstractions ([d212aca](https://github.com/informatievlaanderen/basisregisters-sqs/commit/d212acad2720043038705744b6ada9bee4a2c61d))

## [2.1.2](https://github.com/informatievlaanderen/basisregisters-sqs/compare/v2.1.1...v2.1.2) (2023-04-18)


### Bug Fixes

* style to trigger build ([2eb5d00](https://github.com/informatievlaanderen/basisregisters-sqs/commit/2eb5d0027b4061be7c58b859fa30a72ab074bc2d))

## [2.1.1](https://github.com/informatievlaanderen/basisregisters-sqs/compare/v2.1.0...v2.1.1) (2023-04-18)


### Bug Fixes

* Incorrect TicketError construction ([02d1232](https://github.com/informatievlaanderen/basisregisters-sqs/commit/02d123261f91a882e684126fd2af664f7da04470))

# [2.1.0](https://github.com/informatievlaanderen/basisregisters-sqs/compare/v2.0.3...v2.1.0) (2023-04-17)


### Bug Fixes

* Updated library into latest ticketing system version ([b6e0d3d](https://github.com/informatievlaanderen/basisregisters-sqs/commit/b6e0d3ddbc0e8f70a9851e1afd1a17b0587acf44))


### Features

* Added support for validation exceptions inside ticketing service ([eb7c37e](https://github.com/informatievlaanderen/basisregisters-sqs/commit/eb7c37e9d1198a63fbca4ad87002431660d43805))

## [2.0.3](https://github.com/informatievlaanderen/basisregisters-sqs/compare/v2.0.2...v2.0.3) (2023-03-30)


### Bug Fixes

* bump messagehandling ([c58e4e8](https://github.com/informatievlaanderen/basisregisters-sqs/commit/c58e4e8c00fc8943c5755b7f05df2591ff89edd2))

## [2.0.2](https://github.com/informatievlaanderen/basisregisters-sqs/compare/v2.0.1...v2.0.2) (2023-03-23)


### Bug Fixes

* style to trigger build ([3df2bbf](https://github.com/informatievlaanderen/basisregisters-sqs/commit/3df2bbfbefefe691e8418ed07f231cd8023b4de7))
* style to trigger build ([2bd119d](https://github.com/informatievlaanderen/basisregisters-sqs/commit/2bd119dce5ebaf5be7617a960e4ee5d2e85757a3))

## [2.0.1](https://github.com/informatievlaanderen/basisregisters-sqs/compare/v2.0.0...v2.0.1) (2023-03-21)


### Bug Fixes

* style add new line EOF to bump build ([7845736](https://github.com/informatievlaanderen/basisregisters-sqs/commit/784573682cf55ee0f50ddaf53782f0667e76160c))

# [2.0.0](https://github.com/informatievlaanderen/basisregisters-sqs/compare/v1.3.1...v2.0.0) (2023-03-21)


### Code Refactoring

* sqsLambdaHandlerBase.InnerHandle now returns Task<object> ([4d63753](https://github.com/informatievlaanderen/basisregisters-sqs/commit/4d6375369a02065744bf3ab015100249b55feab9))


### BREAKING CHANGES

* sqsLambdaHandlerBase.InnerHandle now returns Task<object> instead of
Task<ETagResponse>

## [1.3.1](https://github.com/informatievlaanderen/basisregisters-sqs/compare/v1.3.0...v1.3.1) (2023-02-27)


### Bug Fixes

* bump mediatr ([bbf9229](https://github.com/informatievlaanderen/basisregisters-sqs/commit/bbf92297733d3e0cad43bb608c5189ed47c9262c))
* remove test from build.yml ([f68bf4a](https://github.com/informatievlaanderen/basisregisters-sqs/commit/f68bf4ad4fa01e70f88dd31f31a466acbe77910d))

# [1.3.0](https://github.com/informatievlaanderen/basisregisters-sqs/compare/v1.2.0...v1.3.0) (2022-10-26)


### Features

* remove DetailUrlFormat property from SqsLambdaHandlerBase ([8b45c44](https://github.com/informatievlaanderen/basisregisters-sqs/commit/8b45c442c1ea4d51af942f1acd034a26e4e1758c))

# [1.2.0](https://github.com/informatievlaanderen/basisregisters-sqs/compare/v1.1.7...v1.2.0) (2022-10-24)


### Features

* make sqsLambdaRequest a record ([7ec1df4](https://github.com/informatievlaanderen/basisregisters-sqs/commit/7ec1df4dbc03e966ed883a0bb58c4ed42fa3eb73))

## [1.1.7](https://github.com/informatievlaanderen/basisregisters-sqs/compare/v1.1.6...v1.1.7) (2022-10-17)


### Bug Fixes

* update dependencies ([8237466](https://github.com/informatievlaanderen/basisregisters-sqs/commit/8237466b8e9a823f050afe0f4eda46110692c210))

## [1.1.6](https://github.com/informatievlaanderen/basisregisters-sqs/compare/v1.1.5...v1.1.6) (2022-10-17)


### Bug Fixes

* rename HandleAggregateIdIsNotFoundException ([3b40e04](https://github.com/informatievlaanderen/basisregisters-sqs/commit/3b40e04700b84bd76d0670b57a0d1fdf8e40b14f))

## [1.1.5](https://github.com/informatievlaanderen/basisregisters-sqs/compare/v1.1.4...v1.1.5) (2022-10-14)


### Bug Fixes

* use ef core 6.0.3 ([b6eb146](https://github.com/informatievlaanderen/basisregisters-sqs/commit/b6eb14664c046c362f25c782c202829a20e3d2b8))

## [1.1.4](https://github.com/informatievlaanderen/basisregisters-sqs/compare/v1.1.3...v1.1.4) (2022-10-14)


### Bug Fixes

* push to nuget ([aa8a8ec](https://github.com/informatievlaanderen/basisregisters-sqs/commit/aa8a8ec7258f460ee0ae5b9fd637dcf393d350ca))

## [1.1.3](https://github.com/informatievlaanderen/basisregisters-sqs/compare/v1.1.2...v1.1.3) (2022-10-14)


### Bug Fixes

* build.fsx Pack ([dd01086](https://github.com/informatievlaanderen/basisregisters-sqs/commit/dd0108640779d2afe130a16c12c22461e955790b))

## [1.1.2](https://github.com/informatievlaanderen/basisregisters-sqs/compare/v1.1.1...v1.1.2) (2022-10-14)


### Bug Fixes

* dummy commit ([640ab7f](https://github.com/informatievlaanderen/basisregisters-sqs/commit/640ab7fa1413c375a8b5d35183c974506d5adba0))

## [1.1.1](https://github.com/informatievlaanderen/basisregisters-sqs/compare/v1.1.0...v1.1.1) (2022-10-14)


### Bug Fixes

* fix lambda paket.template ([d77adf9](https://github.com/informatievlaanderen/basisregisters-sqs/commit/d77adf9f070e36b453bef49ec81891fd524a155e))

# [1.1.0](https://github.com/informatievlaanderen/basisregisters-sqs/compare/v1.0.10...v1.1.0) (2022-10-14)


### Bug Fixes

* add IfMatchHeaderValueMismatchException ([fb0c721](https://github.com/informatievlaanderen/basisregisters-sqs/commit/fb0c7213ca37f747a0935b22b923dc05fd0bba26))
* fix build.fsx & release.yml ([4cbb666](https://github.com/informatievlaanderen/basisregisters-sqs/commit/4cbb666f6d784fbc252bc65d501b4e03d1e511ca))
* use file-scoped namespaces ([ebcf06b](https://github.com/informatievlaanderen/basisregisters-sqs/commit/ebcf06b604eea6e62e8358afe22c4070229eac36))


### Features

* add lambda code ([5da0729](https://github.com/informatievlaanderen/basisregisters-sqs/commit/5da0729402221e5c2735c32f5ccb5ece9fc96d8d))

## [1.0.10](https://github.com/informatievlaanderen/basisregisters-sqs/compare/v1.0.9...v1.0.10) (2022-10-14)


### Bug Fixes

* dummy commit ([1d5f28b](https://github.com/informatievlaanderen/basisregisters-sqs/commit/1d5f28b30b472de7d56cc1809eee9da352c540bb))

## [1.0.9](https://github.com/informatievlaanderen/basisregisters-sqs/compare/v1.0.8...v1.0.9) (2022-10-14)


### Bug Fixes

* add ETagResponse ([54637ae](https://github.com/informatievlaanderen/basisregisters-sqs/commit/54637aeb35a3b26f67537d3b8a2a6598b5963ec3))

## [1.0.8](https://github.com/informatievlaanderen/basisregisters-sqs/compare/v1.0.7...v1.0.8) (2022-10-13)


### Bug Fixes

* fix nuget path ([53fcf3e](https://github.com/informatievlaanderen/basisregisters-sqs/commit/53fcf3ed6704f16654a8cf600da23d765dcb4720))

## [1.0.7](https://github.com/informatievlaanderen/basisregisters-sqs/compare/v1.0.6...v1.0.7) (2022-10-13)


### Bug Fixes

* change README.md ([af56ceb](https://github.com/informatievlaanderen/basisregisters-sqs/commit/af56cebbc3bf21d298e1d17eb7a1e3caed3b489e))

## [1.0.6](https://github.com/informatievlaanderen/basisregisters-sqs/compare/v1.0.5...v1.0.6) (2022-10-13)


### Bug Fixes

* fix nuget push ([#22](https://github.com/informatievlaanderen/basisregisters-sqs/issues/22)) ([11a171e](https://github.com/informatievlaanderen/basisregisters-sqs/commit/11a171e8ea1b313ee81530e7f23ad02c0b022776))

## [1.0.5](https://github.com/informatievlaanderen/basisregisters-sqs/compare/v1.0.4...v1.0.5) (2022-10-13)


### Bug Fixes

* release workflow nuget ([e8d6aca](https://github.com/informatievlaanderen/basisregisters-sqs/commit/e8d6aca63ee63646774ca3e89429cd1bb45693c4))

## [1.0.4](https://github.com/informatievlaanderen/basisregisters-sqs/compare/v1.0.3...v1.0.4) (2022-10-13)


### Bug Fixes

* change README.md ([be87833](https://github.com/informatievlaanderen/basisregisters-sqs/commit/be8783377de7cffcd51efd3e0c867075259a3891))

## [1.0.3](https://github.com/informatievlaanderen/basisregisters-sqs/compare/v1.0.2...v1.0.3) (2022-10-13)


### Bug Fixes

* fix csproj ([e2ee101](https://github.com/informatievlaanderen/basisregisters-sqs/commit/e2ee101eb16bd97e7e1beebb03d10d8b5aca1573))
* restore pack folder ([9bea5f4](https://github.com/informatievlaanderen/basisregisters-sqs/commit/9bea5f413690397c6d635a6a3a01a12ac4ec3ed8))
* trying publish folder for nuget ([b0379c5](https://github.com/informatievlaanderen/basisregisters-sqs/commit/b0379c594d6f0fbe5e7b6e13addbf7d38f1a58b0))

## [1.0.2](https://github.com/informatievlaanderen/basisregisters-sqs/compare/v1.0.1...v1.0.2) (2022-10-12)


### Bug Fixes

* fix build.fsx for nuget ([d830efa](https://github.com/informatievlaanderen/basisregisters-sqs/commit/d830efa2916db64e31aa71262caa33b00472dbe2))
* fix nuget ([fde8564](https://github.com/informatievlaanderen/basisregisters-sqs/commit/fde85647d9600a56494338cd2a80191ad4491343))
* fix nuget ([0dadc9b](https://github.com/informatievlaanderen/basisregisters-sqs/commit/0dadc9bbebb1aee7a46692aa0ee59c99c0332775))
* fix paket.template ([e8db20f](https://github.com/informatievlaanderen/basisregisters-sqs/commit/e8db20f70089f9c8a0ffe8186f5c04aa5b6890bf))
* ignore Lib_Pack? ([fbb5ff8](https://github.com/informatievlaanderen/basisregisters-sqs/commit/fbb5ff8824783fba150ff58ce4be9176b9846a23))

## [1.0.1](https://github.com/informatievlaanderen/basisregisters-sqs/compare/v1.0.0...v1.0.1) (2022-10-12)


### Bug Fixes

* add nuget to build.fsx ([9ad38e9](https://github.com/informatievlaanderen/basisregisters-sqs/commit/9ad38e9f9b39abc3cf5cb0297bbd2a263cef1865))

# 1.0.0 (2022-10-12)


### Bug Fixes

* add npm ([3bc2de1](https://github.com/informatievlaanderen/basisregisters-sqs/commit/3bc2de11c63b5cfb66aedc7644b66984f425e34a))
* fix build.fsx ([10ee664](https://github.com/informatievlaanderen/basisregisters-sqs/commit/10ee6648e45b98545e5349d1046a20cd1696b248))
* fix build.yml ([2690b96](https://github.com/informatievlaanderen/basisregisters-sqs/commit/2690b96e45f242eb6ddaa54c6e27fbe400912ee5))
* fix npm ([ce53049](https://github.com/informatievlaanderen/basisregisters-sqs/commit/ce53049f3b5e0378e212316dd56eb342087fcc49))
* make build.sh executable ([20a5bd4](https://github.com/informatievlaanderen/basisregisters-sqs/commit/20a5bd469ad19dfc35f27532a6e45c13c3f28411))


### Features

* initial commit ([06ecdc6](https://github.com/informatievlaanderen/basisregisters-sqs/commit/06ecdc6ae29ac9a762cbd5d1356d0ea30189a146))
* initial commit ([#5](https://github.com/informatievlaanderen/basisregisters-sqs/issues/5)) ([8083fe8](https://github.com/informatievlaanderen/basisregisters-sqs/commit/8083fe88f22f075073debb94feef13b248d13b9b))
