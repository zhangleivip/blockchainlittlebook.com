# 区块链小白书(改编)

张磊（改编）&copy; 2019

-----

## 警告

> 区块链作为金融互联网新技术，不可避免地会涉及到投资和投机 —— 而对绝大多数普通人来说：
>
> > **投资有风险，决策需谨慎！**

## 前言

[新华社北京10月25日电](http://www.xinhuanet.com/politics/2019-10/25/c_1125153665.htm)，中共中央政治局10月24日下午就区块链技术发展现状和趋势进行第十八次集体学习。

> 中共中央总书记习近平在主持学习时强调，区块链技术的集成应用在新的技术革新和产业变革中起着重要作用。我们要把区块链作为核心技术自主创新的重要突破口，明确主攻方向，加大投入力度，着力攻克一批关键核心技术，加快推动区块链技术和产业创新发展。
>
> 习近平在主持学习时发表了讲话。他指出，区块链技术应用已延伸到数字金融、物联网、智能制造、供应链管理、数字资产交易等多个领域。目前，全球主要国家都在加快布局区块链技术发展。我国在区块链领域拥有良好基础，要加快推动区块链技术和产业创新发展，积极推进区块链和经济社会融合发展。
>
> 习近平强调，要强化基础研究，提升原始创新能力，努力让我国在区块链这个新兴领域走在理论最前沿、占据创新制高点、取得产业新优势。要推动协同攻关，加快推进核心技术突破，为区块链应用发展提供安全可控的技术支撑。要加强区块链标准化研究，提升国际话语权和规则制定权。要加快产业发展，发挥好市场优势，进一步打通创新链、应用链、价值链。要构建区块链产业生态，加快区块链和人工智能、大数据、物联网等前沿信息技术的深度融合，推动集成创新和融合应用。要加强人才队伍建设，建立完善人才培养体系，打造多种形式的高层次人才培养平台，培育一批领军人物和高水平创新团队。
>
> ……

到了 2019 年，。这些年来，人们对区块链的误解甚至诋毁现在终于可以烟消云散了 —— 因为区块链技术终于在中国获得了认可与支持。

然而，需要注意的是，区块链技术作为金融互联网新技术，不可避免地与投机（或投资）联系在一起，导致的结果是市场上骗局丛生，行业里鱼龙混杂，所以有必要让民众对区块链有正确且清楚的了解。这就是《区块链小白书》的意义 —— 它就是写给小白的，目的不仅是为了让小白少走弯路，更是为了让小白不要误入歧途。

⚠️以上前言部分来自李笑来《[区块链小白书](https://blockchainlittlebook.com/#/)》

## 小白如何使用Mixin获得比特币

### Mixin下载
目前世界上对小白最友好的多币种钱包是 [Mixin Messenger](https://mixin.one/messenger)，它不仅支持你所能听说过的绝大多数数字资产收发与存储，并且使用极为方便。

Mixin 下载方式：

> * iOS
>   * 国内用户，在 iTunes [下载 Mixin 畅聊版](https://apps.apple.com/cn/app/mixin-%E5%AF%86%E4%BF%A1%E7%95%85%E8%81%8A%E7%89%88/id1457938019)
>   * 国外用户，在 iTunes [下载 Mixin Messenger](https://apps.apple.com/app/mixin/id1322324266)
> * Android
>   * 国内用户，在[腾讯应用宝下载](https://a.app.qq.com/o/simple.jsp?pkgname=one.mixin.messenger)，或者[小米应用商店下载](http://app.mi.com/details?id=one.mixin.messenger)
>   * 国外用户，在 [Google Play Store 下载](https://play.google.com/store/apps/details?id=one.mixin.messenger)

iiOS 国内用户下载的 [Mixin 畅聊版](https://apps.apple.com/cn/app/mixin-%E5%AF%86%E4%BF%A1%E7%95%85%E8%81%8A%E7%89%88/id1457938019) 需要添加小钱包机器人（ID: *7000101425*）才能使用数字资产收发存储功能。

![](images/miniwallet.png)

在 Mixin 里提供 OTC 服务的是 exin，机器人 ID：7000101276。

你也可以到 [https://big.one](https://big.one) 或者 [https://b1.run](https://b1.run)，这是国内老牌交易所云币团队打造的有信誉保障的区块链数字资产交易所，可以使用 USDT 购买比特币，它也有 [OTC 服务](https://otc.b1.run/trade)。另外，Big.One 的 Mixin 大群 ID 是：*7000101910*。

再次需要提醒风险：

> 区块链数字资产价格波动巨大，**投资有风险，决策需谨慎！**

另外，对小白来说最靠谱的投资策略是**定投策略** —— 至于具体应该如何操作，请移步[《定投改变命运》（开源第三版）](https://onregularinvesting.com)。

### Mixin使用
> *Mixin中文群：7000101317 入群费：0.07xin
> Mixin用户群
> *Exin 中文群：7000000016 免费
> Exin用户群
> *FoxOne中文群：7000100217 免费
>  Fox.One App的用户群
> *定投公开课群：7000102093 免费（可领红包）
每天有大量红包可以领取，每天大概总值千元人民币左右，但由于一个红包基本分成10000份（10000人抢），所以，只能用苍蝇腿上的肉形容。
> *定投践行群：7000102069
需要支付2019元人民币入群费并且获取邀请码才可进入，有效期一年。现群内开设投资、编程、英语、学习等课程

> *Lucky BTC Bot：7000101487 每日签到获取免费BTC，第1天领取100聪，第2天领取200聪，第10天领取1000聪，第n天n00聪，中断则从100聪重新开始

我的mixinID：35086
[Mixin小群 链接](https://mixin.one/codes/1484dbc5-44f4-4b39-b3e3-92f6de24cb4e)
《得到app》外链（只有40个名额，先到先得，需要在微信客户端打开～）
[01 为什么Libra有可能成为真正的支付工具](https://m.igetget.com/rush/course/index/xe3WMdD1ARZm4vrYagp6zyW2fl7SJJnMTObBRLklX5909pVjLzn8NGoEOb926yKB?from=singlemessage)
[02 Libra如何应对数字货币的币值稳定](https://m.igetget.com/rush/course/index/LqXmD8xyrBJMVke1aEPWVjJ5fXJF44nvCAlZqW43yVEbEQ4Ab2G0lYz3OvnNjd97)
[03 Libra能成为强势货币吗]( https://m.igetget.com/rush/course/index/xZ5EdYj9eW0zNMlJVBPnnodrfN0IJJ2aF6EXbqGJ29VYVP4v2G1rXOAgR7Ka3Loy)
[04 Libra能突破数字货币的通行风险吗](https://m.igetget.com/rush/course/index/1kqdK6Dbj0v8WmZoxVPyNXdgFrjiGG8NIqRZ1aLnJK3V3wBRLJ3N97Yl25eO4nAg)
[05 DCEP:中国自己的数字货币](https://m.igetget.com/rush/course/index/4JLDzyNjZWeGYXa0v5Px80NoSLJHyyeKuaWkJ6Dxg0RLRP17rmd93lERV8kMxO6g)
[06 DCEP的设计和发行逻辑有何创新](https://m.igetget.com/rush/course/index/0bJ9m5rBVk6q2MzXd4wln9dEfVqCOOr6h1gWr2KGOEbJbQWov1aEOj7NxGgy3ZKn)
[结语｜互联网创业思维，不适合金融领域](https://m.igetget.com/rush/course/index/J8VKqm0b9ERnzNBaYvQYVNnDf8aHaa6ku2m7ea4ZBkqKqPx257G1ZyglX3oL6DAj)
