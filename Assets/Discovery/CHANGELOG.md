## [2.0.1](https://github.com/MirrorNG/Discovery/compare/v2.0.0...v2.0.1) (2021-02-15)


### Bug Fixes

* generate reader/writer for default discovery ([e484e26](https://github.com/MirrorNG/Discovery/commit/e484e2649c0b4a367fea1acf2616140035b9beff))

# [2.0.0](https://github.com/MirrorNG/Discovery/compare/v1.0.0...v2.0.0) (2021-02-15)


### Bug Fixes

* update changes that ng made. ([b52745b](https://github.com/MirrorNG/Discovery/commit/b52745b403d6cd71654806a8d52e7e97bb54d8be))
* update dependencies ([32f60e8](https://github.com/MirrorNG/Discovery/commit/32f60e8717e22c1700098ade891c8481851aa02f))


### BREAKING CHANGES

* upgrade to MirrorNG 65.x

# 1.0.0 (2020-12-31)


### Bug Fixes

* examples no longer use prefabs or common files ([#378](https://github.com/MirrorNG/Discovery/issues/378)) ([4f1a8a1](https://github.com/MirrorNG/Discovery/commit/4f1a8a10571ddaccf793af1cb084d0b153c22e6c))
* fix adding and saving Components ([0ad3cac](https://github.com/MirrorNG/Discovery/commit/0ad3cac359ec6f46216ef712be036d1162d3f7b1))
* NetMan cleanup and simplify ([#364](https://github.com/MirrorNG/Discovery/issues/364)) ([4a36b49](https://github.com/MirrorNG/Discovery/commit/4a36b49e5fcb1710366b24bf84b9f3a9b559397e))
* port network discovery ([a2cb606](https://github.com/MirrorNG/Discovery/commit/a2cb6060669b7e09caf7396ba3baa4da15f30721))
* script not found error with NetworkDiscoveryHud ([#494](https://github.com/MirrorNG/Discovery/issues/494)) ([acb6530](https://github.com/MirrorNG/Discovery/commit/acb6530c9d477a3de527cf5b79d543376eadfb0e))


* ClientObjectManager now requires NetworkIdentity (#475) ([088e607](https://github.com/MirrorNG/Discovery/commit/088e607755da8e99de7af146ed1b097a11202a00)), closes [#475](https://github.com/MirrorNG/Discovery/issues/475)
* Renamed ReadMessage -> Reader ([c1e8593](https://github.com/MirrorNG/Discovery/commit/c1e85937939e0a2b534b6067de604a5e8475ff37))


### Features

* New NetworkManagerHud ([#340](https://github.com/MirrorNG/Discovery/issues/340)) ([d0a880a](https://github.com/MirrorNG/Discovery/commit/d0a880ab24c55d1ed3dd2ef462a5fc6eafbf220f))
* Send any data type as message ([#359](https://github.com/MirrorNG/Discovery/issues/359)) ([51d4816](https://github.com/MirrorNG/Discovery/commit/51d4816780384413f38d6f33dc0d87f3889f5ac9))
* **installation:** Simplify packaging ([#336](https://github.com/MirrorNG/Discovery/issues/336)) ([4a586d4](https://github.com/MirrorNG/Discovery/commit/4a586d4107ae74629a7968ae3401654f16c41291))
* asynchronous transport ([#134](https://github.com/MirrorNG/Discovery/issues/134)) ([13a216a](https://github.com/MirrorNG/Discovery/commit/13a216a52618a648823579a8f59a3867494219fa))
* Disposable PooledNetworkReader / PooledNetworkWriter ([#1490](https://github.com/MirrorNG/Discovery/issues/1490)) ([06027b8](https://github.com/MirrorNG/Discovery/commit/06027b8bf9f2ac783acfb98bb191b933267aa44d))
* Implemented NetworkReaderPool ([#1464](https://github.com/MirrorNG/Discovery/issues/1464)) ([b0f1127](https://github.com/MirrorNG/Discovery/commit/b0f112754765b185a6632f7944219c44fa1fe3d2))
* LAN Network discovery ([#1453](https://github.com/MirrorNG/Discovery/issues/1453)) ([a096213](https://github.com/MirrorNG/Discovery/commit/a0962135071be321effc665be3d4af4e9fba7a79)), closes [#38](https://github.com/MirrorNG/Discovery/issues/38)
* Transports can have multiple uri ([#292](https://github.com/MirrorNG/Discovery/issues/292)) ([5ea1370](https://github.com/MirrorNG/Discovery/commit/5ea1370f85dfefd98ac50639fc4d1b8d276a679f))


### BREAKING CHANGES

* Now you can only assign prefabs with NetworkIdentity to the ClientObjectManager
* NetworkReader.ReadMessage renamed to NetworkReader.Read
* NetworkWriter.WriteMessage renamed to NetworkReader.Write
* IMessageBase has been removed,  you don't need to implement anything
* connecition Id is gone
* websocket transport does not work,  needs to be replaced.
