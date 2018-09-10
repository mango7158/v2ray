# v2ray
最好用的 V2Ray 一键安装脚本 &amp; 管理脚本<br>
https://raw.githubusercontent.com/mango7158/v2ray/master/install.sh<br>
https://raw.githubusercontent.com/mango7158/v2ray/master/v2ary.sh<br>

# 安装 

 <br>git clone https://github.com/mango7158/v2ray <br>
cd v2ray <br>
chmod +x install.sh <br>
./install.sh local <br>


# 快速管理

 <br>v2ray info 查看 V2Ray 配置信息 <br>
v2ray config 修改 V2Ray 配置 <br>
v2ray link 生成 V2Ray 配置文件链接 <br>
v2ray infolink 生成 V2Ray 配置信息链接 <br>
v2ray qr 生成 V2Ray 配置二维码链接 <br>
v2ray ss 修改 Shadowsocks 配置 <br>
v2ray ssinfo 查看 Shadowsocks 配置信息 <br>
v2ray ssqr 生成 Shadowsocks 配置二维码链接 <br>
v2ray status 查看 V2Ray 运行状态 <br>
v2ray start 启动 V2Ray <br>
v2ray stop 停止 V2Ray <br>
v2ray restart 重启 V2Ray <br>
v2ray log 查看 V2Ray 运行日志 <br>
v2ray update 更新 V2Ray <br>
v2ray update.sh 更新 V2Ray 管理脚本 <br>
v2ray uninstall 卸载 V2Ray <br>



# 配置文件路径

 <br>V2Ray 配置文件路径：/etc/v2ray/config.json <br>
Caddy 配置文件路径：/etc/caddy/Caddyfile <br>
脚本配置文件路径: /etc/v2ray/233blog_v2ray_backup.conf <br>



# 功能特点

 <br>支持 V2Ray 多数传输协议 <br>
支持 WebSocket + TLS / HTTP/2 <br>
支持 动态端口 (WebSocket + TLS，Socks5， HTTP/2 除外) <br>
支持 屏蔽广告 <br>
支持 配置 Shadowsocks <br>
支持 下载客户端配置文件 (不用 Xshell 也可以下载) <br>
客户端配置文件同时支持 SOCKS 和 HTTP <br>
支持 生成 V2Ray 配置二维码链接 (仅适用部分客户端) <br>
支持 生成 V2Ray 配置信息链接 <br>
支持 生成 Shadowsocks 配置二维码链接 <br>
支持修改 V2Ray 传输协议 <br>
支持修改 V2Ray 端口 <br>
支持修改 动态端口 <br>
支持修改 用户ID <br>
支持修改 TLS 域名 <br>
支持修改 Shadowsocks 端口 <br>
支持修改 Shadowsocks 密码 <br>
支持修改 Shadowsocks 加密协议 <br>
自动启用 BBR 优化 (如果内核支持) <br>
集成可选安装 BBR (by teddysun.com) <br>
集成可选安装 锐速 (by moeclub.org) <br>
一键 查看运行状态 / 查看配置信息 / 启动 / 停止 / 重启 / 更新 / 卸载 / 等等… <br>
人性化向导 & 纯净安装 & 卸载彻底 <br>
