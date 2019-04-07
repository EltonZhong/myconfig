# Config

Familar config

## Software

- Shadowsocks: [Download](https://lvii.gitbooks.io/outman/content/ss.mac.html)
- Postman
- 搜狗拼音
- Charles
- LyricsX + Spotify + 网易云音乐
- Chrome Mysql Admin
- 印象笔记

## Shell

.rc:

- Zsh: https://github.com/robbyrussell/oh-my-zsh
- Vimrc: https://github.com/amix/vimrc

.bash_profile:

```sh
alias android='emulator -avd Pixel_2_XL_API_28'
alias rest='pmset displaysleepnow'
alias home='pmset sleepnow'

function dir() {
    echo "`pwd`/$1"
}
```

Servers:

- [banwagon](https://bwh1.net/clientarea.php)
- [ali](https://account.aliyun.com/login/login.htm?oauth_callback=https%3A%2F%2Fswas.console.aliyun.com%2F%3F%26msctype%3Demail%26mscareaid%3Dcn%26mscsiteid%3Dcn%26mscmsgid%3D6700118122600476116%26#/server/4d297b81d3a844bc81285d85e9ee5751/cn-shenzhen/ops/connect)

## SDK

### Python

See pychard/settings.jar

- Virtual environment:

  ```sh
      alias venv="source ~/venv/bin/activate"
      alias v2"source ~/v2/bin/activate"
  ```

- Pipenv

### Java

Import idea/settings.jar

- Version:

  ```sh
  java version "1.8.0_152"
  Java(TM) SE Runtime Environment (build 1.8.0_152-b16)
  Java HotSpot(TM) 64-Bit Server VM (build 25.152-b16, mixed mode)
  ```

- Jshell:

  ```sh
  alias jshell="/Library/Java/JavaVirtualMachines/jdk-10.0.1.jdk/Contents/Home/bin/jshell"
  ```

- Maven:

  ```sh
  Apache Maven 3.5.2 (138edd61fd100ec658bfa2d307c43b76940a5d7d; 2017-10-18T15:58:13+08:00)
  Maven home: /usr/local/Cellar/maven/3.5.2/libexec
  Java version: 1.8.0_152, vendor: Oracle Corporation
  Java home: /Library/Java/JavaVirtualMachines/jdk1.8.0_152.jdk/Contents/Home/jre
  Default locale: en_CN, platform encoding: UTF-8
  OS name: "mac os x", version: "10.13.6", arch: "x86_64", family: "mac"
  ```

- Gradle

  ```sh
  ------------------------------------------------------------
  Gradle 4.7
  ------------------------------------------------------------

  Build time:   2018-04-18 09:09:12 UTC
  Revision:     b9a962bf70638332300e7f810689cb2febbd4a6c

  Groovy:       2.4.12
  Ant:          Apache Ant(TM) version 1.9.9 compiled on February 2 2017
  JVM:          1.8.0_152 (Oracle Corporation 25.152-b16)
  OS:           Mac OS X 10.13.6 x86_64
  ```

### Node

nvm

```sh
v11.9.0
$ nvm list
v11.9.0
    system
default -> v11.9.0
node -> stable (-> v11.9.0) (default)
stable -> 11.9 (-> v11.9.0) (default)
iojs -> N/A (default)
lts/* -> lts/dubnium (-> N/A)
lts/argon -> v4.9.1 (-> N/A)
lts/boron -> v6.16.0 (-> N/A)
lts/carbon -> v8.15.0 (-> N/A)
lts/dubnium -> v10.15.1 (-> N/A)
```

```sh
# For https://stackoverflow.com/questions/15636367/nodejs-require-a-global-module-package
export NODE_PATH='/usr/local/lib/node_modules'
```

### Kotlin

```sh
➜  ~ kotlin -version
Kotlin version 1.3.10-release-253 (JRE 1.8.0_152-b16)
```

## IDE

1. IDEA Plugins:

   - IdeaVim, IdeaVimExtension
     - .ideavim
     - .ideavimrc:  source ~/.vimrc
   - Alibaba guideline
   - Checkstyle, findBugs

2. VsCode Plugins:

   - Vs IntelliCode
   - Markdown lint
   - Eslint
   - vscode-groovy
   - Vim
   - Typescript Import

## Others:

1. PPT: reveal.js
2. 流程图：https://code2flow.com/dplcJG, processon
