---
title: git����
date: 2019-03-07 22:12:47
tags: git
---

```
# ����ʹ��http����
```
git config --global http.proxy http://127.0.0.1:10808
git config --global https.proxy https://127.0.0.1:10808

# ����ʹ��socks5����
git config --global http.proxy socks5://127.0.0.1:10808
git config --global https.proxy socks5://127.0.0.1:10808

# ȡ������
git config --global --unset http.proxy
git config --global --unset https.proxy
```