# 【内容安全检查】小程序云开发项目实战

[![](https://main.qcloudimg.com/raw/67f5a389f1ac6f3b4d04c7256438e44f.svg)](https://console.cloud.tencent.com/tcb/env/index?action=CreateAndDeployCloudBaseProject&appUrl=https%3A%2F%2Fgithub.com%2FTCloudBase%2FWXAPP-SecCheck&appName=WXAPP-SEC)

## 项目介绍

此处为项目完整代码，可以直接部署使用；

- 初始化云开发环境，如果有多个云开发环境造成wx.cloud.init错误，则在app.js处进行环境定义。
- 将cloudfunctions文件夹内的2个云函数创建并部署

使用Cloudbase FrameWork部署时，在项目根目录创建.env文件，内容按照下属格式填写：
``` bash
ENV_ID=替换你的云开发环境ID
WX_APPID=替换你的微信小程序appid
WX_CI_KEY_PATH=小程序上传密钥文件路径
```

小程序上传密钥请根据[微信文档](https://developers.weixin.qq.com/miniprogram/dev/devtools/ci.html)获取，另外需要注意关闭或设置IP白名单。

## 参考文档

- [云开发文档](https://developers.weixin.qq.com/miniprogram/dev/wxcloud/basis/getting-started.html)
