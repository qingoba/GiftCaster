# 🎁GiftCaster

## 项目概述

七夕将至，设想你要在区块链上给你的对象转账 520 USDC，你不觉得简单的 transfer 太无聊，太平平无奇了吗？

如果有一个链上的礼物平台可以把你的礼物包装起来，无论是代币还是 NFT （比如一束花、一个钻戒、RWA、任何东西） 都可以被包装进礼物中，用精美的图标、边框、特效展示出来，并且网络上所有人都可以看到你的礼物，是不是瞬间变得有趣和充满仪式感了！对象看到肯定喜欢！

🎁GiftCaster 就是为了服务这个需求！它将是 Farcaster Mini App 生态中首个去中心化礼物平台。它将社交关系、数字资产和“仪式感”经济有机结合，让 "transfer" 不再只是枯燥无聊的转账，而是充满仪式感的有趣体验，是身份的表达、社交的放大、品牌的传播。

## 项目所选赛道

Innovative Dapps

## 核心功能

### 礼物派发

- 可指定单一/多个接收者，需签名领取，适合情侣、好友、私密赠送。
  - 支持 ENS！
- 也可面向所有人公开抢红包，增强社群互动与传播。
- 礼物可包装多种资产，包括 ERC-20,ERC-721,ERC-1155 等任意 token

### 礼物榜单

- 网络中所有礼物实时展示，并按礼物价值从高到低排序。
- 高额礼物会长时间“霸榜”，给予赠送者和接收者极强的仪式感与曝光度。
- 所以历史礼物也会有一个榜单，永久保存送礼记录，用户可以送出巨额礼物来在榜单上留下浓墨重彩的一笔

### 社交传播

- 应用依托 Farcaster 社交网络平台，天然具有社交分享与扩散效应。
- 项目方、广告方可通过向所有人发放礼物进行宣传扩散，实现高效的用户增长与品牌曝光。

### 用户需求

🎁GiftCaster 服务了以下几种真实的用户需求：

1. 炫耀心理：大额礼物“霸榜”，彰显身份与影响力。
2. 仪式感：情侣、好友间赠礼，创造独特社交记忆。
3. 项目方宣传扩张：项目方向所有用户发放礼物，实现推广与拉新。

### 为什么做 Farcaster Mini App

- Farcaster Mini App 生态尚处于蓝海阶段，市场空白，先发优势显著
- 去中心化社交 + 礼物的强曝光特性，完美契合 Farcaster 的开放与去中心化属性
- 同时满足 C 端的仪式感 与 B 端的营销推广，双边市场驱动成长
- 我们认为 🎁GiftCaster 有望能够成为 Farcaster 上的明星应用 qwq！（现在是，幻想时间）

### 增值服务（未来规划）

- 礼物外观个性化：边框、特效、礼盒皮肤，提升社交表达。
- 用户等级成长：送过的礼物总价值越高，用户等级越高，作为身份的证明！
- 成就系统：第一送出礼物、第一次领取礼物、第一次购买装饰、第一次将 ERC-721 / ERC-1155 token 打包进礼物盒等等丰富有趣的成就系统，让应用更有趣，激发用户更多使用兴趣
- 空投期望：利用空投期望吸引早期用户参与，快速积累用户。空投代币将可以用户限量版装饰购买
- 总之就是很有商业潜力啊！（现在又是，幻想时间）

## 代码仓库地址

https://github.com/qingoba/GiftCaster

## 团队成员

| name | github url |
| -- | -- |
| 徐元桢 | https://github.com/aliceyzhsu |
| 唐彬杰 | https://github.com/binjietang |
| 刘宇庆 | https://github.com/qingoba |
| 陈润楠 | https://github.com/ChenRunnan-Cooper |
| 兰杨 | https://github.com/Sia2010 |
| 陶子璇 | https://github.com/Abigailhust |

## 历史获奖说明

本项目代码均为短期内开发，第一次参加 hackathon

## 项目演示

https://drive.google.com/drive/folders/1VNooz4YFL-qS8WGYKbd6FpOhhzsv5MLF?usp=sharing

## Getting Started
合约代码位于 `src/contract-code`, 其余为 Dapp 代码

启动 DApp 的命令:

```
npm install
npm run dev
```
如果要在 Farcaster Embed 或手机 App 上显示: 在根目录 index.html 找到如下属性信息, 将 url 字段修改为部署地址(不能是 localhost)
```
<meta name="fc:frame" content='{"version":"next","imageUrl":"https://placehold.co/900x600.png?text=Gift%20Box","button":{"title":"Open Gift Box","action":{"type":"launch_frame","name":"Gift Box","url":"https://respondents-messaging-specials-in.trycloudflare.com","splashImageUrl":"https://placehold.co/900x600.png?text=Gift%20Box","splashBackgroundColor":"#f8f9fa"}}}' />
```