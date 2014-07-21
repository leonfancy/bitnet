bitnet
======

北京理工大学校园网Linux CLI登陆客户端

## 安装
```
$ git clone https://github.com/SlimFancy/bitnet.git
$ cp  bitnet/bit-login bitnet/bit-logout /usr/local/bin
```

*注意:* 本程序依赖curl，如果之前没有安装，运行如下命令安装
```
$ sudo apt-get install curl
```


##使用

登陆
```
$ bit-login 
输入用户名: 2120120805
输入密码: your_password
成功登陆
```

退出
```
$ bit-logout 
成功退出
```
