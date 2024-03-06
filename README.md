 OpenWRT软件包与固件自动云编译

 来自https://github.com/chenmozhijin/OpenWrt-K

## 固件介绍

已内置以下软件包：

LuCI插件：  
  [luci-app-adguardhome](https://github.com/chenmozhijin/luci-app-adguardhome) :AdGuardHome广告屏蔽工具的luci设置界面  
  luci-app-ddns：动态 DNS  
  luci-app-firewall：防火墙  
  [luci-app-netdata](https://github.com/netdata/netdata) 实时监控  
  luci-app-nlbwmon：网络带宽监视器  
  luci-app-opkg：软件包  
  [luci-app-openclash](https://github.com/vernesong/OpenClash):可运行在 OpenWrt 上的 Clash 客户端  
  [luci-app-passwall](https://github.com/xiaorouji/openwrt-passwall)：passwall  
  [luci-app-socat](https://github.com/chenmozhijin/luci-app-socat)：Socat网络工具  
  luci-app-ttyd：ttyd 终端  
  luci-app-vlmcsd：KMS 服务器  
  [luci-app-parentcontrol](https://github.com/sirpdboy/luci-app-parentcontrol)  家长控制
  
  luci-app-zerotier  内网穿透
  

  默认管理IP：192.168.1.252

  若想安装luci-app-mosdns,登录openwrt后台，运行以下脚本

  ```shell
  sh -c "$(curl -ksS https://raw.githubusercontent.com/sbwml/luci-app-mosdns/v5/install.sh)"
  ```
