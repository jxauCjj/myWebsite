## 个人网站开发
### 需求分析
- 开发一个个人网站 用于求职和展示自己写的前端项目

### 概要设计
网站开发 主要分为前端和后台两部分

- 前端： 弄清网站的功能需求 -> 设计好草图(可参展网络上的一些网络模板) -> 静态页面开发(使用bootstrap框架)
		-> 为网站增加一些 js动态效果

- 后台： 主要使用php 主要的动态数据为 个人开发的前端项目数据 (这部分需求不太明确 后期可能需要变动) 


### 详细设计

- 前端部分

--页面展示的内容有： 首页 自我介绍 求职意向 个人项目展示（后期可能会增加新功能）
草图设计 没灵感 可参考网络上的网页模板  

前端： 先将基本的html元素和css样式搭建好 后添加js效果  注意考虑响应式

总的要求： 自顶向下 逐步求精 遇到问题 查资料 自己动手解决 一定不难
使用git来进行版本控制

----------------------------------------------------------------------------------
- 开发时遇到的问题

(1）.container类出现内边距和外边距，.container-fluid类没有。
（2）.container类左右内边距一直是15px，屏幕小于等于767px的时候没有margin值，屏幕大于767px开始有左右margin值，屏幕宽度为768px和1000px的时候，margin值相对最小，分别是9px和15px，其他时候margin值随着屏幕的增大而增大。.container-fluid类宽度不管屏幕宽度大小，一直是100%。

- 2019-4-12
页面基本结构和样式完成 但内容过于简单需要增加新内容
页面设计时考虑不周全 需要加强