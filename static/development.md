# 开发相关

<!-- TODO: 文档示例图片和issue.md图片替换 -->
<!-- TODO: 摸鱼时间逻辑修改 -->
<!-- TODO: readme： 列出支持的浏览器插件，并且去掉chrome相关字眼。 -->

<!-- 
开发TODO: 
流程图的，超过一天的修正。当前时间大于关闭时间怎么办
当天后台关闭的时候，当前时间大于关闭时间，怎么统计。


TODO: firfox兼容
# TODO: 本地id获取 获取本地火狐id链接 getUrl
let fullURL = browser.extension.getURL("beasts/frog.html");
// -> something like:
// moz-extension://2c127fa4-62c7-7e4f-90e5-472b45eecfdc/beasts/frog.html

fireFox直接上传到商店，如果有问题，则解决问题。
否则本地貌似无法调试。 因为上次可以调试，这次只是被禁用以后就无法调试。
firefox兼容: chrome使用 一个一个测试 现在测试
actions上传
    逐个上传插件包
    node 逐个打包 保存打包的zip

整理读书名言（可选）：
更新语录，更新读书笔记中的语录
删除语录

架构（可选）:
梳理环境变量: 删除env文件、或者根据env设置环境变量。
commit相关、eslint相关
更新scripts的脚本使用。
webpack设置，打包压缩。
文件架构梳理
代码质量相关：重复代码检测等

 -->

## 统计相关逻辑

* 有道云笔记

## 环境变量

* NODE_ENV --mode 环境 传递
* VUE_APP_MODE .env.版本 传递
* argv: node deploy.js 参数1 参数2

### 开发
* 写代码
    * 清空issue
    * 清空todo
    * 可选更新架构和工程
    * 可选更新名人名言
* 提交代码
* 写changelog
* 写文档，写功能描述。

## 打包

* 打包各浏览器的应用商店版本
    * 是否修改文档描述
    * 是否修改图片演示
* 打包各浏览器的release版本，通过actions上传到release中。

## tag

* 打tag

### 上传到应用商店。

* 谷歌
* edge
* 火狐