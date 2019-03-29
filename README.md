<br>

<h3 align="center">v-selectpage</h3>

<br>

<p align="center"><img src="https://terryz.github.io/image/v-selectpage/v-selectpage-multiple.png" alt="v-selectpage" ></p>

<p align="center"> v-selectpage的fork项目 </p>

<p align="center">
  <a href="https://www.npmjs.com/package/v-selectpage"><img src="https://img.shields.io/npm/v/v-selectpage.svg"></a>
  <a href="https://mit-license.org/"><img src="https://img.shields.io/badge/license-MIT-brightgreen.svg"></a>
  <a href="https://www.npmjs.com/package/v-selectpage"><img src="https://img.shields.io/npm/dy/v-selectpage.svg"></a>
</p>
<br><br>


## 说明
​       此项目是一个v-selectpage的fork项目，只是v-selectpage很多不适用于本人，所以稍加改制，主要是将分页网络获取自己手动操作了，由父组件下发静态数据到本组件中进行操作。并且内部picked方法增加了locked锁定，避免了input的二次提交。



## 注意

参数和事件都和v-selectpage组件一样，只是新增了几个参数和事件。



## 新增参数

| 参数名       | 必填  | 类型    | 默认值 | 备注               |
| ------------ | ----- | ------- | ------ | ------------------ |
| show-title    | false | Boolean | false  | 是否显示标题       |
| show-title-btn | false | Boolean | false  | 是否显示标题栏按钮 |
| show-search   | false | Boolean | false  | 是否显示搜索框     |
| page-number   | true  | Number  | 1      | 当前页码           |
| total-rows    | true  | Number  | 0      | 数据量总数         |



## 新增事件

| 事件名 | 传入参数 | 传入类型 | 返回 | 备注                                       |
| ------ | -------- | -------- | ---- | ------------------------------------------ |
| page   | pagenum  | Number   | 无   | 翻页事件，可在此函数直接网络获取指定页数据 |



## 原项目

- [English site](https://terryz.github.io/vue/#/selectpage)
- [国内站点](https://terryz.gitee.io/vue/#/selectpage)