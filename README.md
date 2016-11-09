学习：
ssh-keygen //生成ssh公钥
git 
git init //新建git库
git remote //列出所有远程主机
git remote -v //参看远程主机网址

JavaScript debug 
分析工具


知识点：
一、HTML & CSS
  1.对web标准的理解
  
    web标准分三方面 （结构、表现、行为）
    结构化标准语言：
    HTML是HyperText Markup Language（超文本标记语言）的简写，来源与SGML（The Standard Generalized Markup Language标准通用标记语言），对其语法进行规范化，现已成为国际标准。
    XML是The Extensible Markup Language（可扩展标记语言）的简写，和HTML一样，来源于SGML。
    XHTML是The Extensible HyperText Markup Language（可扩展超文本标记语言）的简写，实现HTML向XML的过渡（在HTML4.0的基础上，用XML的规则对其进行扩展，得到XHTML）。
    HTML 5

    表现标准语言：
    CSS，创建的目的在于以CSS取代HTML的表格式布局、帧和其他表现语言。结构与样式分离，便于站点访问维护。

    行为标准：
    DOM（Document Object Model文档对象模型），一种与浏览器，平台，语言的接口，以访问页面其他的标准组件。（解决NetScaped 网景的 JavaScript和Microsoft的JScript之间的冲突）
    ECMAScript是由ECMA(European Computer Manufacturers Association)制定的标准脚本语言（JAVAScript），遵循ECMAScript 262（ECMA-262标准化的脚本程序设计语言）。

  2.浏览器内核差异
    排版引擎：
    浏览器最核心的部分（Rendering Engine解释引擎），一般称为浏览器内核。
    （1）Trident（MSHTML，IE内核）
    浏览器包括：IE浏览器使用的内核，IE4首次采用并沿用至今、猎豹安全浏览器 （liebao）（IE兼容模式）、360极速浏览器（360chrome）（兼容模式）、360安全浏览器（360SE）分为5.0和6.0,5.0单独的ie内核，6.0是双核，兼容模式为ie内核、搜狗浏览器（Sougou Explorer）（兼容模式）、腾讯TT（Tencent Traveler）、QQ浏览器7（QQ Tour）、百度浏览器（兼容模式）、蚂蚁浏览器（MyIE9）、爱帆浏览器（Avant Browser）、瑞影浏览器（Rayying）、极速云浏览器（Jisuyun）
    （2）Gecko（FireFox内核）：跨品台内核，代码完全公开
    浏览器包括：Mozilla FireFox (火狐浏览器) 、Netscape6开始采用的内核
    （3）Presto：Opera采用的内核，渲染速度的优化达到了极致，也是目前公认网页浏览速度最快的浏览器内核，然而代价是牺牲了网页的兼容性。执行Javascrīpt的时候有着最快的速度。商业引擎，浏览器包括：NDSBrowser、Wii Internet Channle、Nokia 770网络浏览器等。（Opera 2013年2月13日宣布放弃Presto内核，转向Webkit内核）
    （4）Webkit：苹果公司自己的内核，也是Safari浏览器使用的内核，Webkit引擎包含WebCore排版引擎及JavaScriptCore解析引擎，自由软件，开放源代码。
    浏览器包括：Chrome，以及大部分手机浏览器（Android原生浏览器、苹果的Safari、谷歌的Chrome）的内核引擎都是基于Webkit开源内核开发的。
    Chromium计划（blink引擎，Webkit分支）
	
    JavaScript引擎：
    （1）Chakra： 查克拉，IE9启用的新的JavaScript引擎
    （2）SpiderMonkey/TraceMonkey/JaegerMonkey：SpiderMonkey应用在Mozilla Firefox 1.0-3.0，TraceMonkey应用在Mozilla Firefox 3.5-3.6版本，JaegerMonkey应用在Mozilla Firefox 4.0及后续的版本
    （3）V8：应用于Chrome、傲游3
    （4）Nitro：应用于Safari 4及后续的版本
    （5）Linear A/Linear B/Futhark/Carakan：Linear A应用于Opera 4.0-6.1版本，Linear B应用于Opera 7.0～9.2版本，Futhark应用于Opera 9.5-10.2版本，Carakan应用于Opera 10.5及后续的版本
    （6）KJS：KHTML对应的JavaScript引擎

  3.兼容性
  4.hack
  5.CSS基本功：
    （1）布局
    （2）盒子模型
    （3）选择器优先级
  6.HTML5
  7.CSS3
  8.Flexbox

二、JavaScript
  1.数据类型
  2.运算
  3.对象
  4.Function
  5.继承
  6.闭包
  7.作用域
  8.原型链
  9.事件
  10.RegExp （正则表达式）
  11.JSON
  12.Ajax
  13.DOM
  14.BOM
  15.内存泄漏
  16.跨域
  17.异步装载
  18.模板引擎
  19.前端MVC
  20.路由
  21.模块化
  22.Canvas
  23.ECMAScript6
  24.Nodejs

三、其他
  1.移动端
  2.响应式
  3.自动化构建
  4.HTTP
  5.离线存储
  6.WEB安全
  7.优化
  8.重构
  9.团队协作
  10.可维护
  11.易用性
  12.SEO
  13.UED
  14.架构
  15.职业生涯
  16.快速学习能力

必学：
1.DOM结构 —— 两个节点之间可能存在哪些关系以及如何在节点之间任意移动
2.DOM操作 —— 如何添加、移除、移动、复制、创建和查找节点等
3.事件 —— 如何使用事件，以及IE和标准DOM事件模型之间存在的差别
4.XMLHttpRequest —— 这是什么、怎样完整地执行一次GET请求、怎样检测错误
5.严格模式与混杂模式 ——如何触发这两种模式，区分它们有何意义
6.盒模型 —— 外边距、内边距和边框之间的关系，以及IE8以下版本的浏览器中的盒模型
7.块级元素和行内元素 —— 怎么用CSS控制它们、以及如何合理地使用它们
8.浮动元素 —— 怎么使用它们、它们有什么问题以及怎么解决这些问题
9.HTML与XHTML —— 二者有什么区别，你觉得应该使用哪一个，并说明理由
10.JSON —— 作用、用途、设计结构 

