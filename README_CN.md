# Padavan-CAKE <p align="right"><a href="README_TW.md">繁體中文</a> | 简体中文 | <a href="README.md">English</a></p>

## 🏆全球首发！

## 🚀 改善网络延迟！TW641 移植 CAKE (sch_cake) Padavan 路由器固件：云端编译懒人包 (支持 142 款机型)

**TW641 移植 CAKE (sch_cake) Padavan 路由器韌體：雲端編譯懶人包 (支援 142 款機型)-Padavan-恩山无线论坛 - Powered by Discuz!**

**[简体中文版请见一楼！]**

**<https://www.right.com.cn/forum/forum.php?mod=viewthread&tid=8465588&fromuid=1047490&fromuser=TW641>**

**TW641 移植 CAKE (sch_cake) Padavan 路由器韌體：雲端編譯懶人包 (支援 142 款機型)-Padavan-恩山无线论坛 - Powered by Discuz!**

**[For English version, please see the 2nd floor!]**

**<https://www.right.com.cn/forum/forum.php?mod=redirect&goto=findpost&ptid=8465588&pid=22706932&fromuid=1047490&fromuser=TW641>**

**TW641 移植 CAKE (sch_cake) Padavan 路由器韌體：雲端編譯懶人包 (支援 142 款機型)-Padavan-恩山无线论坛 - Powered by Discuz!**

**[繁體中文版請見三樓！]**

**<https://www.right.com.cn/forum/forum.php?mod=redirect&goto=findpost&ptid=8465588&pid=22707025&fromuid=1047490&fromuser=TW641>**

👉 **上一篇固件分享、实测结果与刷机教程：**

[固件分享]【Padavan + CAKE 移植】TP-Link Archer C2 V1 (with 3.4.113 Linux Kernel) & 斐讯 Phicomm K2P A1/A2 (with 4.4.198 Linux Kernel)

<https://www.mobile01.com/topicdetail.php?f=110&t=7220226>

这是我个人独立完成、世界上第一个成功将 **CAKE 流量控制算法**移植到 Padavan (包含 Linux Kernel 3.4.113 与 Linux Kernel 4.4.198 两种 Linux 内核版本) 的**本项目**！

我不仅复活了经典的 TP-Link Archer C2 与 斐讯 Phicomm K2P，这次更加码扩充支持机型选项，**一口气精准支持 142 种路由器机型选项**，并拥有多达 **14 种多国语言包的支持**！

---

**🎉 特别致谢区块：**

感谢以下前辈与伙伴在开源与网络技术领域的启发与贡献：

