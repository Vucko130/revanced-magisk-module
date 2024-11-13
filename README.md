# ReVanced Magisk Module
[![Telegram](https://img.shields.io/badge/Telegram-2CA5E0?style=for-the-badge&logo=telegram&logoColor=white)](https://t.me/bot_tribe_rvc)
[![CI](https://github.com/Vucko130/revanced-magisk-module/actions/workflows/ci.yml/badge.svg)](https://github.com/Vucko130/revanced-magisk-module/actions/workflows/ci.yml)
![GitHub Release](https://img.shields.io/github/v/release/Vucko130/revanced-magisk-module?include_prereleases&sort=semver&display_name=tag&logo=android&label=Latest%20Release)
[![API](https://img.shields.io/badge/API-34%2B-brightgreen.svg?style=flat)](https://android-arsenal.com/api?level=34)
![GitHub License](https://img.shields.io/github/license/Vucko130/revanced-magisk-module?style=flat&logo=github&label=License)
[![Github Downloads](https://img.shields.io/github/downloads/Vucko130/revanced-magisk-module/total.svg?label=GitHub%20Downloads&logo=github)](https://github.com/Vucko130/revanced-magisk-module/edit/main/README.md#download)

<div id="Github Badge" align="center">
<a href="https://github.com/Vucko130/revanced-magisk-module/releases/"> 
<img alt="GitHub Badge" src="https://raw.githubusercontent.com/Viperz75/Jar/master/promotional/github-badge.png" height="60px">
</a></div>

<br />

Extensive ReVanced builder  

Get the [latest CI release](https://github.com/Vucko130/revanced-magisk-module/releases).

Use [**zygisk-detach**](https://github.com/j-hc/zygisk-detach) to detach YouTube and YT Music from the Play Store if you are using magisk modules. 

<details><summary><big>Features</big></summary>
<ul>
 <li>Support all present and future ReVanced and <a href="https://github.com/inotia00/revanced-patches">ReVanced Extended</a> apps</li>
 <li> Can build Magisk modules and non-root APKs</li>
 <li> Updated daily with the latest versions of apps and patches</li>
 <li> Optimize APKs and modules for size</li>
 <li> Modules</li>
    <ul>
     <li> recompile invalidated odex for faster usage</li>
     <li> receive updates from Magisk app</li>
     <li> Do not break safetynet or trigger root detections</li>
     <li> handle the installation of the correct version of the stock app and all that</li>
     <li> support Magisk and KernelSU</li>
    </ul>
</ul>
Note that the <a href="../../actions/workflows/ci.yml">CI workflow</a> is scheduled to build the modules and APKs every day using GitHub Actions if there is a change in ReVanced patches. You may want to disable it.
</details>

## To include/exclude patches or patch other apps

 * Star the repo :eyes:
 * Use the repo as a [template](https://github.com/new?template_name=revanced-magisk-module&template_owner=Vucko130)
 * Customize [`config.toml`](./config.toml) using [rvmm-config-gen](https://j-hc.github.io/rvmm-config-gen/)
 * Run the build [workflow](../../actions/workflows/build.yml)
 * Grab your modules and APKs from [releases](../../releases)

also, see here [`CONFIG.md`](./CONFIG.md)

## Building Locally
### On Termux
```console
bash <(curl -sSf https://raw.githubusercontent.com/Vucko130/revanced-magisk-module/main/build-termux.sh)
```

### On Desktop
```console
$ git clone https://github.com/Vucko130/revanced-magisk-module
$ cd revanced-magisk-module
$ ./build.sh
```
