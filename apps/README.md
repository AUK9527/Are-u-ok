#### iStore扩展插件包

* 本页面所下载的离线包插件仅适用于aarch64_cortex-a53平台的机器。

* 例如：EasePi ARS2、小米AX3600、AX9000、红米AX6等。

* 也兼容aarch64_generic平台，例如R2s、R4s、R5s、R68s等。

* aarch64_generic平台如果要兼容这些离线包，请使用iStoreOS固件，或者固件做了适配iStore。

|插件名|功能|下载|
| :----: | :----: | :----: |
| AdGuardHome | AdGuardHome 去广告 | [下载](https://raw.githubusercontent.com/AUK9527/Are-u-ok/main/apps/all/AdGuardHome_20211014.run) |
| ikoolproxy | koolproxy去广告(不适合高于5.4内核的固件) | [下载](https://raw.githubusercontent.com/AUK9527/Are-u-ok/main/apps/all/ikoolproxy_a53.run) |
| Adblock | Adblock 去广告 | [下载](https://raw.githubusercontent.com/AUK9527/Are-u-ok/main/apps/all/adblock.run) |
| Adbyby | 广告屏蔽大师 Plus+ | [下载](https://raw.githubusercontent.com/AUK9527/Are-u-ok/main/apps/all/adbyby_a53.run) |
| OpenClash | OpenClash 科学工具 | [下载](https://raw.githubusercontent.com/AUK9527/Are-u-ok/main/apps/all/OpenClash_a53.run) |
| PassWall | PassWall 科学工具 | [下载](https://raw.githubusercontent.com/AUK9527/Are-u-ok/main/apps/all/PassWall_a53.run) |
| ByPass | ByPass 科学工具 | [下载](https://raw.githubusercontent.com/AUK9527/Are-u-ok/main/apps/all/ByPass_a53.run) |
| VSSR | HelloWorld 科学工具 | [下载](https://raw.githubusercontent.com/AUK9527/Are-u-ok/main/apps/all/VSSR_a53.run) |
| SSR-Plus | ssr-plus 科学工具 | [下载](https://raw.githubusercontent.com/AUK9527/Are-u-ok/main/apps/all/SSR-Plus_a53.run) |
| UnblockNeteaseMusic | 解锁网易云灰色歌曲 | [下载](https://raw.githubusercontent.com/AUK9527/Are-u-ok/main/apps/all/UnblockNeteaseMusic_a53.run) |
| OpenVPN | OpenVPN客户端 | [下载](https://raw.githubusercontent.com/AUK9527/Are-u-ok/main/apps/all/OpenVPN_20211018.run) |
| OpenVPN-Server | OpenVPN服务端 | [下载](https://raw.githubusercontent.com/AUK9527/Are-u-ok/main/apps/all/OpenVPN-Server_a53.run) |
| JD-dailybonus | 某东签到(扫码早就gg，手动填cookie) | [下载](https://raw.githubusercontent.com/AUK9527/Are-u-ok/main/apps/all/JD-dailybonus_20211105.run) |
| KMS | KMS服务器 | [下载](https://raw.githubusercontent.com/AUK9527/Are-u-ok/main/apps/all/KMS_a53.run) |
| MosDNS | DNS 转发/分流器 | [下载](https://raw.githubusercontent.com/AUK9527/Are-u-ok/main/apps/all/MosDNS_a53.run) |
| NPS | Nps内网穿透 | [下载](https://raw.githubusercontent.com/AUK9527/Are-u-ok/main/apps/all/NPS_a53.run) |




* aarch64_generic平台安装PassWall/ByPass/VSSR/SSR-Plus这四个插件如果碰到了下列错误，请使用下面的离线包：
```
Error loading shared library libmbedcrypto.so.3: No such file or directory (needed by /usr/bin/ss-local)
Error relocating /usr/bin/ss-local: mbedtls_cipher_update: symbol not found
Error relocating /usr/bin/ss-local: mbedtls_cipher_free: symbol not found
Error relocating /usr/bin/ss-local: mbedtls_cipher_auth_decrypt: symbol not found
Error relocating /usr/bin/ss-local: mbedtls_cipher_setkey: symbol not found
Error relocating /usr/bin/ss-local: mbedtls_md_finish: symbol not found
Error relocating /usr/bin/ss-local: mbedtls_md_hmac: symbol not found
Error relocating /usr/bin/ss-local: mbedtls_md_hmac_starts: symbol not found
Error relocating /usr/bin/ss-local: mbedtls_cipher_reset: symbol not found
Error relocating /usr/bin/ss-local: mbedtls_md_hmac_update: symbol not found
Error relocating /usr/bin/ss-local: mbedtls_md5_ret: symbol not found
Error relocating /usr/bin/ss-local: mbedtls_md_starts: symbol not found
Error relocating /usr/bin/ss-local: mbedtls_md_update: symbol not found
Error relocating /usr/bin/ss-local: mbedtls_cipher_set_iv: symbol not found
Error relocating /usr/bin/ss-local: mbedtls_md_get_size: symbol not found
Error relocating /usr/bin/ss-local: mbedtls_cipher_init: symbol not found
Error relocating /usr/bin/ss-local: mbedtls_md_setup: symbol not found
Error relocating /usr/bin/ss-local: mbedtls_cipher_setup: symbol not found
Error relocating /usr/bin/ss-local: mbedtls_md_free: symbol not found
Error relocating /usr/bin/ss-local: mbedtls_cipher_info_from_string: symbol not found
Error relocating /usr/bin/ss-local: mbedtls_md_hmac_finish: symbol not found
Error relocating /usr/bin/ss-local: mbedtls_cipher_auth_encrypt: symbol not found
Error relocating /usr/bin/ss-local: mbedtls_md_info_from_string: symbol not found
Error relocating /usr/bin/ss-local: mbedtls_md_init: symbol not found
ln: libmbedcrypto.so.3: File exists
```
|插件名|功能|下载|
| :----: | :----: | :----: |
| PassWall | PassWall 科学工具 | [下载](https://raw.githubusercontent.com/AUK9527/Are-u-ok/main/apps/all/PassWall_generic.run) |
| ByPass | ByPass 科学工具 | [下载](https://raw.githubusercontent.com/AUK9527/Are-u-ok/main/apps/all/ByPass_generic.run) |
| VSSR | HelloWorld 科学工具 | [下载](https://raw.githubusercontent.com/AUK9527/Are-u-ok/main/apps/all/VSSR_generic.run) |
| SSR-Plus | ssr-plus 科学工具 | [下载](https://raw.githubusercontent.com/AUK9527/Are-u-ok/main/apps/all/SSR-Plus_generic.run) |


#### 如何安装，下载后，iStore手动安装，选择文件安装即可。

![png](https://cdn.jsdelivr.net/gh/AUK9527/Are-u-ok@master/apps/install.png)













