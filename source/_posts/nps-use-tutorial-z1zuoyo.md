---
title: nps使用教程
date: '2023-09-08 16:44:04'
updated: '2023-10-12 20:41:15'
permalink: /post/nps-use-tutorial-z1zuoyo.html
comments: true
toc: true
---

> 参考[docker](https://blog.csdn.net/u012513463/article/details/123679206)
>
> 参考[nps教程](https://www.vediotalk.com/?p=4184)

‍

问题

```c
出现问题，这个地方
http_proxy_ip=0.0.0.0
http_proxy_port=8888
https_proxy_port=443
https_just_proxy=true
```

## 服务端运行

```c
docker run -d --name=nps --restart=always --net=host -v /home/nps/conf:/conf ffdfgdfg/nps
```

## 客户端运行

```c
nohup ./npc -server=124.220.55.6:8024 -vkey=123465 -type=tcp > errorLog.txt 2>&1 &
```

‍
