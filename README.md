# DDBOT

一个基于MiraiGO的多功能QQ群机器人。

-----

## **基本功能：**

- **B站直播/动态推送**
    - 让阁下在DD的时候不错过任何一场突击。
- **斗鱼直播推送**
    - 没什么用，主要用来看爽哥。
- **油管直播/视频推送** *New*
    - 支持推送预约直播信息及视频更新
- **人脸识别**
    - 主要用来玩，支持二次元人脸
- **倒放**
    - 主要用来玩
- **Roll**
    - 没什么用的roll点
- **签到**
    - 没什么用的签到
- **权限管理**
    - 可配置整个命令的启用和禁用，也可对单个用户配置命令权限，防止滥用。
- **帮助**
    - 输出一些没什么帮助的信息

<details>
  <summary>里命令</summary>

以下命令默认禁用，使用enable命令后才能使用

- **随机图片**
    - 由 [api.olicon.app](https://api.lolicon.app/#/) 提供
- **色图判定**
    - 由阿里云提供
    - **注意：阿里云该服务2021年3月25日开始收费**

</details>

### 推送效果

<img src="https://user-images.githubusercontent.com/11474360/111737379-78fbe200-88ba-11eb-9e7e-ecc9f2440dd8.jpg" width="300">

### 用法示例

详细介绍及示例请查看：[详细示例](/EXAMPLE.md)

阁下可添加Demo机器人体验，QQ：1561991863

<img src="https://user-images.githubusercontent.com/11474360/108590360-150afa00-739e-11eb-86f7-77f68d845505.jpeg" width="300" height="450">

## 使用与部署

对于普通用户，推荐您选择使用开放的Demo机器人。

如果您需要私人部署，[详见部署指南](/INSTALL.md)

## **最近更新**

- 更换船新b站监控方案，预计单帐号可支持1000订阅，最大延迟30秒。

## 已知问题

- 一些情况下无法正常识别QQ群管理员，属于MiraiGo问题，无法在本项目解决。

## 注意事项

- **bot只在群聊内工作，私聊命令无效**
- **建议bot秘密码设置足够强，同时不建议把bot设置为QQ群管理员，因为存在密码被恶意爆破的可能（包括但不限于盗号、广告等）**
- **您应当知道，bot账号可以人工登陆，请注意个人隐私**
- bot掉线无法重连时将自动退出，请自行实现保活机制
- bot使用 [buntdb](https://github.com/tidwall/buntdb) 作为embed database，会在当前目录生成文件`.lsp.db`
  ，删除该文件将导致bot恢复出厂设置，可以使用 [buntdb-cli](https://github.com/Sora233/buntdb-cli) 作为运维工具，但注意不要在bot运行的时候使用（buntdb不支持多写）

## 敬告

- 请勿滥用
- 禁止商用

## 贡献

*Feel free to make your first pull request.*

想要为开源做一点微小的贡献？

[Golang点我入门！](https://github.com/justjavac/free-programming-books-zh_CN#go)

您也可以选择点一下右上角的⭐星⭐

发现问题或功能建议请到 [issues](https://github.com/Sora233/DDBOT/issues)

其他用法问题请到 [discussions](https://github.com/Sora233/DDBOT/discussions)

## 鸣谢

> [Goland](https://www.jetbrains.com/go/) 是一个非常适合Gopher的智能IDE，它极大地提高了开发人员的效率。

特别感谢 [JetBrains](https://jb.gg/OpenSource) 为本项目提供免费的 [Goland](https://www.jetbrains.com/go/) 等一系列IDE的授权

[<img src="https://user-images.githubusercontent.com/11474360/112592917-baa00600-8e41-11eb-9da4-ecb53bb3c2fa.png" width="200"/>](https://jb.gg/OpenSource)