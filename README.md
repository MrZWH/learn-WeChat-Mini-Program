## 小程序的背景
- 为什么会有小程序
  - 更好的体验
  - 规范与管理
- 什么是小程序
  - 触手可及
  - 用完即走
  - 无需安装卸载
- 小程序与应用程序的区别
  - 无需安装
  - 不占内存
  - 易传播
- 小程序能做什么

## 小程序开发准备工作
1. 注册小程序账号 （https://mp.weixin.qq.com/）
2. 激活邮箱
3. 信息登记
4. 登录小程序管理后台
5. 完善小程序信息
6. 绑定开发者

## 微信小程序开发框架
### 基本构成
- WXML
- WXSS
- WXS
- JavaScript

### WXML（WeiXin Markup Language）
是框架设计的一套标签语言，结合组件、WXS和事件系统可以构建出页面的结构。
语言特性：
- 数据绑定
- 列表渲染
- 条件渲染
- 模板引用

属性：
- id
- class
- style
- hidden
- data-*
- bind* / catch*

### 生命周期
#### 小程序应用的生命周期
- onLaunch
- onShow
- onHide
- onError

#### 页面生命周期
- onLoad
- onShow
- onReady
- onHide
- onUnload

### 事件
- 事件是视图层到逻辑层的通讯方式
- 事件可以将用户的行为反馈到逻辑层进行处理
- 事件可以绑定到组建上，触发事件后，就会执行逻辑层中对应的事件处理函数。
- 事件对象可以携带额外的信息。
可捕获事件：
- touchstart
- touchmove
- touchcancel
- touchend
- tap
- longpress
- longtap
可冒泡事件：
- touchstart
- touchmove
- touchcancel 手指在屏幕上被打断
- touchend
- tap
- longpress
- longtap
- transitionend
- transitionstart
- animationstart
- animationiteration
- animationend
- touchforcechange