# 自用 ImmortalWrt X86_64  
* 基于 [ImmortalWrt](https://github.com/immortalwrt/immortalwrt) SNAPSHOT 最新源码每日自动编译
* 自己不用，所以不保证什么
  
## 修改设置  
* 分区大小默认 1600M
* 开启 IPv6 功能
* 添加 luci
* 替换默认主题为 [Argon](https://github.com/jerrykuku/luci-theme-argon) 主题
 
## 包含插件  
* [DDNSTO 远程控制](https://www.ddnsto.com/)
* [Wechatpush 微信推送](https://github.com/tty228/luci-app-wechatpush)
* [OpenClash](https://github.com/vernesong/OpenClash)（包含dev版本的三种内核与主程序）
* [KMS 服务器](https://github.com/mchome/luci-app-vlmcsd)
* [Alist](https://github.com/sbwml/luci-app-alist)
* [DDNS-GO](https://github.com/sirpdboy/luci-app-ddns-go)
* [frp 服务器](https://github.com/lwz322/luci-app-frps)
* [WOL-PLUS 局域网唤醒](https://github.com/animegasan/luci-app-wolplus)
* [OpenVPN 服务器](https://github.com/DavBfr/luci-app-openvpn-server)
* ttdy 终端服务
* UPnP

## 在线更新 
固件可以自动或手动检测 Github Release 中的最新版本并下载进行更新  
进入 luci 界面 > 在线更新，可选择手动更新或者定时检测最新版本并自动更新  
亦可在 SSH 中输入 openwrt 命令进行更新  

  # 感谢
- [immortalwrt/immortalwrt](https://github.com/immortalwrt/immortalwrt)
- [281677160/build-actions](https://github.com/281677160/build-actions)
