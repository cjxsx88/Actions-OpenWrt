# Actions-OpenWrt

Build OpenWrt using GitHub Actions

运用GitHub云编译OpenWrt固件

感谢[@P3TERX](https://github.com/P3TERX)大佬提供的云编译脚本
P3TERX大佬脚本原始地址→→→[请点我跳转](https://github.com/P3TERX/Actions-OpenWrt)

大佬的中文教程
↓↓↓↓↓↓↓↓

[Read the details in P3TERX blog (in Chinese) | 中文教程](https://p3terx.com/archives/build-openwrt-with-github-actions.html)


---------------------------------------------------------我是分割线-------------------------------------------------------------

本项目编译后生成X86-64固件

以下为文件目录

config.buildinfo

feeds.buildinfo

openwrt-x86-64-generic.manifest

openwrt-x86-64-generic-kernel.bin

openwrt-x86-64-generic-squashfs-combined-efi.img

openwrt-x86-64-generic-squashfs-combined-efi.vmdk

openwrt-x86-64-generic-squashfs-rootfs.img

sha256sums

version.buildinfo

本固件为自用精简版，简化了大部分对我来说无用的功能，仅保留以下功能：

PassWall，广告屏蔽大师Plus+，解锁网易云灰色歌曲，SmartDNS，网络唤醒，KMS服务器，Turbo ACC 网络加速，实时监控。

需要其他功能可参考[@P3TERX](https://github.com/P3TERX)大佬的中文教程进行修改实现自己需要编译的功能。

再次感谢为openwrt无偿付出的所有开源作者，对于刚入手编译的我来说只能尽自己的绵薄之力，将各位的大神的劳动成果借此传播给大家，为大家提供更佳的体验。
如果发现存在bug，希望大家能够相互帮助讨论，积极反馈给本人或者源作者本人，促进和谐稳定发展，祝openwrt项目越来越好！

参考来源：

[@P3TERX](https://github.com/P3TERX/Actions-OpenWrt)'s Actions-OpenWrt

[@Lean](https://github.com/coolsnowwolf/lede)'s OpenWrt

[@lienol](https://github.com/Lienol/openwrt-package)'s OpenWrt-Package

[@kenzok8](https://github.com/kenzok8/openwrt-packages)'s OpenWrt-Package

[@pymumu](https://github.com/pymumu/smartdns)'s SmartDNS

Thkans for all~~~~
