# OpenWrt-K

[![GitHub Repo stars](https://img.shields.io/github/stars/chenmozhijin/OpenWrt-K)](https://github.com/chenmozhijin/OpenWrt-K/stargazers)
[![GitHub forks](https://img.shields.io/github/forks/chenmozhijin/OpenWrt-K)](https://github.com/chenmozhijin/OpenWrt-K/forks?include=active%2Carchived%2Cinactive%2Cnetwork&page=1&period=2y&sort_by=stargazer_counts)
[![GitHub commit activity (branch)](https://img.shields.io/github/commit-activity/t/chenmozhijin/OpenWrt-K)](https://github.com/chenmozhijin/OpenWrt-K/commits)
[![GitHub last commit (by committer)](https://img.shields.io/github/last-commit/chenmozhijin/OpenWrt-K)](https://github.com/chenmozhijin/OpenWrt-K/commits)
[![Workflow Status](https://github.com/chenmozhijin/OpenWrt-K/actions/workflows/build-openwrt.yml/badge.svg)](https://github.com/chenmozhijin/OpenWrt-K/actions)
> OpenWRT软件包与固件自动云编译

## 目录

[README](https://github.com/chenmozhijin/OpenWrt-K#openwrt-k):

1. [固件介绍](https://github.com/chenmozhijin/OpenWrt-K#%E5%9B%BA%E4%BB%B6%E4%BB%8B%E7%BB%8D)
2. [更新日志](https://github.com/chenmozhijin/OpenWrt-K#%E6%9B%B4%E6%96%B0%E6%97%A5%E5%BF%97)  
  
[Wiki页面](https://github.com/chenmozhijin/OpenWrt-K/wiki):

1. [固件使用方法](https://github.com/chenmozhijin/OpenWrt-K/wiki/%E5%9B%BA%E4%BB%B6%E4%BD%BF%E7%94%A8%E6%96%B9%E6%B3%95)
2. [仓库基本介绍](https://github.com/chenmozhijin/OpenWrt-K/wiki/%E4%BB%93%E5%BA%93%E5%9F%BA%E6%9C%AC%E4%BB%8B%E7%BB%8D)
3. [定制编译OpenWrt固件](https://github.com/chenmozhijin/OpenWrt-K/wiki/%E5%AE%9A%E5%88%B6%E7%BC%96%E8%AF%91-OpenWrt-%E5%9B%BA%E4%BB%B6)
4. [常见问题](https://github.com/chenmozhijin/OpenWrt-K/wiki/%E5%B8%B8%E8%A7%81%E9%97%AE%E9%A2%98)

## 固件介绍
基于OpenWrt官方源码编译
已内置以下软件包：

LuCI插件：  
  [luci-app-adguardhome](https://github.com/chenmozhijin/luci-app-adguardhome) :AdGuardHome广告屏蔽工具的luci设置界面  

  luci-app-aria2：aria2下载器  

  luci-app-ddns：动态 DNS  

  luci-app-fileassistant：文件助手  
  luci-app-firewall：防火墙  
  luci-app-netdata：[Netdata](https://github.com/netdata/netdata) 实时监控  
  [luci-app-netspeedtest](https://github.com/sirpdboy/netspeedtest)：网速测试  
  luci-app-nlbwmon：网络带宽监视器  
  luci-app-opkg：软件包  
  [luci-app-openclash](https://github.com/vernesong/OpenClash):可运行在 OpenWrt 上的 Clash 客户端  
  [luci-app-passwall](https://github.com/xiaorouji/openwrt-passwall)：passwall  
  [luci-app-socat](https://github.com/chenmozhijin/luci-app-socat)：Socat网络工具  
  luci-app-ttyd：ttyd 终端  
  [luci-app-turboacc](https://github.com/chenmozhijin/turboacc)：Turbo ACC 网络加速  

  luci-app-vlmcsd：KMS 服务器  

  默认管理IP：192.168.1.252
