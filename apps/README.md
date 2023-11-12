#### iStore扩展插件包

* 本页面所下载的离线包插件适用于aarch64_cortex-a53平台的机器(EasePi ARS2、小米AX3600、AX9000、红米AX6等)。

* 也兼容aarch64_generic平台，例如R2S、R4S、R5S、R68S等。

* aarch64_generic平台如果要兼容这些离线包，请使用iStoreOS固件，或者固件做了适配iStore。

* 一些新版离线包测试：

|插件名|功能|下载|
| :----: | :----: | :----: |
| PassWall | PassWall 科学工具(更新) | [下载新版](./all/PassWall_a53_update.run?raw=true) |
| SSR-Plus | ssr-plus 科学工具(更新) | [下载新版](./all/SSR-Plus_a53_update.run?raw=true) |
| OpenClash | OpenClash 科学工具(更新) | [下载新版](./all/OpenClash_a53_update.run?raw=true) |

passwall和ssr-p安装最后可能会出现一堆ss相关的报错，不要理会，这2个插件位置会出现在VPN分类里。

* 适用于KoolCenter iStoreOS 22.03.5的离线包

|插件名|功能|下载|编译日期|
| :----: | :----: | :----: | :----: |
| PassWall | PassWall 科学工具(更新) | [passwall4.71-2](./all/PassWall4.71-2_a53_all_sdk_22.03.5.run?raw=true) |2023-11-08|
| PassWall | PassWall 科学工具(更新) | [ssr-plus188](./all/SSR-Plus_188_a53_all_sdk22.03.5.run?raw=true) |2023-11-13|

使用22.03.5sdk编译，依旧使用libopenssl1.1，无需libopenssl3依赖的4.71-2最新版passwall，安装后在服务里。
安装后passwall日志里提示一些依赖未安装属于正常现象，不影响使用，这些依赖固件里应该都自带的。可以到【系统】-【软件包】-【已安装】里确认。
如果你在安装此包前通过第三方软件源安装，可能导致意外的错误，例如本不需要libopenssl3，变得需要，此情况可能需要重置你的路由器。

* 一系列离线包：

|插件名|功能|下载|
| :----: | :----: | :----: |
| PassWall | PassWall 科学工具(全组件版，适合大闪存机器，体积60M左右) | [下载](./all/PassWall_a53_all.run?raw=true) |
| PassWall2 | PassWall2 科学工具(全组件版，适合大闪存机器，体积45M左右) | [下载](./all/PassWall2_a53_all.run?raw=true) |
| PassWall | PassWall 科学工具 | [下载](./all/PassWall_a53.run?raw=true) |
| SSR-Plus | ssr-plus 科学工具 | [下载](./all/SSR-Plus_a53.run?raw=true) |
| OpenClash | OpenClash 科学工具(自带核心) | [下载](./all/OpenClash+Kernel_a53.run?raw=true) |
| ByPass | ByPass 科学工具 | [下载](./all/ByPass_a53.run?raw=true) |
| VSSR | HelloWorld 科学工具 | [下载](./all/VSSR_a53.run?raw=true) |
| AdGuardHome | AdGuardHome 去广告(带核心) | [下载](./all/AdGuardHome_a53.run?raw=true) |
| ikoolproxy | koolproxy去广告(不适合高于5.4内核的固件) | [下载](./all/ikoolproxy_a53.run?raw=true) |
| Adblock | Adblock 去广告 | [下载](./all/adblock.run?raw=true) |
| Adbyby | 广告屏蔽大师 Plus+ | [下载](./all/adbyby_a53.run?raw=true) |
| UnblockNeteaseMusic | 解锁网易云灰色歌曲 | [下载](./all/UnblockNeteaseMusic_a53.run?raw=true) |
| OpenVPN | OpenVPN客户端 | [下载](./all/OpenVPN_20211018.run?raw=true) |
| OpenVPN-Server | OpenVPN服务端 | [下载](./all/OpenVPN-Server_a53.run?raw=true) |
| JD-dailybonus | 某东签到(扫码早就gg，手动填cookie) | [下载](./all/JD-dailybonus_20211105.run?raw=true) |
| KMS | KMS服务器 | [下载](./all/KMS_a53.run?raw=true) |
| NPS | Nps内网穿透 | [下载](./all/NPS_a53.run?raw=true) |
| MosDNS | DNS 转发/分流器 | [下载](./all/MosDNS-New_a53.run?raw=true) |

#### 如何安装，下载后，iStore手动安装，选择文件安装即可。

![png](https://cdn.jsdelivr.net/gh/AUK9527/Are-u-ok@master/apps/install.png)

