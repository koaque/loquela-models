# Loquela model mirror

Speech recognition model packages that the [Loquela](https://getloquela.com) keyboard downloads when someone chooses
them in the app. Nothing here is Loquela's own code. Each package is an upstream model, unchanged, repacked as
`.tar.bz2` with its licence files so the app can verify its SHA-256 and unpack it. The app only downloads a package
when a user asks for it, and recognition then runs on the phone.

Files are attached to the [`models-1` release](../../releases/tag/models-1).

## Vosk small models

Source: [Alpha Cephei Vosk models](https://alphacephei.com/vosk/models), Apache License 2.0. Each archive holds the
upstream folder as published, plus `LICENSE` and a `NOTICE` naming the upstream file and its digest.

| Language | File | Size | SHA-256 | Upstream file |
|---|---|---|---|---|
| English (US) | `vosk-model-small-en-us-0.15.tar.bz2` | 40 MB | `f09619cadbc7860a6da0b3a55c95640bb2f7cbe9e362f415b3c3c52c4d2050b3` | [vosk-model-small-en-us-0.15.zip](https://alphacephei.com/vosk/models/vosk-model-small-en-us-0.15.zip) |
| Hindi | `vosk-model-small-hi-0.22.tar.bz2` | 43 MB | `aed534f102a527d8ff4e7f26e8b015a63ce87bfd9381c71cae1ad9de56377de3` | [vosk-model-small-hi-0.22.zip](https://alphacephei.com/vosk/models/vosk-model-small-hi-0.22.zip) |
| Vietnamese | `vosk-model-small-vn-0.4.tar.bz2` | 32 MB | `310aae164dff19b2f837468ef7125dca7b0c798572fde7b3416e515fc3441034` | [vosk-model-small-vn-0.4.zip](https://alphacephei.com/vosk/models/vosk-model-small-vn-0.4.zip) |
| Turkish | `vosk-model-small-tr-0.3.tar.bz2` | 36 MB | `99de4d06e40401b7be50b15bf45051e2cefcc51340e956479d040f023a9544aa` | [vosk-model-small-tr-0.3.zip](https://alphacephei.com/vosk/models/vosk-model-small-tr-0.3.zip) |
| Italian | `vosk-model-small-it-0.22.tar.bz2` | 48 MB | `11343a4988b9f21cd67ee163988fe483d799fb1109b898de7e5a1f75539de25e` | [vosk-model-small-it-0.22.zip](https://alphacephei.com/vosk/models/vosk-model-small-it-0.22.zip) |
| Spanish | `vosk-model-small-es-0.42.tar.bz2` | 39 MB | `70761478294aa537e52926996e0215bc17e9691dc4220d1d33eb55fa403334b0` | [vosk-model-small-es-0.42.zip](https://alphacephei.com/vosk/models/vosk-model-small-es-0.42.zip) |
| French | `vosk-model-small-fr-0.22.tar.bz2` | 41 MB | `36201cbee2c46ea79d30df511e6753b5278405b8e402972d7b439c774fb9d982` | [vosk-model-small-fr-0.22.zip](https://alphacephei.com/vosk/models/vosk-model-small-fr-0.22.zip) |
| German | `vosk-model-small-de-0.15.tar.bz2` | 44 MB | `f303c746c3c938a694a9ecb353c8c49ad762113e18495ff37be6daf479bb841a` | [vosk-model-small-de-0.15.zip](https://alphacephei.com/vosk/models/vosk-model-small-de-0.15.zip) |
| Portuguese | `vosk-model-small-pt-0.3.tar.bz2` | 32 MB | `903319c9718c646957dbd5cc263607a08ccfd85e9f00f546dd119111eca23261` | [vosk-model-small-pt-0.3.zip](https://alphacephei.com/vosk/models/vosk-model-small-pt-0.3.zip) |
| Japanese | `vosk-model-small-ja-0.22.tar.bz2` | 48 MB | `f9a6d317adb5b38f9056fc93cd1ad782486c34c2f5153c6dc85d4152f3b4ec58` | [vosk-model-small-ja-0.22.zip](https://alphacephei.com/vosk/models/vosk-model-small-ja-0.22.zip) |
| Korean | `vosk-model-small-ko-0.22.tar.bz2` | 79 MB | `f258fce07a2eae997af16a61c6df65a032d5d2aa621ebf15418608d46091bf7f` | [vosk-model-small-ko-0.22.zip](https://alphacephei.com/vosk/models/vosk-model-small-ko-0.22.zip) |

## Licences

Every package keeps the licence of its upstream model, included inside the archive. This repository adds nothing
to those terms.

Questions: info@getloquela.com
