---
title: VIM 批量查找替换
date: 2022-10-23 13:25:51
tags:
	- VIM
---


```vim
当前行进行替换
:s/XXX/YYY/g
XXX是需要替换的字符串,YYY是替换后的字符串


全局替换
:% s/XXX/YYY/g


对指定部分进行替换用V进入visual模式,再进行
:s/XXX/YYY/g


或指定行范围 替换
:100,102s/XXX/YYY/g
```
