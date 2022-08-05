
<p align='center'>
  <a href="https://github.com/allinzhang/wujek-ui/">English</a> | <b>简体中文</b>
</p>
## uniapp 多端支持



## 使用方法
### 使用 npm + easycom


npm i @wujek/wujek-ui

在 `pages.json` 添加 `easycom`

{
  "^wujek-(.*)": "@wujek/wujek-ui/lib/wujek-$1/wujek-$1.vue"
}

## 小程序组件
### wujek-ui
|名称|说明|
|---|---|
|wujek-button|[按钮]()|


### 其它
> **注意**
> - `wujek-ui` 不支持使用 `Vue.use()` 的方式安装

### 贡献代码
在使用 `wujek-ui` 中，如遇到无法解决的问题，请提 [Issues](https://github.com/allinzhang/wujek-ui/issues) 给我们
假如您有更好的点子或更好的实现方式，也欢迎给我们提交 [PR](https://github.com/allinzhang/wujek-ui/pulls)