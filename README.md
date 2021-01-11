# NanoPi-R4S 的 OpenWrt 固件  
![R4S-1G-OpenWrt-Lean](https://github.com/RikudouPatrickstar/R4S-OpenWrt-Lean/workflows/R4S-1G-OpenWrt-Lean/badge.svg)  
![R4S-4G-OpenWrt-Lean](https://github.com/RikudouPatrickstar/R4S-OpenWrt-Lean/workflows/R4S-4G-OpenWrt-Lean/badge.svg)  

## 一、固件特性  
1. 基于 [coolsnowwolf/lede](https://github.com/coolsnowwolf/lede) 定制  
2. 设置主机名为 `NanoPi-R4S`  
3. 默认 LAN IP： `192.168.1.1`  
4. 默认用户、密码： `root` `无`  
5. 插件仅包含： `OpenClash` `SSRPlus` `Samba4网络共享`  
6. 重命名 `ShadowSocksR Plus+` 为 `SSRPlus`，并微调其设置首页内容  
7. 主题仅包含 `luci-theme-argon` 且删除主题底部文字  
8. 精简 LuCI 界面，移除 `软件包` `挂载点` `备份/升级`  
9. 提供 `EXT4FS` 和 `SQUASHFS` 两种类型固件  

## 二、感谢  
   感谢所有提供了上游项目代码和给予了帮助的大佬们
