# Flutter VS React Native

---

| 比较条件 | Flutter | 反应本机 |
| --- | --- | --- |
| 它是什么？ | 一个可移植的 UI 工具包，用于从单个代码库跨移动、网络和桌面*构建本地编译的应用程序 | 使用 React 构建本机应用程序的框架 |
| 正式发布 | 2018 年 12 月，Google I/O | 2015年3月，F8大会 |
| 由...制作 | 谷歌 | Facebook |
| 免费和开源 | 是的 | 是的 |
| 编程语言 | Dart | JavaScript |
| 人气 | Github上的 120,000 颗星（2021 年 5 月） | Github上的 95,300 颗星（2021 年 5 月） |
| 热重载 | 是 | 是 |
| 原生性能 | 伟大的 | 伟大的 |
| 用户界面 | Flutter 应用程序在最新的操作系统上看起来和在旧版本上一样好。、由于它们只有一个代码库，因此这些应用程序在iOS和Android上的外观和行为都相似——但多亏了 Material Design 和 Cupertino 小部件，它们还可以模仿平台设计本身。这怎么可能？ Flutter 包含两套符合特定设计语言的 widgets： Material Design widgets 实现了 Google 的同名设计语言；Cupertino widgets 模仿 Apple 的 iOS 设计。`这意味着您的 Flutter 应用程序将在每个平台上看起来和行为自然，模仿它们的原生组件。` |`应用程序组件看起来就像本机组件（例如，` iOS设备上的按钮看起来就像本机 iOS 按钮，在Android上也一样）。React Native在底层使用原生组件这一事实应该让您相信，在任何 OS UI 更新之后，您的应用程序的组件也会立即升级。也就是说，这可能会破坏应用程序的用户界面，但这种情况很少发生。 `如果您希望您的应用程序在各个平台上看起来几乎相同`——以及在旧版本的操作系统上（如 Flutter 实现的）——`那么请考虑使用第三方库`（比如这个）。它们将使您能够使用 Material Design 组件来代替原生组件。|
| 共享代码 | 借助 Flutter 2（于 2021 年 3 月发布），我们可以使用相同的代码库将原生应用程序发布到五种操作系统：iOS、Android、Windows、macOS 和 Linux；以及针对 Firefox、Chrome、Safari 或 Edge 等浏览器的网络体验。Flutter 甚至可以嵌入到汽车、电视和智能家电中。（_来源_）。也许 Flutter 2 中最大的一个公告是对网络的生产质量支持。它可用于：* `渐进式网络应用程序 (PWA)`将网络的影响力与桌面应用程序的功能相结合，* `单页应用程序 (SPA)`，加载一次并在互联网服务之间传输数据。* `现有的移动应用程序`——允许 Flutter 应用程序在桌面上运行。| `iOS和Android` – 但有一些精选的库允许您使用相同的代码来构建`iOS、Android、Web 和 Windows10 应用程序`。> 您还可以将移动、桌面和网络应用程序中的共享代码提取到单独的存储库；将其视为一个单独的项目；然后以与另一个依赖项相同的方式注入它。> 这使开发人员可以专注于为特定平台编写代码，而不必考虑与另一个平台的兼容性。|| 使用此技术制作的热门应用 | 阿里巴巴的闲鱼应用程序、汉密尔顿音乐剧的汉密尔顿应用程序、Google Ads 应用程序、飞利浦 Hue、My BMW | Instagram、Facebook、Facebook 广告、Skype、特斯拉 |
| 上市时间 | 通常比本机开发快得多。 | 可能与使用 Flutter 进行开发一样快。> 然而…> React Native 使用 bridge 和 native 元素，因此它可能需要针对每个平台进行单独优化——这是基于 widget 的 Flutter 不会遇到的问题。它可能会使使用 React Native开发应用程序的时间更长。|
| 竞争优势 |* 丰富的小部件带来出色的外观和感觉；* 快速增长的社区和知名度；* Flutter 团队大力支持的优秀文档（这使得开始使用 Flutter 进行开发变得容易）；* 改进 Flutter for Web，提供跨移动和 Web 平台的同一个代码库的潜力* 难以超越上市时间长度|* 稳定性（上市 5 年以上）；* 许多成功的、杰出的市场参与者都在使用 React Native；* 成熟、广阔的社区；* 简单易学的技术；* 大量的教程和库，可以快速轻松地开发；* 代码可以轻松地重用于Web 应用程序和桌面应用程序开发。|
| 当它不是最合适的时候 | ```如果…> • 您的应用程序需要支持 3D Touch（目前，Flutter 不支持 3D – 但它在 Flutter 团队的长期路线图上具有特色）> •您的应用程序设计是特定于平台的> • 您的应用程序需要与操作系统进行多次交互；或者需要稀有的、鲜为人知的原生库> • 您需要一个简约的用户界面，但依赖于大量使用手机硬件（例如播放音乐或仅拍照的应用程序）> • 您想创建一个免安装应用程序（小型应用程序）> 如果您的应用听起来像上述任何一种，那么您最好选择原生应用开发。> 在此处阅读有关这些案例的更多信息\>>```| 如果…> • 您的应用需要在后台处理不太常见或非常具体的任务（如计算）> • 您需要通过蓝牙进行自定义通信（这可能很难使用 React Native 实现）> • 您想创建一个仅适用于 Android 的应用程序> 事实上，如果你想构建一个 iOS 应用程序并且你了解 JavaScript，请考虑 React Native——但如果你想要一个仅限 Android 的应用程序，最好与另一个团队一起构建本机。为什么？现在，iOS 比 Android 有更好的支持。> 如果您的应用听起来像以上任何一种情况，您最好考虑选择原生应用开发。|



Image:

![support](https://img.shields.io/badge/platform-flutter%7Cdart%20vm-ff69b4.svg?style=flat-square)

Image with link:

[![pub package](https://img.shields.io/pub/v/markdown_widget.svg)](https://pub.dartlang.org/packages/markdown_widget)

Html Image:

<img width=80% height=80% src="https://raw.githubusercontent.com/dd9913762113/sources/main/test/images/hottopic160228_1.jpg"/>

Video:

<video src="http://commondatastorage.googleapis.com/gtv-videos-bucket/sample/BigBuckBunny.mp4">

