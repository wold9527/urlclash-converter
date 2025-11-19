# subconverter-snippet

Clash <-> Link 订阅转换工具

## 这是用来干什么的?

就一个功能: **Clash 配置** 和 **节点链接** 互转

比如这是 Clash 配置:

```yaml
# 已脱敏
proxies:
  - name: 这是名字
    type: vless
    server: 这是服务器
    port: 11451
    uuid: 这是UUID
    flow: xtls-rprx-vision
    network: tcp
    tls: true
    udp: true
    client-fingerprint: chrome
    servername: "www.example-servername-cannot-use.com"
    reality-opts:
      public-key: "这是PubKey"
      short-id: ""
```

TODO