* **🏢 企业与组织：**
    * GL.iNet 深圳市广联智通科技有限公司 ( <https://www.gl-inet.cn/> )
    * LibreQoS LibreQoE, LLC ( <https://libreqos.io/> )
* **💻 开发者与贡献者：**
    * Alfie Zhao
    * Allen Liu
    * Dave Täht
    * Frantisek Borsik (Frank)
    * Jacqueline Wang
    * Wingsley Yik
    * 佐须之男 (ForgotFun) [@佐须之男](https://www.right.com.cn/forum/space-uid-46505.html)

**💡 特别回忆录：那些年我们一起搞的第三方固件**

其实当年我是负责 Tomato Phoneix 不死鸟的繁体中文翻译。

下方附上当年 Tomato Phoneix 不死鸟的百度网盘下载链接与历史截图：

<http://pan.baidu.com/s/1jIGpbQe>

<a href="images/Tomato-Phoenix-Archive.png" target="_blank"><img style="max-width: 100%; height: auto; margin-top: 10px; border: 1px solid #ccc; border-radius: 8px;" src="images/Tomato-Phoenix-Archive.png" alt="Tomato Phoenix 繁体中文版历史截图"></a>

请看下方图片！这是我当年和陆明峰、佐须之男合作时，他亲手写的感谢纸条和送的礼物。

我直到今天都还留着，而且这些感谢如今都仍记在心里！

<a href="images/ForgotFun.jpg" target="_blank"><img style="max-width: 100%; height: auto; border: 1px solid #ccc; border-radius: 8px;" src="images/ForgotFun.jpg" alt="佐须之男的感谢纸条"></a>

**🤝 支持佐须之男 (ForgotFun)：**

这不是我的账号，但就让我们一起帮他一把吧，感谢他多年来的开源贡献。如果您想支持他，请前往他的官方网站了解支持方式：

<https://www.tomato.org.cn/donate-us.html>

<https://forgotfun.org/helpus.html>

> *「佐须之男长期致力于国内第三方免费固件的开发，期间靠的是广大用户的支持才能坚持到现在。一路走来的过程中有喝彩也有唏嘘，但我从未停止过脚步，并希望我能继续再坚持下去。希望广大的用户在力所能及的前提下能给予我些赞助，让这份梦想得以延续。」*

顺带一提，最近在论坛看到有版友发帖问：恩山为什么没有gl-inet版块？( <https://www.right.com.cn/forum/forum.php?mod=viewthread&tid=8463592&fromuid=1047490&fromuser=TW641> )

借着这篇技术分享，我也想在此向管理员许愿：**强烈希望能开立一个 GL.iNet 专属板块！** 这样大家讨论相关技术跟固件会更方便集中！

---

### 📌 固件版本特色速览

* **内核突破：** 提供 Linux Kernel 3.4.113 与 4.4.198 双版本，大幅领先原厂旧内核。
* **性能解放：** 全系列整合 CAKE 流量调度、HWNAT (硬件加速) + SFE (软件加速)。
* **界面优化：** 内建繁体中文 (支持替换简体)，并针对 1080P 宽屏幕进行排版优化。
* **稳定提升：** 修复 MT7610E 无线驱动断线问题，启用快速重连；4.4 版本采用最稳定的 Iptables 1.8.7 与 libmnl 1.0.5 组合。
* **安全防护：** 全面升级 Busybox 1.37.0，修复多个 CVE 高风险漏洞。

*(注：我先前的旧项目放在旧账号 TWShiyuLiou1997，现在成功运作的成品都会集中在新的 **TW641** 账号中，两个主页我都放在下面，请以新仓库的 Actions 为主哦！如果您觉得这个项目有帮助到您，请帮我点击下方链接 **Follow** 我的 GitHub 账号给予支持与鼓励！)*

👉 我的全新 GitHub 主页 (TW641)：<https://github.com/TW641>

👉 我的旧版 GitHub 主页 (TWShiyuLiou1997)：<https://github.com/TWShiyuLiou1997>

---

## 🌍 来自国际开源界的肯定！

**本项目**不仅在技术论坛发布，更在国际开源社区引起了巨大的反响，这对身为唯一开发者的我来说，是极大的肯定与惊喜：

* **来自捷克的国际开源大神的亲自认可：** 我的 GitHub 项目成功获得了 **LibreQoS 运营长 Frantisek (Frank) Borsik** 的亲自追踪与肯定！Frank 来自**捷克布拉格地区**，在国际开源网络界大有来头，曾负责知名开源路由器 Turris (OpenWrt) 以及 RF elements 的核心推广。这代表**本项目**已经成功打入全球「对抗 Bufferbloat (缓冲膨胀)」社区的最核心圈！能与来自捷克的专家交流，真的是莫大的荣幸。
* **来自日本的顶尖网络学者的跨国关注：** 来自日本顶尖名校 **庆应义塾大学 (Keio University) 的 Dikshie 博士** 也亲自给予**此项目**关注与认可！Dikshie 博士专攻 P2P 网络、互联网架构与网络科学，能获得这类精于底层网络基础设施的重量级学者肯定，证明了这份算法移植的技术含金量极高！

<div align="center">
  <a href="images/followers.png" target="_blank"><img style="max-width: 100%; height: auto; border: 1px solid #ccc; border-radius: 8px;" src="images/followers.png" alt="国际认可" /></a>
  <br>
  <em><small>[图说：来自捷克 LibreQoS 运营长与日本庆应大学顶尖学者的亲自追踪认可]</small></em>
</div>

* **官方社区致敬：** LibreQoS 官方甚至在其各大国际社交平台上发布了**发文致敬**，将**这个项目**誉为给 Dave Täht 的 **"Time-Traveling Valentine's Gift" (穿越时空的情人节礼物)**！能让开源技术贡献跃上国际版面，真的是非常感动的时刻！大家有兴趣可以去搜索 LibreQoS 官方账号查看。

---

## 🕊️ In Loving Memory of Dave Täht (纪念缓冲膨胀缓解之魂)

<a href="images/davetaht.jpg" target="_blank"><img style="max-width: 100%; height: auto; border: 1px solid #ccc; border-radius: 8px;" src="images/davetaht.jpg" alt="Dave Täht"></a>
*<small>[图片来源: LibreQoS]</small>*

> **"When you miss Dave, modprobe sch_cake!"**
> — *A tribute to the soul of bufferbloat mitigation.*

### **他的心愿，我来实现**
### **His wish, I finished.**
Dave Täht (1965–2025) 是一位伟大的网络技术开源贡献者。他生前拒绝了无数高薪合约，只为了将他的代码保持免费与开源。因为他在 Bufferbloat (缓冲膨胀) 领域的研究，今天无数的设备才能享有顺畅的网络。

**🏹 穿越时空的巧合：Archer (弓箭手) 与 Arrow (箭)**
有句成语说：**「一支穿云箭，千军万马来相见」**
Dave 就像是那支划破网络拥塞黑夜的穿云箭。巧合的是，当年他于 2015 年展示 CAKE 算法时，使用的测试机是 **TP-Link Archer C7**；2016 年他用 **odroid C2** 做测试驱动。
今天，我成功将他的这项**遗作**移植到了 **TP-Link Archer C2** 身上。Dave 是那位弓箭手 (Archer)，这段代码是那支箭 (Arrow)，而我成功命中了目标：一个没有 Bufferbloat 的美好世界。

**🧩 迟来的约定：MT76 的预言**
2016 年，Dave 曾在**博客**写下他苦寻不到一台基于 MediaTek (MT76) 的路由器，他预言这会是未来开源网络的新星。几年后的今天，我透过**这个项目**，让成千上万台 MT76 设备顺利跑起了他撰写的 CAKE 算法。
**"Dave，这台 MT76，我终于帮你跑起来了！"**

**🌟 点亮星星，让爱延续**
Dave 的姓氏 **"Täht"** 在爱沙尼亚语中正是**「星星」**的意思。如果您使用了我的固件，请到 GitHub 开源项目纪念仓库上帮我点亮那颗「Star」，延续 Dave Täht 的精神！

👉 开源移植代码与纪念仓库：<https://github.com/TW641/sch_cake

👉 阅读完整的 Dave Täht 纪念文章 (LibreQoS)：<https://libreqos.io/2025/04/01/in-loving-memory-of-dave/>

---

## 🔧 科普小教室｜为什么你的网络需要 CAKE？

CAKE 建立在 fq_codel 的成熟基础上，是一种最先进的主动队列管理 (AQM) 技术。借助 CAKE，大量传输不再中断即时应用程序。即使家人在下载大文件，你的在线游戏依然能维持低 Ping 值✅。

### 🍰 为什么叫 "CAKE" (蛋糕)？
这个名字源自电影《2010》与游戏《Portal》，代表着「人人都有蛋糕吃」的美好愿景。它实际上是 Common Applications Kept Enhanced 的缩写。简单来说，它能让网络在多人使用时，依然人人有带宽，顺畅不卡顿。

### ⚙️ 快速看懂运作原理
<a href="images/CAKE.png" target="_blank"><img style="max-width: 100%; height: auto; border: 1px solid #ccc; border-radius: 8px;" src="images/CAKE.png" alt="CAKE 原理"></a>

CAKE 最主要的目标是消除 Bufferbloat（缓冲膨胀）。
**它的核心功能：**

1.  **流量整形 (Shaping)：** 限制进出带宽，确保**网络数据包**不会在调制解调器等节点堆积。
2.  **公平排队 (Fair Queuing)：** 确保每个设备都能公平分配到带宽，防止单一程序霸占网络。
3.  **自动化管理：** 相比旧型的 QoS，CAKE 通常只需设定下载与上传带宽即可达到极佳效果。

⚠️ **注意：** CAKE 比较消耗 CPU 性能。在硬件较弱的路由器上处理超过 350 Mbps 以上的带宽时，可能会成为性能瓶颈。

### 🔍 怎么确认 CAKE 完美运行
<a href="images/VerifyCAKE1.png" target="_blank"><img style="max-width: 100%; height: auto; margin-bottom: 5px; border: 1px solid #ccc; border-radius: 8px;" src="images/VerifyCAKE1.png" alt="确认运行图1"></a>
<a href="images/VerifyCAKE2.png" target="_blank"><img style="max-width: 100%; height: auto; margin-bottom: 5px; border: 1px solid #ccc; border-radius: 8px;" src="images/VerifyCAKE2.png" alt="确认运行图2"></a>
<a href="images/VerifyCAKE3.png" target="_blank"><img style="max-width: 100%; height: auto; margin-bottom: 5px; border: 1px solid #ccc; border-radius: 8px;" src="images/VerifyCAKE3.png" alt="确认运行图3"></a>
<a href="images/VerifyCAKE4.png" target="_blank"><img style="max-width: 100%; height: auto; margin-bottom: 5px; border: 1px solid #ccc; border-radius: 8px;" src="images/VerifyCAKE4.png" alt="确认运行图4"></a>

---

## 🚀 Supported Device Matrix (精准支持 142 种机型选项清单)

请先在下方找到你的路由器品牌与商品名称，括号 **( )** 内的就是稍后在 GitHub 编译菜单中需要输入的**「选项代码」**！

### 🟢 Kernel 3.4 经典老爷机 (共 125 种选项)

*(注：若下方图片无法加载，请直接参考下方的文字表格)*
<a href="images/list1.png" target="_blank"><img style="max-width: 100%; height: auto; border: 1px solid #ccc; border-radius: 8px;" src="images/list1.png" alt="Kernel 3.4 清单"></a>

| 品牌 (A-Z) | 支持型号：商品名称 `(选项代码)` |
| :--- | :--- |
| **5K** | 5K-W20 `(5K-W20)` |
| **A5** | A5-V11 16M `(A5-V11_16M)`, A5-V11 4M `(A5-V11_4M)`, A5-V11 8M `(A5-V11_8M)` |
| **ATEL** | ALR-U270 `(ALR-U270)` |
| **ASUS (华硕)** | RP-AC56 `(RP-AC56)`, RT-AC1200 `(RT-AC1200)`, RT-AC1200GU `(RT-AC1200GU)`, RT-AC1200HP `(RT-AC1200HP)`, RT-AC51U `(RT-AC51U)`, RT-AC54U `(RT-AC54U)`, RT-N10 C1 `(RT-N10C1)`, RT-N11P `(RT-N11P)`, RT-N11P B1 `(RT-N11PB1)`, RT-N12+ `(RT-N12plus)`, RT-N13U B1 `(RT-N13UB1)`, RT-N14U `(RT-N14U)`, RT-N56U `(RT-N56U)`, RT-N56U GE2 `(RT-N56U-GE2)`, RT-N56U B1 `(RT-N56UB1)` |
| **BELKIN** | F9K1103 `(F9K1103)` |
| **D-Link (友讯)** | DIR-300 B1 `(DIR-300B1)`, DIR-300 B7 `(DIR-300B7)`, DIR-320 B1 `(DIR-320B1)`, DIR-620 A1 `(DIR-620A1)`, DIR-620 D1 `(DIR-620D1)`, DIR-860L `(DIR-860L)`, DIR-882 `(DIR-882)` |
| **GL.iNet** | GL-MT300A `(GL-MT300A)`, GL-MT300N `(GL-MT300N)`, GL-MT300N V2 `(GL-MT300NV2)` |
| **HiWiFi (极路由)** | HC5661A `(HC5661A)` |
| **Kroks** | KNDRT31R26 `(KNDRT31R26)`, KNDRT31R3 `(KNDRT31R3)` |
| **Linksys** | EA-8100 `(EA-8100)` |
| **MQMaker** | WiTi 256M `(MQ-WITI-256)`, WiTi 512M `(MQ-WITI-512)` |
| **Newifi (新路由)** | Newifi D1 `(NEWIFI-D1)`, Newifi D2 `(NEWIFI-D2)`, Newifi Mini `(NEWIFI-MINI)`, Newifi Y1S `(NEWIFI-Y1S)` |
| **Nexx** | WT3020A `(WT3020A)`, WT3020H `(WT3020H)`, WT3020H 16M `(WT3020H16M)` |
| **Phicomm (斐讯)** | PSG1218 256M `(256PSG1218)`, PSG1218 `(PSG1218)` |
| **Samsung (三星)** | SWR1100 `(SWR1100)` |
| **Sercomm** | RT-S1010 `(RT-S1010)`, Smartbox SPI `(SMARTBOX_SPI)`, SMBX Pro NAND `(SMBXPRONAND)`, SMBX Turbo `(SMBXTURBO)` |
| **SNR** | SNR-MD1 `(SNR-MD1)`, SNR-ME1 `(SNR-ME1)`, SNR-W4N-M `(SNR-W4N-M)`, SNR-W4N-M USB `(SNR-W4N-M_USB)` |
| **Totolink** | A3004NS `(A3004NS)` |
| **TP-Link** | Archer C2 V1 `(TL_C2-V1)`, Archer C20 V1 `(TL_C20-V1)`, Archer C20 V1 16M `(TL_C20-V1_16M)`, Archer C20 V4 `(TL_C20-V4)`, Archer C20 V5 `(TL_C20-V5)`, Archer C5 V4 `(TL_C5-V4)`, Archer C50 V1 `(TL_C50-V1)`, Archer C50 V3 `(TL_C50-V3)`, Archer C50 V4 `(TL_C50-V4)`, EC220-G5 V2 `(TL_EC220_G5-V2)`, MR200 V1 `(TL_MR200-V1)`, MR3020 V3 `(TL_MR3020-V3)`, MR3420 V5 `(TL_MR3420-V5)`, WDR7300 V5 `(TL_WDR7300-V5)`, WR840N V4 `(TL_WR840N-V4)`, WR840N V4 USB `(TL_WR840N-V4_USB)`, WR840N V5 `(TL_WR840N-V5)`, WR840N V5 RU `(TL_WR840N-V5_RU)`, WR840N V6 `(TL_WR840N-V6)`, WR841N V13 `(TL_WR841N-V13)`, WR841N V13 USB `(TL_WR841N-V13_USB)`, WR841N V14 `(TL_WR841N-V14)`, WR841N V14 8M `(TL_WR841N-V14_8M)`, WR842N V5 `(TL_WR842N-V5)`, WR845N V3 `(TL_WR845N-V3)`, WR845N V4 `(TL_WR845N-V4)` |
| **Tuoshi** | TS7620N `(TS7620N)` |
| **Ubiquiti** | EdgeRouter X `(UBNT-ERX)` |
| **Unielec** | U7621-06 `(U7621-06)` |
| **Wall-AP** | Wall-AP `(WALL-AP)` |
| **Xiaomi (小米/红米)** | Mi Router 3 `(MI-3)`, Mi Router 3 SPI `(MI-3_SPI)`, Mi Router 3C `(MI-3C)`, Mi Router 3G `(MI-R3G)`, Mi Router 3G SPI `(MI-R3G_SPI)`, Mi Router 3G v2 `(MI-R3Gv2)`, Mi Router 3 Pro `(MI-R3PRO)`, Mi Router 3P SPI `(MI-R3P_SPI)`, Mi Router 4 `(MI-4)`, Mi Router 4A 100M `(MI-4A_100M)`, Mi Router 4C `(MI-4C)`, Mi Router Mini `(MI-MINI)`, Mi Router Nano `(MI-NANO)`, Xiaomi Router 2100 `(R2100)`, Redmi Router AC2100 `(RM-AC2100)` |
| **Youhua (友华)** | WR1200JS `(WR1200JS)` |
| **Youku (优酷)** | YK-L1 `(YK-L1)`, YK-L1C `(YK-L1C)` |
| **ZBT** | WE1326 `(ZBT-WE1326)`, WE1626 `(ZBT-WE1626)`, WE826-T2 `(ZBT-WE826T2)`, WG3526 `(ZBT-WG3526)`, WG3526-32 `(ZBT-WG3526-32)`, WR8305RT `(ZBT-WR8305RT)` |
| **ZTE (中兴)** | E8820S `(ZTE_E8820S)` |
| **ZyXEL (合勤/Keenetic)** | KN-4G3 `(KN-4G3)`, KN-4G3B `(KN-4G3B)`, KN-EXTRA `(KN-EXTRA)`, KN-EXTRA2 `(KN-EXTRA2)`, KN-GIGA3 `(KN-GIGA3)`, KN-LITE `(KN-LITE)`, KN-LITE2 `(KN-LITE2)`, KN-LITE3 `(KN-LITE3)`, KN-LITE3B `(KN-LITE3B)`, KN-OMNI `(KN-OMNI)`, KN-OMNI2 `(KN-OMNI2)`, KN-START2 `(KN-START2)`, KN-ULTRA2 `(KN-ULTRA2)`, KN-VIVA `(KN-VIVA)` |

### 🔵 Kernel 4.4 进阶机型 (共 17 种选项)

*(注：若下方图片无法加载，请直接参考下方的文字表格)*
<a href="images/list2.png" target="_blank"><img style="max-width: 100%; height: auto; border: 1px solid #ccc; border-radius: 8px;" src="images/list2.png" alt="Kernel 4.4 清单"></a>

| 品牌 (A-Z) | 支持型号：商品名称 `(选项代码)` |
| :--- | :--- |
| **D-Link (友讯)** | DIR-878 `(DIR-878)`, DIR-882 `(DIR-882)` |
| **JCG (捷稀)** | 836PRO `(JCG-836PRO)`, AC860M `(JCG-AC860M)`, Q20 `(JCG-Q20)`, Y2 `(JCG-Y2)` |
| **Motorola (摩托罗拉)** | MR2600 `(MR2600)` |
| **Netgear (网件)** | BZV `(NETGEAR-BZV)` |
| **Newifi (新路由)** | Newifi 3 `(NEWIFI3)` |
| **Phicomm (斐讯)** | K2P `(K2P)`, K2P Nano `(K2P-NANO)`, K2P USB `(K2P-USB)` |
| **Xiaomi (小米/红米)** | CR660x `(CR660x)`, Mi Router 3G `(MI-R3G)`, Mi Router 3 Pro `(MI-R3P)`, Redmi Router 2100 `(RM2100)` |
| **XiaoYu (小渔)** | XY-C1 `(XY-C1)` |

---

## 🌐 支持 14 种多国语言
我相信网络无国界，现在固件编译环境已支持 14 种语言：

* **English_Only** (默认英文)
* **CN** - **繁体中文**，请在菜单填入 **CN** 即可获得。
* 另外包含：俄语 (RU), 捷克语 (CZ), 德语 (DE), 法语 (FR) 等共 14 国语言。

## 🇨🇳 需要简体中文版本的人，请看这边教学

如果你需要替换成简体中文字典，请依照以下步骤操作：

1.  请先前往并找到简体中文字典档的历史纪录版本：
    - 4.4 内核版本字典档：<https://github.com/TW641/padavan-4.4/blob/79a0cf68ee0a1781d1d7184cfb87a82f0cd68c2d/trunk/user/www/dict/CN.dict>
    - 3.4 内核版本字典档 (ng)：<https://github.com/TW641/padavan-ng/blob/e0f189d6ac747909f14128c52cb84dea27c328cb/trunk/user/www/dict/CN.dict>
2.  进入上方链接后，按下 **复制 (Copy)** 按钮，复制全部的字典内容。
3.  接着，回到你自己 Fork 出来的 main / master 项目分支中，找到字典档路径 (`trunk/user/www/dict/CN.dict`)，进行「**编辑 (Edit) -> 贴上刚刚复制的内容 (Paste) -> 存储 (Commit changes)**」，三个步骤搞定简体中文字典！
4.  **⚠️ 最后请务必更改 Workflow 路径：**
    - **4.4 内核版本：** 请编辑 <https://github.com/TW641/padavan-4.4/blob/main/.github/workflows/CI.yml#L112>
    将 `git clone --depth=1 https://github.com/TWShiyuLiou1997/padavan-4.4.git /opt/rt-n56u` 里面的网址，改成**你刚刚自己 fork 的 github 账号和对应的项目名称**。
    - **3.4 内核版本 (ng)：** 请编辑 <https://github.com/TW641/padavan-builder-workflow/blob/main/.github/workflows/build.yml#L260>
    将 `echo "PADAVAN_REPO=https://github.com/TWShiyuLiou1997/padavan-ng" >> $GITHUB_ENV` 里面的网址，改成**你刚刚自己 fork 的 github 账号和对应的项目名称**。

---

## 🍰 A PIECE OF CAKE！超简单、超轻松的云端编译法 (免架环境，5分钟搞定！)

这真的是 Piece of cake！我已经把所有设定都写进 GitHub Actions 里了。你完全不需要会写代码，只要会点击鼠标，几分钟就能得到专属你的固件档！

### 👉 简单 6 步骤：

1.  **Step 1：注册登录 GitHub 并点亮「星星」🌟 (纪念 Dave Täht)**
    前往 GitHub 注册一个免费账号并登录。请前往项目纪念仓库，顺手**点击**右上角的 **「Star ⭐」** 向 Dave 致敬！
    
    👉 <https://github.com/TW641/sch_cake>
    
2.  **Step 2：选择你的路由器机型并 Fork 项目**
    根据你刚刚在上方表格找到的代码，进入对应链接后，**点击**右上角的 **「Fork」** 按钮：
    
    🟢 **经典老机 (内核 3.4)** 👉 <https://github.com/TW641/padavan-builder-workflow>
    
    🔵 **进阶机型 (内核 4.4)** 👉 <https://github.com/TW641/padavan-4.4>
    
3.  **Step 3：启用 Actions 功能**
    进入你刚 Fork 的项目，**点击**上方菜单的 **「Actions」**，并**点击**绿色按钮 **「I understand my workflows, go ahead and enable them」** 启用它。
    
4.  **Step 4：选择正确的 Workflow**
    在 Actions 页面左侧，根据机型**点击**对应的流程名称：
    
    🟢 **3.4 机型：** Build firmware (Ultimate Fix - Early Size Check)
    
    🔵 **4.4 机型：** Custom-Router-Build-Final-Fix
    
6.  **Step 5：一键开始编译与自定义参数 (IP/密码)**
    **点击**画面右边的 **「Run workflow」** 下拉菜单。
    **【最重要的一步】** 在 Target Model 栏位中输入你的**「路由器选项代码」**(需与表格括号内一模一样)；语言菜单请填入 **CN** (即代表繁体中文，若是替换过字典则为简体中文)。
    **自定义设定 (Customization)：**你可以在 JSON 栏位中直接修改默认 IP 与密码，若不修改，将使用默认值。最后**点击**绿色的 **「Run workflow」** 按钮即可！
    
7.  **Step 6：下载与刷机**
    等待约 10~15 分钟，流程亮起绿色打勾图标 ✅ 后，**点击**进去该次流程，拉到最下方找到 **「Artifacts」** 下载压缩档，里面的 .bin 文件就是你的专属固件！

**欢迎大家交流测试心得！只谈技术，享受网络！**
