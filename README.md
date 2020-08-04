# win10_env_setup

## Introduction

This is an article about how to build my own windows development environment.\
You can get some useful software and tips here.\
If you have something to recommend me to use, just post an issue.\
This repository will keep on refresh.

## Language

- [English](README.md)
- [简体中文](README-CN.md)

## System

I am using the en_windows_10_enterprise_ltsc_2019_x64 edition of windows 10.

It is doesn't matter what kind of system edition you are using, but I highly recommend you use this edition because it is super clean and doesn't contain much useless software and service. So, you can just install what you need and let the useless software gone.

You can download a system iso file from the [Microsoft][1], or you can download an iso file [here][2].

## git

### download

You can get git on their [official website][3] or download directly [here][4]

### config

Using bellow command to config your git quickly.

```bash
# user information
git config --global user.name "AimerNeige"
git config --global user.email aimer.neige.soft@gmail.com

# proxy
git config --global http.proxy http://127.0.0.1:1080
git config --global https.proxy https://127.0.0.1:1080
```

---

[1]: https://www.microsoft.com/en-us/evalcenter/evaluate-windows-10-enterprise "Download ISO from Microsoft"
[2]: https://www.reddit.com/r/Windows10LTSC/comments/hf58ut/windows_10_ltsc_iso_download/ "Download ISO from Reddit"
[3]: https://git-scm.com/ "Home page for git"
[4]: https://git-scm.com/download/win "Download git for windows"
