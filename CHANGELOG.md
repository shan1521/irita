<!--
Guiding Principles:

Changelogs are for humans, not machines.
There should be an entry for every single version.
The same types of changes should be grouped.
Versions and sections should be linkable.
The latest version comes first.
The release date of each version is displayed.
Mention whether you follow Semantic Versioning.

Usage:

Change log entries are to be added to the Unreleased section under the
appropriate stanza (see below). Each entry should ideally include a tag and
the Github issue reference in the following format:

* (<tag>) \#<issue-number> message

The issue numbers will later be link-ified during the release process so you do
not have to worry about including a link manually, but you can if you wish.

Types of changes (Stanzas):

"Features" for new features.
"Improvements" for changes in existing functionality.
"Deprecated" for soon-to-be removed features.
"Bug Fixes" for any bug fixes.
"Breaking" for breaking API changes.

Ref: https://keepachangelog.com/en/1.0.0/
-->

# Changelog

## [Unreleased]

## [v3.0.0]
*December 31, 2021*

### Application

* [\#161](https://github.com/bianjieai/irita/pull/161) Add EVM Support
* (modules/perm) [\#33](https://github.com/bianjieai/iritamod/pull/33) Add EVM contract permission management

## [v2.1.1]
*December 8, 2021*
### Application

* [iritamod \#32](https://github.com/bianjieai/iritamod/pull/32) (modules/identity) add `data` field, and the field length limit is only related to the block and transaction size limit.

## [v2.1.0]

*November 1, 2021*

### Application


* [\#135](https://github.com/bianjieai/irita/pull/135) Bump cosmos-sdk version to [v0.44.2](https://github.com/cosmos/cosmos-sdk/releases/tag/v0.44.2)
* [\#130](https://github.com/bianjieai/irita/pull/130) Integrated tibc protocol
* [irismod \#189](https://github.com/irisnet/irismod/pull/189) Enhance nft module

### Breaking Changes

* [cosmos-sdk \#9594](https://github.com/cosmos/cosmos-sdk/pull/9594) Remove legacy REST API. Please see the [REST Endpoints Migration guide](https://docs.cosmos.network/master/migrations/rest.html) to migrate to the new REST endpoints.


## [v2.0.0] - 2021-04-26

### Features

* build irita v2.0 based on
  * [cosmos-sdk v0.42.3](https://github.com/bianjieai/cosmos-sdk/releases/tag/v0.42.3-irita-210413)
  * [tendermint v0.34.8](https://github.com/bianjieai/tendermint/releases/tag/v0.34.8-irita-210413)
  * [iritamod v1.0.0](https://github.com/bianjieai/iritamod/releases/tag/v1.0.0)
  * [irismod v1.4.0](https://github.com/irisnet/irismod/releases/tag/v1.4.0)
  * [wasmd v0.15.1](https://github.com/CosmWasm/wasmd/releases/tag/v0.15.1)

<!-- Release links -->

[v2.1.1]: https://github.com/bianjieai/irita/releases/tag/v2.1.1
[v2.1.0]: https://github.com/bianjieai/irita/releases/tag/v2.1.0
[v2.0.0]: https://github.com/bianjieai/irita/releases/tag/v2.0.0
