## 一个简单的tcp代理

>不支持http协议
>默认监听6000端口

使用方式:
```
tcp-proxy --bind 0.0.0.0:9000 --backend 127.0.0.1:8000
```

client <-> tcp-proxy <-> backend
