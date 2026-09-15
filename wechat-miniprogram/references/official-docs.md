# 微信小程序官方文档索引

本索引对应微信开放文档的小程序开发指南。页面内容和基础库会更新，遇到具体 API、组件属性、最低版本或平台差异时，打开对应官方页面核对最新说明。

## 框架入口

- [小程序开发指南](https://developers.weixin.qq.com/miniprogram/dev/framework/)
- [目录结构](https://developers.weixin.qq.com/miniprogram/dev/framework/structure.html)
- [小程序配置](https://developers.weixin.qq.com/miniprogram/dev/framework/config.html)
- [小程序框架 MINA](https://developers.weixin.qq.com/miniprogram/dev/framework/MINA.html)
- [小程序运行环境](https://developers.weixin.qq.com/miniprogram/dev/framework/runtime/env.html)
- [基础库版本与兼容性](https://developers.weixin.qq.com/miniprogram/dev/framework/client-lib/)

## 界面与组件

- [界面渲染架构](https://developers.weixin.qq.com/miniprogram/dev/framework/view/rendering.html)
- [WXML](https://developers.weixin.qq.com/miniprogram/dev/framework/view/wxml/)
- [WXSS](https://developers.weixin.qq.com/miniprogram/dev/framework/view/wxss.html)
- [组件框架](https://developers.weixin.qq.com/miniprogram/dev/framework/component-framework/)
- [自定义组件](https://developers.weixin.qq.com/miniprogram/dev/framework/custom-component/)
- [组件参考文档](https://developers.weixin.qq.com/miniprogram/dev/component/)
- [框架 API 参考文档](https://developers.weixin.qq.com/miniprogram/dev/reference/)

## 能力与工程

- [基础能力](https://developers.weixin.qq.com/miniprogram/dev/framework/ability/network.html)
- [登录与开放能力](https://developers.weixin.qq.com/miniprogram/dev/framework/open-ability/login.html)
- [插件](https://developers.weixin.qq.com/miniprogram/dev/framework/plugin/)
- [开发者工具](https://developers.weixin.qq.com/miniprogram/dev/devtools/devtools)
- [调试](https://developers.weixin.qq.com/miniprogram/dev/framework/usability/debug.html)
- [性能与体验](https://developers.weixin.qq.com/miniprogram/dev/framework/performance/)
- [小程序安全指引](https://developers.weixin.qq.com/miniprogram/dev/framework/security.html)
- [服务端 API](https://developers.weixin.qq.com/miniprogram/dev/server/API/)
- [云开发指南](https://developers.weixin.qq.com/miniprogram/dev/wxcloudservice/wxcloud/basis/getting-started)

## 按任务路由

- 创建新项目或修复目录问题：先读“目录结构”“小程序配置”。
- 页面、组件、数据绑定或事件问题：先读“MINA”“界面渲染架构”“组件框架”，再查 WXML/WXSS 或组件参考。
- 登录、请求、上传、支付、位置、设备或授权问题：先读对应能力指南和 API 参考，并核对权限、域名、平台和基础库要求。
- 卡顿、白屏、包体积或首屏慢：先读“性能与体验”，再定位启动阶段、渲染阶段、网络阶段或资源阶段。
- 上线前审查：读“运行环境”“调试”“性能与体验”“安全指引”，并补做真机和弱网检查。
