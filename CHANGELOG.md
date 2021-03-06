# Change Log

All notable changes to this project will be documented in this file.
See [Conventional Commits](https://conventionalcommits.org) for commit guidelines.

## [0.5.7](https://github.com/decentralized-identity/element/compare/v0.5.6...v0.5.7) (2020-03-03)

**Note:** Version bump only for package @transmute/element





## [0.5.6](https://github.com/decentralized-identity/element/compare/v0.5.5...v0.5.6) (2020-03-03)

**Note:** Version bump only for package @transmute/element





## [0.5.5](https://github.com/decentralized-identity/element/compare/v0.5.4...v0.5.5) (2020-03-03)

**Note:** Version bump only for package @transmute/element





## [0.5.4](https://github.com/decentralized-identity/element/compare/v0.5.3...v0.5.4) (2020-03-02)

**Note:** Version bump only for package @transmute/element





## [0.5.3](https://github.com/decentralized-identity/element/compare/v0.5.2...v0.5.3) (2020-03-02)


### Features

* update couchdb to latest version ([05a1418](https://github.com/decentralized-identity/element/commit/05a1418))





## [0.5.2](https://github.com/decentralized-identity/element/compare/v0.5.1...v0.5.2) (2020-02-17)

**Note:** Version bump only for package @transmute/element





## [0.5.1](https://github.com/decentralized-identity/element/compare/v0.5.0...v0.5.1) (2020-02-17)

**Note:** Version bump only for package @transmute/element





# [0.5.0](https://github.com/decentralized-identity/element/compare/v0.4.4...v0.5.0) (2020-02-17)


### Bug Fixes

* make api node 10 ([219dd0f](https://github.com/decentralized-identity/element/commit/219dd0f))
* qr code mobile view and page refresh bug ([fa769a8](https://github.com/decentralized-identity/element/commit/fa769a8))





## [0.4.4](https://github.com/decentralized-identity/element/compare/v0.4.3...v0.4.4) (2020-01-24)


### Bug Fixes

* fix key of operation list to be unique ([79ba1f3](https://github.com/decentralized-identity/element/commit/79ba1f3))
* lint errors and warnings ([f0b4097](https://github.com/decentralized-identity/element/commit/f0b4097))
* page crash with no keystore ([50cd780](https://github.com/decentralized-identity/element/commit/50cd780))


### Features

* add a sidetree func to order operations by transactionNumber ([38534b0](https://github.com/decentralized-identity/element/commit/38534b0))
* add publicKeyJwk IRIs ([a113d49](https://github.com/decentralized-identity/element/commit/a113d49))
* add scripts for the couchdb service ([43618e3](https://github.com/decentralized-identity/element/commit/43618e3))
* order transactions after reading them from cache ([ac4db39](https://github.com/decentralized-identity/element/commit/ac4db39))
* update ElementCouchDBAdapter to default to local couchdb ([7f4eafe](https://github.com/decentralized-identity/element/commit/7f4eafe))
* update json ld context ([010b27e](https://github.com/decentralized-identity/element/commit/010b27e))





## [0.4.3](https://github.com/decentralized-identity/element/compare/v0.4.2...v0.4.3) (2020-01-14)


### Bug Fixes

* add publicKeyJwk to JSON schemas ([9b81717](https://github.com/decentralized-identity/element/commit/9b81717))





## [0.4.2](https://github.com/decentralized-identity/element/compare/v0.4.1...v0.4.2) (2020-01-11)


### Features

* add controller property in did documents public keys ([7c64d8e](https://github.com/decentralized-identity/element/commit/7c64d8e))





## [0.4.1](https://github.com/decentralized-identity/element/compare/v0.4.0...v0.4.1) (2020-01-09)


### Features

* add support for setting up edv properties ([c8008de](https://github.com/decentralized-identity/element/commit/c8008de))
* add toFullyQualifiedDidDocument func ([c6e68e8](https://github.com/decentralized-identity/element/commit/c6e68e8))
* add X25519KeyPair to crypto module ([61c3703](https://github.com/decentralized-identity/element/commit/61c3703))





# [0.4.0](https://github.com/decentralized-identity/element/compare/v0.3.0...v0.4.0) (2020-01-07)


### Bug Fixes

* eslint setup ([24be4e8](https://github.com/decentralized-identity/element/commit/24be4e8))
* fix AddKeyDialog key creation ([7fe2731](https://github.com/decentralized-identity/element/commit/7fe2731))
* recovery id bug ([90f1725](https://github.com/decentralized-identity/element/commit/90f1725))


### Features

* add ed25519 key to default wallet ([d8d6092](https://github.com/decentralized-identity/element/commit/d8d6092))
* add RSA as valid key type ([2e33c5c](https://github.com/decentralized-identity/element/commit/2e33c5c))
* add sidetree context to element ([a34b872](https://github.com/decentralized-identity/element/commit/a34b872))
* add support for service and proof ([9aa0bea](https://github.com/decentralized-identity/element/commit/9aa0bea))
* display key in did document regardless of its encoding ([2e9f539](https://github.com/decentralized-identity/element/commit/2e9f539))
* update schema to support did-key ([8c00433](https://github.com/decentralized-identity/element/commit/8c00433))
* upgrade did-wallet version ([dd2b223](https://github.com/decentralized-identity/element/commit/dd2b223))
* use Firestore adapter for API ([7e89daa](https://github.com/decentralized-identity/element/commit/7e89daa))





# [0.3.0](https://github.com/decentralized-identity/element/compare/v0.2.0...v0.3.0) (2019-12-20)


### Bug Fixes

* add transactionHash to rxdb schema ([e85bfbf](https://github.com/decentralized-identity/element/commit/e85bfbf))
* addressed missing changes ([8e799ed](https://github.com/decentralized-identity/element/commit/8e799ed))
* bug where operations could be overriden ([0ca42a9](https://github.com/decentralized-identity/element/commit/0ca42a9))
* cache instance for faster getTransactions ([200cc65](https://github.com/decentralized-identity/element/commit/200cc65))
* createDIDRequest to use the recovery key ([dbfc319](https://github.com/decentralized-identity/element/commit/dbfc319))
* dequeue processed operations in batchWrite ([3ba129b](https://github.com/decentralized-identity/element/commit/3ba129b))
* dont mark a partially synced transaction as synced ([698dab0](https://github.com/decentralized-identity/element/commit/698dab0))
* fix condition for checking a recovery key ([8f31d07](https://github.com/decentralized-identity/element/commit/8f31d07))
* fix id in key schema ([63ab5f6](https://github.com/decentralized-identity/element/commit/63ab5f6))
* fix payloadToHash to be like sidetree ([3249474](https://github.com/decentralized-identity/element/commit/3249474))
* kid missing # ([7322676](https://github.com/decentralized-identity/element/commit/7322676))
* prevent removing the recovery key ([8b8b172](https://github.com/decentralized-identity/element/commit/8b8b172))
* reduce bundle size for prod ([84de553](https://github.com/decentralized-identity/element/commit/84de553))
* remove watching changes in md files ([b9172b6](https://github.com/decentralized-identity/element/commit/b9172b6))
* test operationHash ([b614b1b](https://github.com/decentralized-identity/element/commit/b614b1b))
* transactionTime in the case where lastTransaction exists ([dd59cc2](https://github.com/decentralized-identity/element/commit/dd59cc2))
* use transactionTime instead of Date.now ([ffbf682](https://github.com/decentralized-identity/element/commit/ffbf682))
* wrong operationHash doesnt match did ([46d3a5c](https://github.com/decentralized-identity/element/commit/46d3a5c))


### Features

* add a batchScheduler ([d308245](https://github.com/decentralized-identity/element/commit/d308245))
* add a didDocumentModel schema ([d9609f7](https://github.com/decentralized-identity/element/commit/d9609f7))
* add a new lastResolvedTransactionTime variable to the cache object ([8ce8973](https://github.com/decentralized-identity/element/commit/8ce8973))
* add a sidetree key schema ([cc40df5](https://github.com/decentralized-identity/element/commit/cc40df5))
* add batchFileToOperations to the func module ([1aec403](https://github.com/decentralized-identity/element/commit/1aec403))
* add couchdb adapter in element-lib ([8be7f94](https://github.com/decentralized-identity/element/commit/8be7f94))
* add flag to activate the just in time feature of the resolver ([82ac820](https://github.com/decentralized-identity/element/commit/82ac820))
* add payload validation in the resolver ([e8e40c2](https://github.com/decentralized-identity/element/commit/e8e40c2))
* add removing a key update ([ff2778e](https://github.com/decentralized-identity/element/commit/ff2778e))
* add signature validation for update operation ([2f8433f](https://github.com/decentralized-identity/element/commit/2f8433f))
* add suport for websql rxdb adapter ([7dd30f9](https://github.com/decentralized-identity/element/commit/7dd30f9))
* add support for delete operation ([33093cb](https://github.com/decentralized-identity/element/commit/33093cb))
* add support for leveldown rxdb adapter ([e5fa056](https://github.com/decentralized-identity/element/commit/e5fa056))
* add transactionTimeHash to getTransactions ([886f9f8](https://github.com/decentralized-identity/element/commit/886f9f8))
* add update operation for adding a new key ([d558d1e](https://github.com/decentralized-identity/element/commit/d558d1e))
* add usage property to getDidDocumentModel ([504327f](https://github.com/decentralized-identity/element/commit/504327f))
* check last operation hash in create operation ([aadb542](https://github.com/decentralized-identity/element/commit/aadb542))
* check signature in create operation ([284f102](https://github.com/decentralized-identity/element/commit/284f102))
* create several keys in did wallet ([a2847f8](https://github.com/decentralized-identity/element/commit/a2847f8))
* fix header encoding for create operation ([dbdb2da](https://github.com/decentralized-identity/element/commit/dbdb2da))
* fix sign and verify to include encoded header ([087ba79](https://github.com/decentralized-identity/element/commit/087ba79))
* getTransactions endpoint ([fd7e7e0](https://github.com/decentralized-identity/element/commit/fd7e7e0))
* implement operation queue ([ac1aad3](https://github.com/decentralized-identity/element/commit/ac1aad3))
* implement recover op ([191f4d5](https://github.com/decentralized-identity/element/commit/191f4d5))
* implement remove did key ([1f0d689](https://github.com/decentralized-identity/element/commit/1f0d689))
* operation validation ([e71220e](https://github.com/decentralized-identity/element/commit/e71220e))
* refactor all operations to use a makeSignedOperation ([b4a5026](https://github.com/decentralized-identity/element/commit/b4a5026))
* refactor resolve to apply operation in the right order ([094186b](https://github.com/decentralized-identity/element/commit/094186b))
* stop syncing transaction after sending to ethereum ([6eedf4a](https://github.com/decentralized-identity/element/commit/6eedf4a))
* throw errors when operation is not valid ([1c3b68b](https://github.com/decentralized-identity/element/commit/1c3b68b))
* use cache for anchorFiles ([9021893](https://github.com/decentralized-identity/element/commit/9021893))
* use couchdb adapter for docker setup ([58d36a5](https://github.com/decentralized-identity/element/commit/58d36a5))
* use previousOperationHash in update ([1c65ced](https://github.com/decentralized-identity/element/commit/1c65ced))
* use usage in getUpdatePayloadForAddingAKey ([25d1ebd](https://github.com/decentralized-identity/element/commit/25d1ebd))





# [0.2.0](https://github.com/decentralized-identity/element/compare/v0.0.2-2...v0.2.0) (2019-11-08)


### Bug Fixes

* fix resolver not working when there is a cache hit ([17021e6](https://github.com/decentralized-identity/element/commit/17021e6))
* **package:** fix bundle for core ([f34436f](https://github.com/decentralized-identity/element/commit/f34436f))
* add a default gas price of 100 GWei ([a65c1b5](https://github.com/decentralized-identity/element/commit/a65c1b5))
* add fromTransactionTime parameter in getTransactions ([247d49b](https://github.com/decentralized-identity/element/commit/247d49b))
* add omitTimestamp flag for resolver ([18eb7f9](https://github.com/decentralized-identity/element/commit/18eb7f9))
* add requirement for node 10 ([3e555e9](https://github.com/decentralized-identity/element/commit/3e555e9))
* add requirement for node 10 ([c2c6cd8](https://github.com/decentralized-identity/element/commit/c2c6cd8))
* await bug ([02974b4](https://github.com/decentralized-identity/element/commit/02974b4))
* fix badOperation ([8282df4](https://github.com/decentralized-identity/element/commit/8282df4))
* fix condition to determine when to use ElementMemoryAdapter ([da074ef](https://github.com/decentralized-identity/element/commit/da074ef))
* increment transactionTime ([4a4cfeb](https://github.com/decentralized-identity/element/commit/4a4cfeb))
* ipfs test ([da1b9fd](https://github.com/decentralized-identity/element/commit/da1b9fd))
* make sure to read ipfs if cache is empty ([672a558](https://github.com/decentralized-identity/element/commit/672a558))
* memory leak in snackbar ([f37e992](https://github.com/decentralized-identity/element/commit/f37e992))
* pin truffle-hdwallet-provider to 1.0.5 ([f355b00](https://github.com/decentralized-identity/element/commit/f355b00))
* proptype warning ([d3edbb9](https://github.com/decentralized-identity/element/commit/d3edbb9))
* remove networkChangedDetected variable ([a291f46](https://github.com/decentralized-identity/element/commit/a291f46))
* simplify ElementFirestoreAdapter constructor ([a3dc196](https://github.com/decentralized-identity/element/commit/a3dc196))
* stop using firebase and only rely on firebase-admin ([9908e0a](https://github.com/decentralized-identity/element/commit/9908e0a))
* storage manager test ([1d70d41](https://github.com/decentralized-identity/element/commit/1d70d41))
* test memory issue ([24c744a](https://github.com/decentralized-identity/element/commit/24c744a))
* test timeout ([ac34551](https://github.com/decentralized-identity/element/commit/ac34551))
* truffle test ([9e96ef7](https://github.com/decentralized-identity/element/commit/9e96ef7))
* **package:** remove tests from dist ([7b11c56](https://github.com/decentralized-identity/element/commit/7b11c56))
* update context to use a did spec that supports publicKeyHex ([91978b1](https://github.com/decentralized-identity/element/commit/91978b1))
* update name of firebase-adminsdk to be more generic ([2d959c4](https://github.com/decentralized-identity/element/commit/2d959c4))
* upgrade web3 version in app ([da1b6a4](https://github.com/decentralized-identity/element/commit/da1b6a4))
* upgrade web3 version in lib ([e9d0a5f](https://github.com/decentralized-identity/element/commit/e9d0a5f))
* use Promise API for web3.eth.getBlock ([7c06dd8](https://github.com/decentralized-identity/element/commit/7c06dd8))
* use rxdb on api ([c2348b8](https://github.com/decentralized-identity/element/commit/c2348b8))
* version of solc to avoid truffle build error ([7493e40](https://github.com/decentralized-identity/element/commit/7493e40))


### Features

* add storage manager ([c97a369](https://github.com/decentralized-identity/element/commit/c97a369))
* add transactionTimestamp ([a8a5291](https://github.com/decentralized-identity/element/commit/a8a5291))
* make storage manager retry interval configurable ([8087d16](https://github.com/decentralized-identity/element/commit/8087d16))
* replace pouchdb with rxdb for app db ([94e390b](https://github.com/decentralized-identity/element/commit/94e390b))
