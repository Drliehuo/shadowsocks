# shadowsocks
在centos系统服务中，快速部署shadowsocks，让客户端建立连接，shadowsocks加密方式默认的缺省值为：aes-256-gcm。

# 开始安装

```
wget https://i.inetpub.cn/linux/shadowsocks-libev.sh && chmod +x shadowsocks-libev.sh && ./shadowsocks-libev.sh 2>&1 | tee shadowsocks-libev.log
```

# 开始卸载

```
./shadowsocks-libev.sh uninstall
```

# 启动状态

```
/etc/init.d/shadowsocks status
```

# 使用命令

```
启动 /etc/init.d/shadowsocks start

停止 /etc/init.d/shadowsocks stop

重启 /etc/init.d/shadowsocks restart

状态 /etc/init.d/shadowsocks status
```

powered by 烈火 alpha team & Inetpub Mr.Chen
