# 微信小程序官方框架文档索引

本文件不是官方手册的复制品，而是 skill 的任务路由。微信客户端、开发者工具、基础库、API 参数和平台规则会变化；处理具体任务时打开对应官方页面核对当前内容。

## 框架总入口

- [小程序开发指南](https://developers.weixin.qq.com/miniprogram/dev/framework/)
- [起步](https://developers.weixin.qq.com/miniprogram/dev/framework/quickstart/)
- [目录结构](https://developers.weixin.qq.com/miniprogram/dev/framework/structure.html)
- [小程序配置](https://developers.weixin.qq.com/miniprogram/dev/framework/config.html)
- [小程序框架 MINA](https://developers.weixin.qq.com/miniprogram/dev/framework/MINA.html)
- [小程序运行时](https://developers.weixin.qq.com/miniprogram/dev/framework/runtime/env.html)

## 界面与渲染

- [界面渲染](https://developers.weixin.qq.com/miniprogram/dev/framework/view/rendering.html)
- [WXML 语法](https://developers.weixin.qq.com/miniprogram/dev/framework/view/wxml/)
- [WXSS 样式](https://developers.weixin.qq.com/miniprogram/dev/framework/view/wxss.html)
- [组件框架](https://developers.weixin.qq.com/miniprogram/dev/framework/component-framework/)
- [自定义组件](https://developers.weixin.qq.com/miniprogram/dev/framework/custom-component/)
- [自定义组件脚本](https://developers.weixin.qq.com/miniprogram/dev/framework/custom-component/scripting.html)
- [组件引用](https://developers.weixin.qq.com/miniprogram/dev/framework/custom-component/using-components.html)
- [事件系统](https://developers.weixin.qq.com/miniprogram/dev/framework/component-framework/event-system.html)
- [Skyline 渲染引擎](https://developers.weixin.qq.com/miniprogram/dev/framework/runtime/skyline/introduction.html)
- [Skyline 文档](https://developers.weixin.qq.com/miniprogram/dev/framework/runtime/skyline/)
- [组件参考文档](https://developers.weixin.qq.com/miniprogram/dev/component/)
- [框架参考文档](https://developers.weixin.qq.com/miniprogram/dev/reference/)

## 运行时与基础库

- [运行环境](https://developers.weixin.qq.com/miniprogram/dev/framework/runtime/env.html)
- [JavaScript 支持情况](https://developers.weixin.qq.com/miniprogram/dev/framework/runtime/js-support.html)
- [基础库](https://developers.weixin.qq.com/miniprogram/dev/framework/client-lib/)
- [基础库版本分布](https://developers.weixin.qq.com/miniprogram/dev/framework/client-lib/version.html)
- [兼容性](https://developers.weixin.qq.com/miniprogram/dev/framework/compatibility.html)
- [更新日志](https://developers.weixin.qq.com/miniprogram/dev/framework/release/)

## 基础能力与平台扩展

- [基础能力](https://developers.weixin.qq.com/miniprogram/dev/framework/ability/network.html)
- [网络](https://developers.weixin.qq.com/miniprogram/dev/framework/ability/network.html)
- [插件](https://developers.weixin.qq.com/miniprogram/dev/framework/plugin/)
- [XR-FRAME](https://developers.weixin.qq.com/miniprogram/dev/framework/xr-frame/)
- [连接硬件能力](https://developers.weixin.qq.com/miniprogram/dev/framework/device/bluetooth.html)
- [开放能力](https://developers.weixin.qq.com/miniprogram/dev/framework/open-ability/login.html)
- [小程序 API](https://developers.weixin.qq.com/miniprogram/dev/api/)
- [服务端 API](https://developers.weixin.qq.com/miniprogram/dev/server/API/)

## 调试、性能与安全

- [开发者工具](https://developers.weixin.qq.com/miniprogram/dev/devtools/devtools)
- [调试](https://developers.weixin.qq.com/miniprogram/dev/framework/usability/debug.html)
- [真机调试](https://developers.weixin.qq.com/miniprogram/dev/devtools/remote-debug-2)
- [实时日志](https://developers.weixin.qq.com/miniprogram/dev/framework/realtimelog/index.html)
- [性能与体验](https://developers.weixin.qq.com/miniprogram/dev/framework/performance/)
- [启动性能](https://developers.weixin.qq.com/miniprogram/dev/framework/performance/tips/start.html)
- [运行时性能](https://developers.weixin.qq.com/miniprogram/dev/framework/performance/tips.html)
- [安全指引](https://developers.weixin.qq.com/miniprogram/dev/framework/security.html)

## 业务、平台和运营

- [健康运营指引](https://developers.weixin.qq.com/miniprogram/dev/framework/operation.html)
- [国际化友好适配指南](https://developers.weixin.qq.com/miniprogram/dev/framework/Internationalization-Friendly.html)
- [企业微信兼容](https://developer.work.weixin.qq.com/document/path/92455)
- [小程序搜索](https://developers.weixin.qq.com/miniprogram/dev/framework/search/seo.html)
- [PC 小程序](https://developers.weixin.qq.com/miniprogram/dev/framework/pc/)
- [云开发指南](https://developers.weixin.qq.com/miniprogram/dev/wxcloudservice/wxcloud/basis/getting-started)
- [云托管指南](https://developers.weixin.qq.com/miniprogram/dev/wxcloudservice/wxcloudrun/src/basic/intro)
- [AI 能力](https://developers.weixin.qq.com/miniprogram/dev/ai/guide)

## 按任务读取顺序

### 创建、迁移和结构修复

先读“起步”“目录结构”“小程序配置”；如果涉及新基础库能力，再读“运行环境”“基础库”“更新日志”。

### 页面、组件和交互

先读“MINA”“界面渲染”“WXML”“WXSS”“组件框架”；自定义组件再读“自定义组件”“组件引用”“事件系统”。

### Skyline 或 glass-easel

先读“Skyline 渲染引擎”“组件框架”和“基础库”，核对依赖关系、支持的组件/WXSS、页面级配置、平台覆盖和降级方案。

### 网络、设备和开放能力

先读对应的“基础能力”或“开放能力”入口，再读具体 API；涉及服务器、身份、权限、密钥、支付或云函数时同时读“服务端 API”和“安全指引”。

### XR、硬件和插件

不要套用普通 Web 的实现方式。先确定目标平台和基础库，再分别读取 XR-FRAME、硬件或插件文档，核对权限、生命周期、资源释放和发布约束。

### 调试和线上问题

先记录设备、系统、微信版本、基础库、开发者工具版本、页面路径和复现步骤，再按问题选择调试、真机调试、实时日志、运行环境和更新日志。

### 性能优化

先区分启动性能和运行时性能，再检查分包、首屏请求、`setData`、长列表、图片、动画、内存、资源和网络。优化后在目标真机复测。

### 上线审查

依次检查安全、隐私/授权、网络域名、基础库兼容性、性能、运营/健康、搜索、国际化、企业微信/PC 等实际发布目标。
