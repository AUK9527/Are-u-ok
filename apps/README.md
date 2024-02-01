#### iStore扩展软件包

* 本页面所下载的软件包插件适用于aarch64_cortex-a53平台的机器(EasePi ARS2、小米AX3600、AX9000、红米AX6等)。

* 也兼容aarch64_generic平台，例如R2S、R4S、R5S、R68S等。

* aarch64_generic平台如果要兼容这些软件包，请使用iStoreOS固件，或者固件做了适配iStore。

* 适用于KoolCenter iStoreOS 22.03.X的软件包

|插件名|功能|下载|编译日期|
| :----: | :----: | :----: | :----: |
| PassWall | 科学工具 | [PassWall_4.73-3](https://github.com/AUK9527/Are-u-ok/raw/main/apps/all/PassWall_4.73-3_aarch64_a53_all_sdk_22.03.6.run) |2024-02-01|
| PassWall2 | 科学工具 | [PassWall2_1.25-4](https://github.com/AUK9527/Are-u-ok/raw/main/apps/all/PassWall2_1.25-4_aarch64_a53_all_sdk_22.03.6.run) |2024-02-01|
| SSR-Plus | 科学工具 | [SSR-Plus_188-3](https://github.com/AUK9527/Are-u-ok/raw/main/apps/all/SSR-Plus_188-3_aarch64_a53_all_sdk_22.03.6.run) |2024-01-30|
| OpenClash | 科学工具 | [OpenClash_0.45.164](https://github.com/AUK9527/Are-u-ok/raw/main/apps/all/OpenClash_0.45.164+aarch_64_core.run) |2024-01-31|
| MosDNS | DNS 转发/分流器 | [mosdns_5.3.1-1](https://github.com/AUK9527/Are-u-ok/raw/main/apps/all/mosdns_5.3.1-1_aarch64_a53_all.run) |2023-11-06|
| UnblockNeteaseMusic | 解锁网易云灰色歌曲 | [下载](https://github.com/AUK9527/Are-u-ok/raw/main/apps/all/unblockneteasemusic.run) |2024-01-05|

* passwall、passwall2、ssr-plus均使用 22.03.X sdk编译，依旧使用libopenssl1.1，无需libopenssl3依赖，安装后在服务里。
* 安装后passwall日志里提示一些依赖未安装属于正常现象，不影响使用，这些依赖固件里应该都自带的。可以到【系统】-【软件包】-【已安装】里确认。
* 如果你在安装此包前通过第三方软件源安装，可能导致意外的错误，例如本不需要libopenssl3，变得需要，此情况可能需要重置你的路由器。
* 自带clash核心的openclash，版本为0.45.164。如果安装完出现路由器断网，重启一次路由器。
* **注意，上述软件包安装，部分依赖依然要通过opkg软件源在线安装。如果安装失败，检查路由器自身的网络情况，特别是旁路由模式下最容易出现网络问题。**
**再三注意需要路由器自身联网正常**

* 一系列软件包：

|插件名|功能|下载|
| :----: | :----: | :----: |
| ByPass | ByPass 科学工具 | [下载](https://github.com/AUK9527/Are-u-ok/raw/main/apps/all/ByPass_a53.run) |
| VSSR | HelloWorld 科学工具 | [下载](https://github.com/AUK9527/Are-u-ok/raw/main/apps/all/VSSR_a53.run) |
| AdGuardHome | AdGuardHome 去广告(带核心) | [下载](https://github.com/AUK9527/Are-u-ok/raw/main/apps/all/AdGuardHome_a53.run) |
| ikoolproxy | koolproxy去广告(不适合高于5.4内核的固件) | [下载](https://github.com/AUK9527/Are-u-ok/raw/main/apps/all/ikoolproxy_a53.run) |
| Adblock | Adblock 去广告 | [下载](https://github.com/AUK9527/Are-u-ok/raw/main/apps/all/adblock.run) |
| Adbyby | 广告屏蔽大师 Plus+ | [下载](https://github.com/AUK9527/Are-u-ok/raw/main/apps/all/adbyby_a53.run) |
| OpenVPN | OpenVPN客户端 | [下载](https://github.com/AUK9527/Are-u-ok/raw/main/apps/all/OpenVPN_20211018.run) |
| OpenVPN-Server | OpenVPN服务端 | [下载](https://github.com/AUK9527/Are-u-ok/raw/main/apps/all/OpenVPN-Server_a53.run) |
| JD-dailybonus | 某东签到(扫码早就gg，手动填cookie) | [下载](https://github.com/AUK9527/Are-u-ok/raw/main/apps/all/JD-dailybonus_20211105.run) |
| KMS | KMS服务器 | [下载](https://github.com/AUK9527/Are-u-ok/raw/main/apps/all/KMS_a53.run) |
| NPS | Nps内网穿透 | [下载](https://github.com/AUK9527/Are-u-ok/raw/main/apps/all/NPS_a53.run) |

#### 如何安装，下载后，iStore手动安装，选择文件安装即可。

![png](https://cdn.jsdelivr.net/gh/AUK9527/Are-u-ok@master/apps/install.png)

