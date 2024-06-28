<p align="center">
    <a href="https://screego.net">
        <img src="docs/logo.png" />
    </a>
</p>


<h1 align="center">screego/server</h1>
<p align="center"><i>screen sharing for developers</i></p>

<p align="center">
    <a href="https://github.com/screego/server/actions?query=workflow%3Abuild">
        <img alt="Build Status" src="https://github.com/screego/server/workflows/build/badge.svg">
    </a> 
    <a href="https://github.com/screego/server/pkgs/container/server">
        <img alt="Build Status" src="https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Fraw.githubusercontent.com%2Fipitio%2Fghcr-pulls%2Fmaster%2Findex.json&query=%24%5B%3F(%40.owner%3D%3D%22screego%22%20%26%26%20%40.repo%3D%3D%22server%22%20%26%26%20%40.image%3D%3D%22server%22)%5D.pulls&logo=github&label=pulls">
    </a> 
    <a href="https://goreportcard.com/report/github.com/screego/server">
        <img alt="Go Report Card" src="https://goreportcard.com/badge/github.com/screego/server">
    </a>
    <a href="https://hub.docker.com/r/screego/server">
        <img alt="Docker Pulls" src="https://img.shields.io/docker/pulls/screego/server.svg">
    </a>
    <a href="https://github.com/screego/server/releases/latest">
        <img alt="latest release" src="https://img.shields.io/github/release/screego/server.svg">
    </a>
</p>

## Intro

过去，在使用 Microsoft Teams 等企业聊天解决方案与同事共享屏幕时，我遇到了一些问题。我想向他们展示我的一些代码，但要么是视频流延迟了几秒钟，要么是质量太差，我的同事无法阅读代码。或者两者兼而有之。
这就是我创建 screego 的原因。它允许您以高质量和低延迟共享您的屏幕。Screego 是对现有软件的补充，仅帮助您共享屏幕。没有其他功能

## Features

* Multi User Screenshare
* Secure transfer via WebRTC
* Low latency / High resolution
* Simple Install via Docker / single binary
* Integrated TURN Server see [NAT Traversal](https://screego.net/#/nat-traversal)

[Demo / Public Instance](https://app.screego.net/) ᛫ [Installation](https://screego.net/#/install) ᛫ [Configuration](https://screego.net/#/config) 

## Versioning

We use [SemVer](http://semver.org/) for versioning. For the versions available, see the
[tags on this repository](https://github.com/screego/server/tags).
