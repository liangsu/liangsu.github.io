---
title: git命令
date: 2019-03-07 22:12:47
tags: git
---

```
# 以下使用http代理
```
git config --global http.proxy http://127.0.0.1:10808
git config --global https.proxy https://127.0.0.1:10808

# 以下使用socks5代理
git config --global http.proxy socks5://127.0.0.1:10808
git config --global https.proxy socks5://127.0.0.1:10808

# 取消代理
git config --global --unset http.proxy
git config --global --unset https.proxy
```