# 自用 ImmortalWrt X86_64  
* 基于 ImmortalWrt 最新源码每日自动编译 
  
## 修改设置  
* 分区大小默认 1600M
* 开启 IPv6 功能
* 添加 luci

## 包含插件  
* DDNSTO 远程控制
* Wechatpush 微信推送
* OpenClash（包含dev版本的三种内核与主程序）
* KMS 服务器
* Alist
* DDNS-GO
* frp 服务器
* UPnP
* WOL-PLUS 局域网唤醒
* ttdy 终端服务
* OpenVPN 服务器

## 在线更新 
固件可以自动或手动检测 Github Release 中的最新版本并下载进行更新  
进入 luci 界面 > 在线更新，可选择手动更新或者定时检测最新版本并自动更新  
亦可在 SSH 中输入 openwrt 命令进行更新  

  # 感谢
- [immortalwrt/immortalwrt](https://github.com/immortalwrt/immortalwrt)
- [281677160/build-actions](https://github.com/281677160/build-actions)
