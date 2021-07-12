## 说明

- css部分使用了uni.scss部分变量, 其他语法已剔除特殊语法, 除变量外可直接替换其他css预处理器
- app.vue下定义了个别全局样式以及引用iconfont图标
- 代码注释比较详细，单独使用请主意1.2两条的引入
- 该项目为前端页面效果展示, 数据和图片来自网络，均只用于案例展示，请勿用于其他用途。

## [官方文档：https://www.uviewui.com](https://www.uviewui.com)

### 官方1群：812144991（已满）

### [点击加6群交流反馈：812144991](https://qm.qq.com/cgi-bin/qm/qr?k=nSvu1k6AFqHVvZhgN9FEavJPXIMyYCxY&jump_from=webapi)

## 特性

- 兼容安卓，iOS，微信小程序，H5，QQ小程序，百度小程序，支付宝小程序，头条小程序
- 60+精选组件，功能丰富，多端兼容，让您快速集成，开箱即用
- 众多贴心的JS利器，让您飞镖在手，召之即来，百步穿杨
- 众多的常用页面和布局，让您专注逻辑，事半功倍
- 详尽的文档支持，现代化的演示效果
- 按需引入，精简打包体积


## 预览

您可以通过**微信**扫码，查看最佳的演示效果。
<br>
<br>
<img src="https://uviewui.com/common/weixin_mini_qrcode.png" width="220" height="220" >


## 友情链接

#### **vue-admin-beautiful** —— [企业级、通用型中后台前端解决方案（基于vue/cli 4 最新版，同时支持电脑，手机，平板）](https://github.com/chuzhixin/vue-admin-beautiful)

#### **vue-admin-beautiful** —— [在线演示](http://beautiful.panm.cn/vue-admin-beautiful/#/index)

#### **pl-table** —— [ 完美解决 element 万级表格数据渲染卡顿问题](https://github.com/livelyPeng/pl-table)

#### **luch-request** —— [基于 Promise 开发的 uni-app 跨平台、项目级别的请求库，它有更小的体积，易用的 api，方便简单的自定义能力](https://www.quanzhan.co/luch-request/)
<br>

## 链接

- [官方文档](https://uviewui.com/)
- [更新日志](https://uviewui.com/components/changelog.html)
- [升级指南](https://uviewui.com/components/changelog.html)
- [关于我们](https://uviewui.com/cooperation/about.html)

## 交流反馈

欢迎加入我们的QQ群812144991交流反馈

## 安装

#### **下载地址** —— [https://ext.dcloud.net.cn/plugin?id=1593](https://ext.dcloud.net.cn/plugin?id=1593)

## 快速上手

1. `main.js`引入uView库
```js
// main.js
import uView from 'uview-ui';
Vue.use(uView);
```

2. `App.vue`引入基础样式(注意style标签需声明scss属性支持)
```css
/* App.vue */
<style lang="scss">
@import "uview-ui/index.scss";
</style>
```

3. `uni.scss`引入全局scss变量文件
```css
/* uni.scss */
@import "uview-ui/theme.scss";
```

4. `pages.json`配置easycom规则(按需引入)

```js
// pages.json
{
	"easycom": {
		// 下载安装的方式需要前面的"@/"，npm安装的方式无需"@/"
		// 下载安装方式
		"^u-(.*)": "@/uview-ui/components/u-$1/u-$1.vue"
		// npm安装方式
		// "^u-(.*)": "uview-ui/components/u-$1/u-$1.vue"
	},
	// 此为本身已有的内容
	"pages": [
		// ......
	]
}
```

请通过[快速上手](https://uviewui.com/components/quickstart.html)了解更详细的内容

## 使用方法
配置easycom规则后，自动按需引入，无需`import`组件，直接引用即可。

```html
<template>
	<u-button>按钮</u-button>
</template>
```

请通过[快速上手](https://uviewui.com/components/quickstart.html)了解更详细的内容


## 隐私、权限声明

1. 本插件需要申请的系统权限列表：

收货地址管理需要定位权限

2. 本插件采集的数据、发送的服务器地址、以及数据用途说明：

无

3. 本插件是否包含广告，如包含需详细说明广告表达方式、展示频率：

无

## 版权信息
遵循[MIT](https://en.wikipedia.org/wiki/MIT_License)开源协议，意味着您无需支付任何费用，也无需授权，即可将应用到您的产品中。
