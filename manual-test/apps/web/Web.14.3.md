---
http://open-estuary.org是estuary项目的门户网站，它提供了产品介绍、注册登陆、信息查询、咨询订阅、搭建ARM64平台所需firmware的下载等服务。本用例是为了验证网页的安全性。
 
Hardware platform: PC  
Software Platform: linux or windows 
Author: Vasily Fang <fangyuanzheng3@huawei.com>  
Date: 2017-11-06
Categories: Estuary Documents  
Remark:
---

# Dependency
```
N/A
```

# Test Procedure
```bash
  1.打开网站首页
  2.填写错误的用户密码登陆网页
  3.重复步骤2多次直至用户被锁定
```

# Expected Result
```bash
  多次输入错误密码后用户被锁定
```
