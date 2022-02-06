<div align="center">
  <h1 align="center">sCrypt 资源集锦</h1>
  <p align="center">
    <a href="https://github.com/sindresorhus/awesome">
      <img alt="awesome list badge" src="https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg">
    </a>
    <a href="http://makeapullrequest.com">
      <img alt="pull requests welcome badge" src="https://img.shields.io/badge/PRs-welcome-brightgreen.svg?style=flat">
    </a>
  </p>
  
  <p align="center">比特币智能合约高级语言 <a href="https://scrypt.io">sCrypt</a> 相关学习资源、开发库、项目、工具等内容精编汇总。</p>
  
</div>

### 内容

- [官方](#官方)
- [初学者教程](#初学者教程)
- [文章](#文章)
  - [官方博客](#官方博客)
  - [社区文章](#社区文章)
- [视频](#视频)
- [示例代码](#示例代码)
- [库合约](#库合约)
- [SDKs](#sdks)
- [集成开发环境](#集成开发环境)
- [实际应用](#实际应用)
- [钱包支持](#钱包支持)
- [交流社区](#交流社区)
- [License](#license)


## 官方

- [网站](https://scrypt.io) - 官方网址
- [sCrypt 语言文档](https://scryptdoc.readthedocs.io/zh_CN/latest/syntax.html) - 开发语言官方文档
- [IDE 文档](https://scrypt-ide.readthedocs.io/zh_CN/latest/index.html) - 桌面 IDE 官方文档
- [博客](https://blog.csdn.net/freedomhero) - 官方中文博客

## 初学者教程

- [Learn sCrypt](https://learn.scrypt.io/?lang=zh) - 交互式学习网站, 初学者首选
- [Learn sCrypt by Example](https://by-example.scrypt.io) - 用简单例子来介绍sCrypt
- [比特币智能合约入门（1）](https://blog.csdn.net/freedomhero/article/details/106801904) - UTXO 模型、比特币虚拟机及脚本简介
- [比特币智能合约入门（2）](https://blog.csdn.net/freedomhero/article/details/107104952) - sCrypt 高级语言简介
- [比特币智能合约入门（3）](https://blog.csdn.net/freedomhero/article/details/107127341) - sCrypt 开发工具 Visual Studio Code 插件介绍
- [比特币智能合约入门（4）](https://blog.csdn.net/freedomhero/article/details/107235041) - sCrypt 合约实战之 P2PKH 合约化
-  [比特币与以太坊智能合约比较](https://blog.csdn.net/freedomhero/article/details/117924646) - UTXO 模型优势
- [实现有状态的比特币智能合约](https://blog.csdn.net/freedomhero/article/details/107307306) - 有状态合约简介
-  [基于 sCrypt 合约开发一个完整的 dApp：井字棋游戏](https://blog.csdn.net/freedomhero/article/details/115419901) - 一个完整 DApp 的开发、测试、部署全流程演示


## 文章

### 官方博客

- [使用 sCrypt 智能合约在比特币上实现康威生命游戏](https://blog.csdn.net/freedomhero/article/details/111152834) - 一个简单的游戏合约
- [比特币上的数独游戏合约](https://blog.csdn.net/freedomhero/article/details/112758212) - 一个可实现链上外包求解数独的合约
- [比特币网络上公平的掷硬币游戏](https://blog.csdn.net/freedomhero/article/details/114257034) - 链上掷硬币游戏合约
- [比特币网络上的拍卖合约](https://blog.csdn.net/freedomhero/article/details/114638176) 
- [比特币上的机器学习-基于SVD的图像售卖合约](https://blog.csdn.net/freedomhero/article/details/115856795)
- [在比特币上构建机器学习竞赛市场](https://blog.csdn.net/freedomhero/article/details/119204702)
- [比特币智能合约 2.0（1）](https://blog.csdn.net/freedomhero/article/details/115862217) - 一种链上链下相结合的智能合约设计新思路
- [更多内容](https://blog.csdn.net/freedomhero)

### 社区文章

- [水龙头合约](https://blog.csdn.net/Edward_sv/article/details/109119838) - 基于智能合约的链上水龙头合约（by 老刘-Edward）
- [Oracle token方案](https://blog.csdn.net/Edward_sv/article/details/110977950) - 一种Oracle token方案的概述（by 老刘-Edward)
- [BSV智能合约（一）](https://blog.csdn.net/Edward_sv/article/details/106688515) - 看似不可能完成的任务（by 老刘-Edward)
- [BSV智能合约（二）](https://blog.csdn.net/Edward_sv/article/details/106688661) - 计数器合约代码分析（by 老刘-Edward)
- [感应合约的简介和基本原理](https://gulu-dev.com/post/2021/2021-05-01-sensible-intro) - 顾露 东澳岛BSV第一届训练营 (Bootcamp)
- [打开sCrypt的盒子（1）P2PKH合约](https://blog.csdn.net/weixin_47461167/article/details/108368848?spm=1001.2014.3001.5501) - sCrypt 入门合约解析（by Note.SV-李龍）
-  [打开sCrypt的盒子（2）Demo合约](https://blog.csdn.net/weixin_47461167/article/details/108390203?spm=1001.2014.3001.5501) - sCrypt 入门合约解析（by Note.SV-李龍）
-  [SPV Token 优化](https://powping.com/posts/28182efcc5b7ea2bf726e56599d58deb19b8b3933782e4174ce1af03e09cd359/comments/2e3545f5365472f33f01826c06a173dd394a326811deed3eacecc8e8917c273f#_2e3545f5365472f33f01826c06a173dd394a326811deed3eacecc8e8917c273f) - 一个针对 SPV Token 样例合约的优化实现（by microserver）
-  [在BSV链上建立带有互换(swap)功能的token合约](https://zhuanlan.zhihu.com/p/312024053) - by 王彼特
-  [通过oracle建立Bsv的链上二元期权合约](https://zhuanlan.zhihu.com/p/276215975) - by 王彼特
-  [BSV上的一种Fungible Token协议实现方案](https://zhuanlan.zhihu.com/p/349992213) - by 王彼特
-  [实现bsv上token的Pay to Contract](https://zhuanlan.zhihu.com/p/335212771) - by 王彼特
-  [bsv链上双人玩剪刀石头布](https://blog.csdn.net/jiedo/article/details/111187530) - by jiedo
-  [聊聊比特币BSV上的智能合约（一）](https://zhuanlan.zhihu.com/p/352208466) - by 区块链旺仔
-  [聊聊比特币BSV上的智能合约-预言机（Oracle)](https://zhuanlan.zhihu.com/p/356192260) - by 区块链旺仔
-  [浅谈比特币UTXO模型和以太坊账户模型的优劣](https://zhuanlan.zhihu.com/p/264882173) - by 区块链旺仔
-  [使用见证人服务构建第三方参与的比特币合约](https://blog.csdn.net/weixin_47461167/article/details/117662439) - (by Note.SV-李龍)
- [Pushdata 的“最小推送”规则](https://aaron67.cc/2022/02/06/pushdata-minimal-push-rule/) - by Aaron
- [Rabin 数字签名](https://aaron67.cc/2021/07/10/rabin-signatures/) - by Aaron
- [我被盗了 600 BSV](https://aaron67.cc/2020/11/08/lost-600-bsv/) - by Aaron
- [OP_RETURN](https://aaron67.cc/2018/12/31/bitcoin-transaction-null-data/) - by Aaron
- [比特币交易的脚本](https://aaron67.cc/2018/12/26/bitcoin-transaction-script/) - by Aaron
- [比特币脚本里的整数](https://aaron67.cc/2022/02/07/numbers-in-bsv-script/) - by Aaron
- [部分文章索引](https://wiki.bsv.info/scrypt)

## 视频

- [开发者交流会议](https://space.bilibili.com/1294122227/channel/seriesdetail?sid=538938) - 每周官方meetup
- [中国 Devcon 2020 演讲](https://www.bilibili.com/video/BV1yT4y1L7gx) - 使用 sCrypt 在比特币上开发智能合约
- [Bitcoin SV智能合约开发教程（一）](https://live.csdn.net/v/145948?ops_request_misc=%257B%2522request%255Fid%2522%253A%2522162877393716780255210029%2522%252C%2522scm%2522%253A%252220140713.130102334.pc%255Fvideo.%2522%257D&request_id=162877393716780255210029&biz_id=&utm_medium=distribute.pc_search_result.none-task-short_video-2~video~first_rank_v2~rank_v29-8-145948.nonecase&utm_term=bitcoin+sv) - 区块链智能合约入门
- [Bitcoin SV智能合约开发教程（二）](https://live.csdn.net/v/146834?ops_request_misc=%257B%2522request%255Fid%2522%253A%2522162877393716780255210029%2522%252C%2522scm%2522%253A%252220140713.130102334.pc%255Fvideo.%2522%257D&request_id=162877393716780255210029&biz_id=&utm_medium=distribute.pc_search_result.none-task-short_video-2~video~first_rank_v2~rank_v29-11-146834.nonecase&utm_term=bitcoin+sv) - 比特币智能合约和 sCrypt 简介
- [Bitcoin SV智能合约开发教程（三）](https://live.csdn.net/v/148403?ops_request_misc=%257B%2522request%255Fid%2522%253A%2522162877393716780255210029%2522%252C%2522scm%2522%253A%252220140713.130102334.pc%255Fvideo.%2522%257D&request_id=162877393716780255210029&biz_id=&utm_medium=distribute.pc_search_result.none-task-short_video-2~video~first_rank_v2~rank_v29-10-148403.nonecase&utm_term=bitcoin+sv) - sCrypt 智能合约开发工具简介
- [Bitcoin SV智能合约开发教程（四）](https://live.csdn.net/v/156027?ops_request_misc=%257B%2522request%255Fid%2522%253A%2522162877393716780255210029%2522%252C%2522scm%2522%253A%252220140713.130102334.pc%255Fvideo.%2522%257D&request_id=162877393716780255210029&biz_id=&utm_medium=distribute.pc_search_result.none-task-short_video-2~video~first_rank_v2~rank_v29-13-156027.nonecase&utm_term=bitcoin+sv) - `OP_PUSH_TX` 技术及有状态 sCrypt 智能合约介绍
- [Bitcoin SV智能合约开发实践](https://www.bilibili.com/video/BV1EZ4y1F7r7?p=8) - sCrypt 语言新特性及合约范例解析
- [DotCamp打点创新营](https://www.bilibili.com/video/BV1kr4y1c76Y?share_source=copy_web) - 使用sCrypt开发比特币智能合约

- [感应合约简介和基本原理](https://www.bilibili.com/video/BV1EZ4y1F7r7?p=10) - 顾露 Bootcamp 2021
- [感应合约应用:三方交易等应用方向及案例](https://www.bilibili.com/video/BV1EZ4y1F7r7?p=12) - 蒋杰 Bootcamp 2021
- [sCrypt的工程化实践经验](https://www.bilibili.com/video/BV1EZ4y1F7r7?p=9) - 蒋杰 Bootcamp 2021
- [Sensible Fungible Token 方案](https://www.bilibili.com/video/BV1EZ4y1F7r7?p=11) - 陈诚 Bootcamp 2021
- [感应合约开发工具与开发资源介绍](https://www.bilibili.com/video/BV1H34y197kX) - 陈耀欢 DEVCON 2021

## 示例代码

- [sCrypt Project Boilerplate](https://github.com/sCrypt-Inc/boilerplate) - 官方及社区共同维护的 sCrypt 合约实例及测试代码，数量已超过 80 个并持续增长中；
- [Gist](https://gist.github.com/ccoincash) - 示例合约和部署代码，包含token sale, 交易解析, merkle tree, token swap, and 二元期权 by 陈诚
- [Sensible Fungible Token](https://github.com/sensible-contract/token_sensible)
- [Sensible NFT](https://github.com/sensible-contract/nft)
- [Sensible NFT拍卖](https://github.com/sensible-contract/nft-auction-js)
- [价格对赌](https://gist.github.com/gitzhou/7f4f8709590995ac8b7c008d7860bada) - 价格信息来自Oracle WitnessOnChain

## 库合约

- [深入学习比特币脚本之 OP_PUSH_TX（1）](https://blog.csdn.net/freedomhero/article/details/107306604) - OP_PUSH_TX 技术介绍
- [深入学习比特币脚本之 OP_PUSH_TX（2）](https://blog.csdn.net/freedomhero/article/details/107333738) - OP_PUSH_TX 技术介绍
- [预言机与 Rabin 签名在比特币智能合约中的应用原理](https://blog.csdn.net/freedomhero/article/details/107237537)  - Rabin 签名及应用
- [如何在 sCrypt 合约中实现浮点数运算](https://blog.csdn.net/freedomhero/article/details/118709814) - 合约内的高精度计算
- [使用 Merklized 抽象语法树压缩智能合约](https://blog.csdn.net/freedomhero/article/details/119301247) - 合约优化


## SDKs

- [scryptlib](https://github.com/sCrypt-Inc/scryptlib) - Javascript / Typescript.
- [py-scryptlib](https://github.com/sCrypt-Inc/py-scryptlib) - Python.
- [go-scryptlib](https://github.com/sCrypt-Inc/go-scryptlib) - Go.


## 集成开发环境

- [桌面版](https://marketplace.visualstudio.com/items?itemName=bsv-scrypt.sCrypt) - Visual Studio Code 插件 IDE
- [云版](https://scrypt.studio) - 在线开发环境


## 实际应用
- [感应合约](https://sensiblecontract.org/) - 一个基于 sCrypt 的智能合约溯源及协作协议
- [TokenSwap](https://tswap.io) - 基于BSV网络的去中心化交易所
- [小聪游戏](https://satoplay.com/pc.html) - 基于BSV网络的游戏平台，平台通证和 NFT 使用了感应合约
- [ShowApp](https://show.sv/) - 基于MetaID的社交软件和钱包，平台通证和NFT将使用感应合约
- [CUTP](https://github.com/CUTP) - Controllable UTXO Token协议

## 钱包支持

- [打点钱包](https://www.dotwallet.com/en/article/269)
- [Volt钱包](https://volt.id/#/)


## 交流社区

- [微信](https://scrypt.io/static/img/wechat-qrcode.jpg) - 官方微信群
- [Slack](https://join.slack.com/t/scryptworkspace/shared_invite/enQtNzQ1OTMyNDk1ODU3LTJmYjE5MGNmNDZhYmYxZWM4ZGY2MTczM2NiNTIxYmFhNTVjNjE5MGYwY2UwNDYxMTQyNGU2NmFkNTY5MmI1MWM) - 官方技术交流社区
- [Github](https://github.com/sCrypt-Inc) - 开源合约、SDK、实例 dApp 代码
- [Telegram](https://t.me/joinchat/GwaRAxKT16JjXyHt5PuhHw) - 电报群


---

## License

[![CC0](https://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](https://creativecommons.org/publicdomain/zero/1.0/)

在法律允许的范围内，sCrypt Inc 放弃了本作品的所有版权和相关或邻接权。