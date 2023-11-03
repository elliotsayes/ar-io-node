# Changelog

## 1.0.0 (2023-11-03)


### Features

* add support for uploading observer reports PE-4797 ([0c7fa42](https://github.com/elliotsayes/ar-io-node/commit/0c7fa42769e5aafaccb6cfafba92f8fed53e9bfe))
* bump observer version ([4576ef7](https://github.com/elliotsayes/ar-io-node/commit/4576ef7b4c49dd0c72e585afc8cec122956a87c7))
* **envoy:** route /ar-io/observer to the observer service PE-4797 ([52f39b3](https://github.com/elliotsayes/ar-io-node/commit/52f39b3f6c33b1fb7a8400baa50fd2a6cbfca828))
* expose X-ArNS-* headers for CORS requests ([ee03255](https://github.com/elliotsayes/ar-io-node/commit/ee032553ec485cb056cb4285f4953b8dd267865b))
* **info observer:** advertise the contract ID in use PE-4894 ([4dd26c8](https://github.com/elliotsayes/ar-io-node/commit/4dd26c8a45481409455068c8acd7fba5e30682ac))
* **observer:** add observer service to docker-compose config PE-4797 ([209ad85](https://github.com/elliotsayes/ar-io-node/commit/209ad850421c2ee2b4424ee371fce7d37bd48fd2))
* **observer:** bump image to add ARM support PE-4870 ([c3856b3](https://github.com/elliotsayes/ar-io-node/commit/c3856b3cb67ebae2fb246f5b60325fea0d158eba))
* **observer:** bump version for better missing wallet handing PE-4749 ([8035bb4](https://github.com/elliotsayes/ar-io-node/commit/8035bb4b5465178f52227f74f753d481f8780d65))
* **observer:** enable observer by default PE-4749 ([0d6b6a8](https://github.com/elliotsayes/ar-io-node/commit/0d6b6a86a8c96b85ca197d024120826157fa8ebc))
* rename OBSERVER_DATA_PATH to REPORTS_DATA_PATH PE-4816 ([1a2dfbf](https://github.com/elliotsayes/ar-io-node/commit/1a2dfbfd926a88977b33ec889d08d47e73bb0b7e))
* **sandbox:** use https as default protocol for sandboxing ([38eb496](https://github.com/elliotsayes/ar-io-node/commit/38eb4969a30d229bb52df05a4f0578cce18864ba)), closes [#56](https://github.com/elliotsayes/ar-io-node/issues/56)


### Bug Fixes

* **observer:** bump observer to fix cache/referesh timing ([c3e6376](https://github.com/elliotsayes/ar-io-node/commit/c3e637645bd8e1343faf3f2ddc79a19fafd4c537))
* **observer:** bump version to fix healthcheck ([9312e59](https://github.com/elliotsayes/ar-io-node/commit/9312e59722df59eee08747e2a02b681724a1d9e5))
* **sqlite debug:** correct typo in debug key ([9a0777b](https://github.com/elliotsayes/ar-io-node/commit/9a0777bdbd81ebea1215e56c3e37d3a2bc510baf))
