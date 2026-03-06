# Padavan-CAKE

> [繁體中文](README_TW) | [简体中文](README_CN) | English

## 🏆 🇹🇼 World Premiere! Taiwan No.1! 🇹🇼

## 🚀 Improve Network Latency! TW641 Ported CAKE (sch_cake) Padavan Router Firmware: Cloud Compilation Guide (Supports 142 Models)

**For English version, please visit: [https://www.mobile01.com/topicdetail.php?f=110&t=7231531#92875608](https://www.mobile01.com/topicdetail.php?f=110&t=7231531#92875608)**

**繁體中文版本，請見：[https://www.mobile01.com/topicdetail.php?f=110&t=7231531#92875605](https://www.mobile01.com/topicdetail.php?f=110&t=7231531#92875605)**
 
👉 **Previous Firmware Release, Test Results & Flashing Guide:** 

[Firmware Release] [Padavan + CAKE Port] TP-Link Archer C2 V1 (with 3.4.113 Linux Kernel) & Phicomm K2P A1/A2 (with 4.4.198 Linux Kernel)

[https://www.mobile01.com/topicdetail.php?f=110&t=7220226](https://www.mobile01.com/topicdetail.php?f=110&t=7220226)

This is my independent project and the world's first successful port of the **CAKE traffic control algorithm** to Padavan (including both Linux Kernel 3.4.113 and Linux Kernel 4.4.198)!
 
Not only have I resurrected the classic TP-Link Archer C2 and Phicomm K2P, but I have also significantly expanded the supported device list. This project **accurately supports 142 router models at once**, with up to **14 multi-language packs available**!
 
## 📌 Firmware Features Overview
 
* **Kernel Breakthrough:** Provides dual versions of Linux Kernel 3.4.113 and 4.4.198, significantly ahead of the original old kernels.
* **Performance Unleashed:** Fully integrated CAKE traffic scheduling, HWNAT (Hardware Acceleration) + SFE (Software Acceleration).
* **UI Optimization:** Built-in multi-language support, with layout optimized for 1080P widescreen.
* **Stability Boost:** Fixed MT7610E wireless disconnect issues, enabled fast reconnection; the 4.4 version uses the most stable Iptables 1.8.7 and libmnl 1.0.5 combo.
* **Security Enhancements:** Fully upgraded Busybox to 1.37.0, fixing multiple high-risk CVE vulnerabilities.

*(Note: My previous older projects were hosted under my old account TWShiyuLiou1997. Now, all successful builds are centralized in the new **TW641** account. Please refer to the new repository's Actions! If you find this project helpful, please click the link below to **Follow** my GitHub account for support and encouragement!)*

👉 My New GitHub Profile (TW641): [https://github.com/TW641](https://github.com/TW641)

👉 My Old GitHub Profile (TWShiyuLiou1997): [https://github.com/TWShiyuLiou1997](https://github.com/TWShiyuLiou1997)

---

## 🌍 Recognition from the Global Open Source Community & Presidential Level! (True Digital Diplomacy)
 
**This project** was not only successfully released on Taiwanese forums but also caused a huge response in the international open-source community, which is a massive validation and surprise for me as a solo developer:

* **🇹🇼🤝🇨🇿 Endorsed by Czech Open Source Expert:**
My GitHub project successfully gained the attention and approval of **Frantisek (Frank) Borsik, COO of LibreQoS**! Frank, from **Prague, Czech Republic**, is a prominent figure in the global open-source networking community, having previously promoted the core of the well-known open-source router Turris (OpenWrt) and RF elements. This means **this project** has successfully broken into the core circle of the global "Anti-Bufferbloat" community! It's an immense honor to interact with experts from the friendly Czech Republic.

* **🇹🇼🤝🇯🇵 Cross-Border Attention from Top Japanese Network Scholar:**
Dr. Dikshie from **Keio University**, a top university in Japan, also paid attention to and endorsed **this project**! Dr. Dikshie specializes in P2P networks, internet architecture, and network science. Receiving such recognition from a heavyweight scholar who excels in underlying network infrastructure proves that the technical value of this algorithm porting is extremely high!

<a href="images/followers.png" target="_blank"><img style="max-width: 100%; height: auto; border: 1px solid #ccc; border-radius: 8px;" src="images/followers.png" alt="GitHub Endorsement Proof"></a>

*[Image: Personal tracking and endorsement from LibreQoS COO and a top scholar from Keio University]*

* **🇹🇼 Presidential-level Digital Diplomacy:**
LibreQoS officially published a **tribute post** on international social platforms like X (Twitter), Facebook, and LinkedIn, praising **this project** as a **"Time-Traveling Valentine's Gift"** for Dave Täht, and unprecedentedly tagged the **President of Taiwan, Lai Ching-te, former President Tsai Ing-wen, and the Presidential Office Spokesperson**! Bringing Taiwan's open-source technical contributions to the international stage is true citizen diplomacy in action! 🇹🇼

<a href="images/Facebook.png" target="_blank"><img style="max-width: 100%; height: auto; margin-bottom: 10px; border: 1px solid #ccc; border-radius: 8px;" src="images/Facebook.png" alt="LibreQoS Facebook Post"></a>
<a href="images/X.png" target="_blank"><img style="max-width: 100%; height: auto; margin-bottom: 10px; border: 1px solid #ccc; border-radius: 8px;" src="images/X.png" alt="LibreQoS X Post"></a>
<a href="images/LinkedIn.png" target="_blank"><img style="max-width: 100%; height: auto; border: 1px solid #ccc; border-radius: 8px;" src="images/LinkedIn.png" alt="LibreQoS LinkedIn Post"></a>

*[Image: LibreQoS official tribute posts across Facebook, X, and LinkedIn]*

**👇 Need Your Support! Let the World See Taiwan's Contribution! 👇**
If you also feel passionate about this "digital diplomacy," please take 10 seconds to click the official LibreQoS social post links below to **Like, Comment, and Share**! Let this transnational tribute from Taiwan be spread to the whole world:
* 👉 **X (Twitter) Post:** [https://x.com/LibreQoS/status/2022688823361126545](https://x.com/LibreQoS/status/2022688823361126545)

* 👉 **Facebook Post:** [https://www.facebook.com/libreqos/posts/pfbid02JCNKynFeQ48FdBMFbVoAoWFDLfgiA55mH3Fyz76xKHdEU86XkxgVziWzXoRYbbT1l](https://www.facebook.com/libreqos/posts/pfbid02JCNKynFeQ48FdBMFbVoAoWFDLfgiA55mH3Fyz76xKHdEU86XkxgVziWzXoRYbbT1l)

* 👉 **LinkedIn Post:** [https://www.linkedin.com/posts/libreqos_davetaht-routers-bufferbloat-activity-7428458742301659136-YAL2](https://www.linkedin.com/posts/libreqos_davetaht-routers-bufferbloat-activity-7428458742301659136-YAL2) 

---

## 🕊️ In Loving Memory of Dave Täht (The Soul of Bufferbloat Mitigation)
<a href="images/davetaht.jpg" target="_blank"><img style="max-width: 100%; height: auto; border: 1px solid #ccc; border-radius: 8px;" src="images/davetaht.jpg" alt="Dave Täht Tribute"></a>

*[Image Source: LibreQoS]*

> **"When you miss Dave, modprobe sch_cake!"**
>
> — *A tribute to the soul of bufferbloat mitigation.*

### **🇹🇼: 他的心願，我來實現 (Tā de xīn yuàn, wǒ lái shí xiàn)** 
### **🇺🇸: His wish, I finished.** Dave Täht (1965–2025) was a great open-source contributor in network technology. He turned down countless high-paying contracts just to keep his code free and open-source. Because of his research in the Bufferbloat field, countless devices today enjoy smooth networking.

**🏹 A Coincidence Across Time: Archer and Arrow**

There is a Chinese idiom: **"A single arrow pierces the clouds, and thousands of troops come to meet."**
 
Dave is like that cloud-piercing arrow tearing through the dark night of network congestion. Coincidentally, when he demonstrated the CAKE algorithm in 2015, the test device he used was the **TP-Link Archer C7**; in 2016, he used an **odroid C2** to test the driver.
 
Today, I successfully ported his **final legacy** to the **TP-Link Archer C2**. Dave is the Archer, this code is the Arrow, and I successfully hit the target: a beautiful world without Bufferbloat.

**🧩 A Belated Promise: The MT76 Prophecy**

In 2016, Dave wrote on his **blog** that he struggled to find a MediaTek (MT76) based router, predicting it would be the rising star of open-source networking.
 
Years later, through **this project**, I've enabled thousands of MT76 devices to smoothly run the CAKE algorithm he wrote.
 
**"Dave, I finally got this MT76 running for you!"**

**🌟 Light a Star, Let the Love Continue**
 
Dave's surname **"Täht"** means **"Star"** in Estonian. If you use my firmware, please go to the GitHub open-source memorial repository and light up that "Star" for me to continue Dave Täht's spirit!
 
* 👉 Open Source Port Code & Memorial Repository: [https://github.com/TW641/sch_cake](https://github.com/TW641/sch_cake)

* 👉 Read the full memorial article for Dave Täht (LibreQoS): [https://libreqos.io/2025/04/01/in-loving-memory-of-dave/](https://libreqos.io/2025/04/01/in-loving-memory-of-dave/)

---

## 🔧 Tech 101 | Why Does Your Network Need CAKE? 
Built on the mature foundation of fq_codel, CAKE is a state-of-the-art Active Queue Management (AQM) technology. With CAKE, heavy bulk transfers no longer interrupt real-time applications. Even if your family is downloading large files, your online games will still maintain a low Ping✅.

### 🍰 Why is it called "CAKE"? 
The name originates from the movie "2010" and the game "Portal", representing the beautiful vision that everyone gets a piece of the cake. It actually stands for Common Applications Kept Enhanced. Simply put, it ensures that when multiple people use the network, everyone still gets bandwidth, keeping things smooth and stutter-free.

### ⚙️ Quick Guide to How It Works
<a href="images/CAKE.png" target="_blank"><img style="max-width: 100%; height: auto; border: 1px solid #ccc; border-radius: 8px;" src="images/CAKE.png"></a>
CAKE's primary goal is to eliminate Bufferbloat.

**Its Core Features:**
* **Traffic Shaping:** Limits ingress and egress bandwidth to ensure **network packets** don't pile up in nodes like modems.
* **Fair Queuing:** Ensures every device gets a fair share of bandwidth, preventing a single application from hogging the network.
* **Automated Management:** Compared to older QoS, CAKE usually only requires setting the download and upload bandwidth limits to achieve excellent results.

⚠️ **Note:** CAKE is relatively CPU-intensive. It may become a performance bottleneck on weaker routers when handling bandwidths over 350 Mbps.

### 🔍 How to Verify CAKE is Running Perfectly
<a href="images/VerifyCAKE1.png" target="_blank"><img style="max-width: 100%; height: auto; border: 1px solid #ccc; border-radius: 8px;" src="images/VerifyCAKE1.png"></a>
<a href="images/VerifyCAKE2.png" target="_blank"><img style="max-width: 100%; height: auto; border: 1px solid #ccc; border-radius: 8px;" src="images/VerifyCAKE2.png"></a>
<a href="images/VerifyCAKE3.png" target="_blank"><img style="max-width: 100%; height: auto; border: 1px solid #ccc; border-radius: 8px;" src="images/VerifyCAKE3.png"></a>
<a href="images/VerifyCAKE4.png" target="_blank"><img style="max-width: 100%; height: auto; border: 1px solid #ccc; border-radius: 8px;" src="images/VerifyCAKE4.png"></a>

---

## 🚀 Supported Device Matrix (Accurately Supports 142 Models)
Please find your router brand and model name below. The text inside the brackets `( )` is the **"Option Code"** you will need to input in the GitHub compilation menu later!

### 🟢 Kernel 3.4 Classic Devices (125 Options)
| **Brand (A-Z)** | **Supported Model: Product Name `(Option Code)`** |
| :--- | :--- |
| **5K** | 5K-W20 `(5K-W20)` |
| **A5** | A5-V11 16M `(A5-V11_16M)`, A5-V11 4M `(A5-V11_4M)`, A5-V11 8M `(A5-V11_8M)` |
| **ATEL** | ALR-U270 `(ALR-U270)` |
| **ASUS** | RP-AC56 `(RP-AC56)`, RT-AC1200 `(RT-AC1200)`, RT-AC1200GU `(RT-AC1200GU)`, RT-AC1200HP `(RT-AC1200HP)`, RT-AC51U `(RT-AC51U)`, RT-AC54U `(RT-AC54U)`, RT-N10 C1 `(RT-N10C1)`, RT-N11P `(RT-N11P)`, RT-N11P B1 `(RT-N11PB1)`, RT-N12+ `(RT-N12plus)`, RT-N13U B1 `(RT-N13UB1)`, RT-N14U `(RT-N14U)`, RT-N56U `(RT-N56U)`, RT-N56U GE2 `(RT-N56U-GE2)`, RT-N56U B1 `(RT-N56UB1)` |
| **BELKIN** | F9K1103 `(F9K1103)` |
| **D-Link** | DIR-300 B1 `(DIR-300B1)`, DIR-300 B7 `(DIR-300B7)`, DIR-320 B1 `(DIR-320B1)`, DIR-620 A1 `(DIR-620A1)`, DIR-620 D1 `(DIR-620D1)`, DIR-860L `(DIR-860L)`, DIR-882 `(DIR-882)` |
| **GL.iNet** | GL-MT300A `(GL-MT300A)`, GL-MT300N `(GL-MT300N)`, GL-MT300N V2 `(GL-MT300NV2)` |
| **HiWiFi** | HC5661A `(HC5661A)` |
| **Kroks** | KNDRT31R26 `(KNDRT31R26)`, KNDRT31R3 `(KNDRT31R3)` |
| **Linksys** | EA-8100 `(EA-8100)` |
| **MQMaker** | WiTi 256M `(MQ-WITI-256)`, WiTi 512M `(MQ-WITI-512)` |
| **Newifi** | Newifi D1 `(NEWIFI-D1)`, Newifi D2 `(NEWIFI-D2)`, Newifi Mini `(NEWIFI-MINI)`, Newifi Y1S `(NEWIFI-Y1S)` |
| **Nexx** | WT3020A `(WT3020A)`, WT3020H `(WT3020H)`, WT3020H 16M `(WT3020H16M)` |
| **Phicomm** | PSG1218 256M `(256PSG1218)`, PSG1218 `(PSG1218)` |
| **Samsung** | SWR1100 `(SWR1100)` |
| **Sercomm** | RT-S1010 `(RT-S1010)`, Smartbox SPI `(SMARTBOX_SPI)`, SMBX Pro NAND `(SMBXPRONAND)`, SMBX Turbo `(SMBXTURBO)` |
| **SNR** | SNR-MD1 `(SNR-MD1)`, SNR-ME1 `(SNR-ME1)`, SNR-W4N-M `(SNR-W4N-M)`, SNR-W4N-M USB `(SNR-W4N-M_USB)` |
| **Totolink** | A3004NS `(A3004NS)` |
| **TP-Link** | Archer C2 V1 `(TL_C2-V1)`, Archer C20 V1 `(TL_C20-V1)`, Archer C20 V1 16M `(TL_C20-V1_16M)`, Archer C20 V4 `(TL_C20-V4)`, Archer C20 V5 `(TL_C20-V5)`, Archer C5 V4 `(TL_C5-V4)`, Archer C50 V1 `(TL_C50-V1)`, Archer C50 V3 `(TL_C50-V3)`, Archer C50 V4 `(TL_C50-V4)`, EC220-G5 V2 `(TL_EC220_G5-V2)`, MR200 V1 `(TL_MR200-V1)`, MR3020 V3 `(TL_MR3020-V3)`, MR3420 V5 `(TL_MR3420-V5)`, WDR7300 V5 `(TL_WDR7300-V5)`, WR840N V4 `(TL_WR840N-V4)`, WR840N V4 USB `(TL_WR840N-V4_USB)`, WR840N V5 `(TL_WR840N-V5)`, WR840N V5 RU `(TL_WR840N-V5_RU)`, WR840N V6 `(TL_WR840N-V6)`, WR841N V13 `(TL_WR841N-V13)`, WR841N V13 USB `(TL_WR841N-V13_USB)`, WR841N V14 `(TL_WR841N-V14)`, WR841N V14 8M `(TL_WR841N-V14_8M)`, WR842N V5 `(TL_WR842N-V5)`, WR845N V3 `(TL_WR845N-V3)`, WR845N V4 `(TL_WR845N-V4)` |
| **Tuoshi** | TS7620N `(TS7620N)` |
| **Ubiquiti** | EdgeRouter X `(UBNT-ERX)` |
| **Unielec** | U7621-06 `(U7621-06)` |
| **Wall-AP** | Wall-AP `(WALL-AP)` |
| **Xiaomi / Redmi** | Mi Router 3 `(MI-3)`, Mi Router 3 SPI `(MI-3_SPI)`, Mi Router 3C `(MI-3C)`, Mi Router 3G `(MI-R3G)`, Mi Router 3G SPI `(MI-R3G_SPI)`, Mi Router 3G v2 `(MI-R3Gv2)`, Mi Router 3 Pro `(MI-R3PRO)`, Mi Router 3P SPI `(MI-R3P_SPI)`, Mi Router 4 `(MI-4)`, Mi Router 4A 100M `(MI-4A_100M)`, Mi Router 4C `(MI-4C)`, Mi Router Mini `(MI-MINI)`, Mi Router Nano `(MI-NANO)`, Xiaomi Router 2100 `(R2100)`, Redmi Router AC2100 `(RM-AC2100)` |
| **Youhua** | WR1200JS `(WR1200JS)` |
| **Youku** | YK-L1 `(YK-L1)`, YK-L1C `(YK-L1C)` |
| **ZBT** | WE1326 `(ZBT-WE1326)`, WE1626 `(ZBT-WE1626)`, WE826-T2 `(ZBT-WE826T2)`, WG3526 `(ZBT-WG3526)`, WG3526-32 `(ZBT-WG3526-32)`, WR8305RT `(ZBT-WR8305RT)` |
| **ZTE** | E8820S `(ZTE_E8820S)` |
| **ZyXEL / Keenetic** | KN-4G3 `(KN-4G3)`, KN-4G3B `(KN-4G3B)`, KN-EXTRA `(KN-EXTRA)`, KN-EXTRA2 `(KN-EXTRA2)`, KN-GIGA3 `(KN-GIGA3)`, KN-LITE `(KN-LITE)`, KN-LITE2 `(KN-LITE2)`, KN-LITE3 `(KN-LITE3)`, KN-LITE3B `(KN-LITE3B)`, KN-OMNI `(KN-OMNI)`, KN-OMNI2 `(KN-OMNI2)`, KN-START2 `(KN-START2)`, KN-ULTRA2 `(KN-ULTRA2)`, KN-VIVA `(KN-VIVA)` |

### 🔵 Kernel 4.4 Advanced Devices (17 Options)
| **Brand (A-Z)** | **Supported Model: Product Name `(Option Code)`** |
| :--- | :--- |
| **D-Link** | DIR-878 `(DIR-878)`, DIR-882 `(DIR-882)` |
| **JCG** | 836PRO `(JCG-836PRO)`, AC860M `(JCG-AC860M)`, Q20 `(JCG-Q20)`, Y2 `(JCG-Y2)` |
| **Motorola** | MR2600 `(MR2600)` |
| **Netgear** | BZV `(NETGEAR-BZV)` |
| **Newifi** | Newifi 3 `(NEWIFI3)` |
| **Phicomm** | K2P `(K2P)`, K2P Nano `(K2P-NANO)`, K2P USB `(K2P-USB)` |
| **Xiaomi / Redmi** | CR660x `(CR660x)`, Mi Router 3G `(MI-R3G)`, Mi Router 3 Pro `(MI-R3P)`, Redmi Router 2100 `(RM2100)` |
| **XiaoYu** | XY-C1 `(XY-C1)` |

---

## 🌐 Supports 14 Languages 
I believe the internet has no borders. The firmware build environment now supports 14 languages:
* **English_Only** (Default)
* **CN** - **Traditional Chinese (Taiwan)**, simply enter `CN` in the menu to get it.
* Also includes: Russian (RU), Czech (CZ), German (DE), French (FR), totaling 14 languages.

---

## 🍰 A PIECE OF CAKE! Super Easy Cloud Compilation (No Local Environment Needed, Done in 5 Mins!) 
It's truly a piece of cake! I have integrated all settings into GitHub Actions. You don't need to know how to code at all. Just click your mouse, and you'll get your customized firmware in minutes!

### **👉 6 Simple Steps:**

**Step 1: Register/Log in to GitHub and Light a "Star" 🌟 (In Memory of Dave Täht)**
 
Go to GitHub to register a free account and log in. Please visit the memorial repository and **click** the **"Star ⭐"** in the top right corner to pay tribute to Dave!
 
👉 [https://github.com/TW641/sch_cake](https://github.com/TW641/sch_cake)

**Step 2: Select Your Router Model and Fork the Project**
 
Based on the code you found in the table above, enter the corresponding link and **click** the **"Fork"** button in the top right corner:
 
🟢 **Classic Devices (Kernel 3.4)** 👉 [https://github.com/TW641/padavan-builder-workflow](https://github.com/TW641/padavan-builder-workflow)
 
🔵 **Advanced Devices (Kernel 4.4)** 👉 [https://github.com/TW641/padavan-4.4](https://github.com/TW641/padavan-4.4)

**Step 3: Enable Actions**
 
Go to your Forked project, **click** the **"Actions"** tab at the top, and **click** the green button **"I understand my workflows, go ahead and enable them"**.

**Step 4: Select the Correct Workflow**
 
On the left side of the Actions page, **click** the corresponding workflow name based on your model:
 
🟢 **3.4 Models:** `Build firmware (Ultimate Fix - Early Size Check)`
 
🔵 **4.4 Models:** `Custom-Router-Build-Final-Fix`

**Step 5: One-Click Compile & Customize (IP/Password)**
 
**Click** the **"Run workflow"** dropdown menu on the right.
 
**[Most Important Step]** Enter your **"Option Code"** in the `Target Model` field (must perfectly match the one in the brackets from the table); for the language menu, enter `English_Only` (or `CN` if you prefer **Traditional Chinese**).
 
**Customization:** You can directly modify the default IP and password in the JSON field. If untouched, default values will be used. Finally, **click** the green **"Run workflow"** button!

**Step 6: Download & Flash**
 
Wait for about 10-15 minutes. Once the workflow shows a green checkmark ✅, **click** into the run, scroll to the bottom, and find **"Artifacts"** to download the ZIP file. The `.bin` file inside is your exclusive firmware!
