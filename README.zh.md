<!--idoc:ignore:start-->
> [!TIP]
> 声明：此项目并非开源项目，仓库作为官方网站，用于收集问题和用户需求。这样做是为了节省成本，因为没有官网，应用无法通过审核。
<!--idoc:ignore:end-->

<div align="center">
  <br />
  <br />
  <img src="./assets/logo.png" width="160" height="160">
  <h1>
    Keyzer 密码管理器
  </h1>
  <!--rehype:style=border: 0;-->
  <p>
    <a href="./README.md">English</a> • 
    <a target="_blank" href="https://github.com/jaywcjlove/keyzer/issues/new?template=bug_report_cn.yml">联系&支持</a> • 
    <a href="./CHANGELOG.zh.md">更新日志</a>
  </p>
  <p>
    <a target="_blank" href="https://apps.apple.com/app/Keyzer/6500434773" title="Keyzer for macOS">
      <img alt="Keyzer AppStore" src="https://jaywcjlove.github.io/sb/download/macos.svg" height="51">
    </a>
  </p>
</div>

![](./assets/screenshots-1.jpg)

![](./assets/screenshots-2.jpg)

![](./assets/screenshots-3.jpg)

![](./assets/screenshots-4.jpg)

Keyzer 是一款专为 macOS 设计的原生密码管理器，帮助你安全存储所有密码和私密信息。
在日常生活中，你总有一些不想让他人知道的敏感数据，比如信用卡信息、银行账户和各类密码。
Keyzer 将这些数据加密保存为便携的 Keyzer 文件，确保你的信息始终存储在本地设备上，完全离线使用，让你在保护隐私的同时，轻松访问和管理。

## 隐私与安全

这是一个非常合理的担忧，我完全理解为什么在处理敏感信息的应用中，"信任"如此重要。

我的设计目标是尽量**减少用户需要对开发者本人的信任依赖**：

- 所有数据都**只存储在本地设备**，不会上传到任何服务器
- **没有账号系统、没有统计分析、也没有后台联网行为**
- 应用可以完全离线使用，数据始终由用户自己掌控

另外，这个应用是通过 **Mac App Store** 发布的，意味着它需要通过苹果的审核流程，并运行在苹果的沙盒和安全机制之下。这在一定程度上确保了应用只能做它声明过的事情，无法越权访问系统或用户的其他数据。

当然，我也理解每个人对安全和信任的标准不同，如果这个应用不符合你的期望，那也是完全可以理解的。

<!--idoc:config:
title: Keyzer
keywords: Keyzer,密码管理器,密码,安全,加密,隐私,安全存储,密码保险库,本地存储,离线,数据保护,简单,易用
description: 一款原生应用，用于安全存储你的所有密码及其他私密信息
-->