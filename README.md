
<h1 align="center">
  <br>
 <img src="https://github.com/ethereum-proxy/Minerproxy/blob/main/logo.png" width="500"/>
</h1>

<h4 align="center">letsec 加密隧道，Go语言原生开发，letminer专用加密客户端。
<br />私有加密协议，安全性更高、更稳定，防嗅探、防扫描，矿厂必备。
<h4 align="center"><a style="color:red" href="https://github.com/ethereum-proxy/Minerproxy">配合 MinerProxy 矿机代理使用 >></a></h4>

# · letsec使用方式
```bash
【矿机】 ---SSL/TCP连接---> 【letsec本地端口】 ---> 【Minerproxy本地端口】 ---SSL/TCP连接--->【矿池】
```

# · Liunx在线安装
 · 推荐系统：Ubuntu 16+ / Debian 8+ / CentOS 7+，使用 root 用户输入下面命令安装或卸载<br />
 · 服务器可以直连Github
```bash  
bash <(curl -s -L https://github.com/ethereum-proxy/letsec/main/install.sh)
```
 · 服务器无法访问Github
```bash
bash <(curl -s -L https://cdn.statically.io/gh/ethereum-proxy/letsec/main/install.sh)
```

# · Linux离线安装
```bash
1、直接下载zip压缩包，
2、解压，运行安装脚本 ：bash install.sh       
```

# · Windows安装
```bash
1、直接下载zip压缩包，
2、解压下载的压缩包，双击 windows启动.bat 即可,
   或直接双击 letsec_windows.exe。
```

# ·  重要提示
```bash
1、Linux系统第一次安装完成后请重启服务器，连接限制修改方可生效！
2、安装完成后，请立即修改默认密码！
3、letsec支持矿机使用SSL/TCP两种连接方式，
   letsec已内置SSL证书，如需更换，请将证书文件命名为 server.key 与 server.pem ,并放置于程序安装目录下！
```

# ·  版本日志
```bash
2022/07/01 v1.0.0  发布第一个版本；letminer（版本>=1.0.0）专用本地加密客户端。
```
  
# · 联系我们
```bash
1、Telegram技术交流群：https://t.me/minerproxy
2、欢迎建议、使用反馈、定制需求，电报群直接私聊群主
```    


