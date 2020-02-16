# Google Play Services Resolver Package

[![openupm](https://img.shields.io/npm/v/io.elhan.play-services-resolver?label=openupm&registry_uri=https://package.openupm.com)](https://openupm.com/packages/io.elhan.play-services-resolver/)

This repository makes it possible to use [play-services-resolver](https://github.com/googlesamples/unity-jar-resolver) with Unity Package Manager (UPM)

![play-services-resolver](https://i.imgur.com/vE6XQhQ.png)

## Installation

### Install via OpenUPM

The package is available on the [openupm registry](https://openupm.com). It's recommended to install it via [openupm-cli](https://github.com/openupm/openupm-cli).

```
openupm add io.elhan.play-services-resolver
```

### Install via Git URL

- Add following dependency to `Packages/manifest.json` in your project;

  ```json
  {
    "dependencies": {
      "io.elhan.play-services-resolver": "https://github.com/oae/unity-package-play-services-resolver.git#0.1.0",
    }
  }
  ```

> For the official plugin, check out the [original repository](https://github.com/googlesamples/unity-jar-resolver)
