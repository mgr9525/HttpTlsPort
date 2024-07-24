# http&https 同一端口服务

## 使用
* [example.yml](example.yml)

* [下载](http-tls-port-rs_linux_amd64)

```
./http-tls-port-rs_linux_amd64 -c /etc/httptls/example.yml
```

## 网页中使用

> 使用浏览器访问 **http://test1.example.com/index.html** */ 和 **https://test1.example.com/index.html** 都可正常访问

```
<!-- test1.example.com/index.html -->
<body>
<img src="//test1.example.com:8443/icon.png">
</body>
```

> 当然js和axios.post等也可使用 **//test1.example.com:8443/login**