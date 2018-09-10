# v2ray
最好用的 V2Ray 一键安装脚本 &amp; 管理脚本


git clone https://github.com/mango7158/v2ray
cd v2ray
chmod +x install.sh
./install.sh local


快速管理
v2ray info 查看 V2Ray 配置信息
v2ray config 修改 V2Ray 配置
v2ray link 生成 V2Ray 配置文件链接
v2ray infolink 生成 V2Ray 配置信息链接
v2ray qr 生成 V2Ray 配置二维码链接
v2ray ss 修改 Shadowsocks 配置
v2ray ssinfo 查看 Shadowsocks 配置信息
v2ray ssqr 生成 Shadowsocks 配置二维码链接
v2ray status 查看 V2Ray 运行状态
v2ray start 启动 V2Ray
v2ray stop 停止 V2Ray
v2ray restart 重启 V2Ray
v2ray log 查看 V2Ray 运行日志
v2ray update 更新 V2Ray
v2ray update.sh 更新 V2Ray 管理脚本
v2ray uninstall 卸载 V2Ray



配置文件路径
V2Ray 配置文件路径：/etc/v2ray/config.json
Caddy 配置文件路径：/etc/caddy/Caddyfile
脚本配置文件路径: /etc/v2ray/233blog_v2ray_backup.conf



功能特点
支持 V2Ray 多数传输协议
支持 WebSocket + TLS / HTTP/2
支持 动态端口 (WebSocket + TLS，Socks5， HTTP/2 除外)
支持 屏蔽广告
支持 配置 Shadowsocks
支持 下载客户端配置文件 (不用 Xshell 也可以下载)
客户端配置文件同时支持 SOCKS 和 HTTP
支持 生成 V2Ray 配置二维码链接 (仅适用部分客户端)
支持 生成 V2Ray 配置信息链接
支持 生成 Shadowsocks 配置二维码链接
支持修改 V2Ray 传输协议
支持修改 V2Ray 端口
支持修改 动态端口
支持修改 用户ID
支持修改 TLS 域名
支持修改 Shadowsocks 端口
支持修改 Shadowsocks 密码
支持修改 Shadowsocks 加密协议
自动启用 BBR 优化 (如果内核支持)
集成可选安装 BBR (by teddysun.com)
集成可选安装 锐速 (by moeclub.org)
一键 查看运行状态 / 查看配置信息 / 启动 / 停止 / 重启 / 更新 / 卸载 / 等等…
人性化向导 & 纯净安装 & 卸载彻底
