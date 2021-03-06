常用的插件整理一下，免得每次都花时间重新找~

GitHub上面的文章在[这里](https://github.com/ck18781145809/wheels/blob/master/article.md)哟~

-----

目录
=================

* [Layout](#layout)
* [动画库](#%E5%8A%A8%E7%94%BB%E5%BA%93)
  * [\- Hover动画](#--hover%E5%8A%A8%E7%94%BB)
  * [\- 滚动展示动画](#--%E6%BB%9A%E5%8A%A8%E5%B1%95%E7%A4%BA%E5%8A%A8%E7%94%BB)

  * [\- 文本动画](#--%E6%96%87%E6%9C%AC%E5%8A%A8%E7%94%BB)
  * [\- 其他](#--%E5%85%B6%E4%BB%96)
* [滚动库](#%E6%BB%9A%E5%8A%A8%E5%BA%93)
* [纯CSS背景](#%E7%BA%AFcss%E8%83%8C%E6%99%AF)
  * [\- 全屏滚动](#--%E5%85%A8%E5%B1%8F%E6%BB%9A%E5%8A%A8)
* [轮播](#%E8%BD%AE%E6%92%AD)
* [弹出框](#%E5%BC%B9%E5%87%BA%E6%A1%86)
  * [\- 消息通知](#--%E6%B6%88%E6%81%AF%E9%80%9A%E7%9F%A5)
  * [\- Alert](#--alert)
  * [\- Popper](#--popper)
* [表单处理](#%E8%A1%A8%E5%8D%95%E5%A4%84%E7%90%86)
  * [\- 数据加密](#--%E6%95%B0%E6%8D%AE%E5%8A%A0%E5%AF%86)
  * [\- 表单验证](#--%E8%A1%A8%E5%8D%95%E9%AA%8C%E8%AF%81)
  * [\- 日期处理](#--%E6%97%A5%E6%9C%9F%E5%A4%84%E7%90%86)
  * [\- 按钮](#--%E6%8C%89%E9%92%AE)
  * [\- Select](#--select)
    * [\-\- 下拉选择](#---%E4%B8%8B%E6%8B%89%E9%80%89%E6%8B%A9)
    * [\-\- 级联选择器](#---%E7%BA%A7%E8%81%94%E9%80%89%E6%8B%A9%E5%99%A8)
    * [\-\- 颜色选择](#---%E9%A2%9C%E8%89%B2%E9%80%89%E6%8B%A9)
    * [\-\- 时间选择](#---%E6%97%B6%E9%97%B4%E9%80%89%E6%8B%A9)
* [AJAX](#ajax)
  * [\- jsonp](#--jsonp)
* [分页](#%E5%88%86%E9%A1%B5)
* [富文本](#%E5%AF%8C%E6%96%87%E6%9C%AC)
  * [\- Markdown](#--markdown)
* [树形结构](#%E6%A0%91%E5%BD%A2%E7%BB%93%E6%9E%84)
* [定位](#%E5%AE%9A%E4%BD%8D)
* [图片](#%E5%9B%BE%E7%89%87)
  * [\- 预加载](#--%E9%A2%84%E5%8A%A0%E8%BD%BD)
  * [\- 懒加载](#--%E6%87%92%E5%8A%A0%E8%BD%BD)
  * [\- 瀑布流](#--%E7%80%91%E5%B8%83%E6%B5%81)
  * [\- 相册](#--%E7%9B%B8%E5%86%8C)
  * [\- 主题色提取](#--%E4%B8%BB%E9%A2%98%E8%89%B2%E6%8F%90%E5%8F%96)
  * [\- 占位](#--%E5%8D%A0%E4%BD%8D)
  * [\- 滤镜](#--%E6%BB%A4%E9%95%9C)
* [导航](#%E5%AF%BC%E8%88%AA)
* [唤醒APP](#%E5%94%A4%E9%86%92app)
* [视频](#%E8%A7%86%E9%A2%91)
  * [\- 带弹幕](#--%E5%B8%A6%E5%BC%B9%E5%B9%95)
* [复制粘贴](#%E5%A4%8D%E5%88%B6%E7%B2%98%E8%B4%B4)
* [条码](#%E6%9D%A1%E7%A0%81)
  * [\- 条形码](#--%E6%9D%A1%E5%BD%A2%E7%A0%81)
  * [\- 二维码](#--%E4%BA%8C%E7%BB%B4%E7%A0%81)
* [拖拽](#%E6%8B%96%E6%8B%BD)
* [移动端触摸事件](#%E7%A7%BB%E5%8A%A8%E7%AB%AF%E8%A7%A6%E6%91%B8%E4%BA%8B%E4%BB
%B6)
* [文件上传](#%E6%96%87%E4%BB%B6%E4%B8%8A%E4%BC%A0)
* [代码](#%E4%BB%A3%E7%A0%81)
  * [\- 代码高亮](#--%E4%BB%A3%E7%A0%81%E9%AB%98%E4%BA%AE)
  * [\- 代码分享](#--%E4%BB%A3%E7%A0%81%E5%88%86%E4%BA%AB)
* [前端国际化](#%E5%89%8D%E7%AB%AF%E5%9B%BD%E9%99%85%E5%8C%96)
* [地图](#%E5%9C%B0%E5%9B%BE)
* [即时通讯](#%E5%8D%B3%E6%97%B6%E9%80%9A%E8%AE%AF)
* [数据可视化](#%E6%95%B0%E6%8D%AE%E5%8F%AF%E8%A7%86%E5%8C%96)
* [PDF阅读](#pdf%E9%98%85%E8%AF%BB)
* [前端存储](#%E5%89%8D%E7%AB%AF%E5%AD%98%E5%82%A8)
* [数据模拟](#%E6%95%B0%E6%8D%AE%E6%A8%A1%E6%8B%9F)
* [分享](#%E5%88%86%E4%BA%AB)
* [评论](#%E8%AF%84%E8%AE%BA)
  * [代码截图分享](#%E4%BB%A3%E7%A0%81%E6%88%AA%E5%9B%BE%E5%88%86%E4%BA%AB)
* [计算](#%E8%AE%A1%E7%AE%97)
* [引导](#%E5%BC%95%E5%AF%BC)
* [Flutter](#flutter)
* [字体&amp;图标](#%E5%AD%97%E4%BD%93%E5%9B%BE%E6%A0%87)
* [项目流程](#%E9%A1%B9%E7%9B%AE%E6%B5%81%E7%A8%8B)
* [人脸识别](#%E4%BA%BA%E8%84%B8%E8%AF%86%E5%88%AB)
* [其他](#%E5%85%B6%E4%BB%96)
* [polyfill](#polyfill)
* [Gulp](#gulp)
* [Eslint](#eslint)
* [组件库](#%E7%BB%84%E4%BB%B6%E5%BA%93)
  * [React](#react)
  * [小程序](#%E5%B0%8F%E7%A8%8B%E5%BA%8F)
* [VUE](#vue)
  * [插件](#%E6%8F%92%E4%BB%B6)
  * [组件库](#%E7%BB%84%E4%BB%B6%E5%BA%93-1)
* [Chrome插件](#chrome%E6%8F%92%E4%BB%B6)

# Layout

[kitecss](https://github.com/hiloki/kitecss)

- 兼容IE8+的flex替代方案

#  动画库

[Animate.css](https://github.com/daneden/animate.css)

- CSS3 动画库，也是目前最通用的动画库。

[Anime.js](https://github.com/juliangarnier/anime)

- 一个强大的、轻量级的用来制作动画的javascript库

[GreenSock](https://greensock.com/docs/ )

- Tween，Timeline
- 时间线控制动画流程

[Magic.css](https://github.com/miniMAC/magic)

- css3 animation动画库

[Bounce.js](https://github.com/tictail/bounce.js)

- 回弹动画

[Waves](https://github.com/fians/Waves)

- 仿移动端按钮点击波纹效果

[Move.js](http://visionmedia.github.io/move.js/)

- 一个小型的JavaScript库，通过JS来控制一系列的CSS动画顺序执行，使CSS3动画变得非常简单和优雅。

[Velocity.js](https://github.com/julianshapiro/velocity)

- 一个功能齐全的 JavaScript 动画套件 ,`$.animate()`增强版

[bindingx](https://github.com/alibaba/bindingx)

- 在移动端（app）使复杂交互操作以60fps的帧率流畅执行的解决方案
- 水波纹，header的收放等
- 适用于weex，rn。貌似vue也可以。

## - Hover动画

[hover3d](https://github.com/ariona/hover3d)

- 3d悬停效果

[Hover.css](https://github.com/IanLunn/Hover)

- CSS hover 悬停效果，可以应用于链接、按钮、图片等等。

[HoverEffectIdeas](https://github.com/codrops/HoverEffectIdeas)

- 纯CSS图片hover，有很多种搭配好的效果，直接添加样式就ok

[hover-effect](https://github.com/robin-dela/hover-effect)

- [Three.js](https://www.zhihu.com/question/36367846) 和 [TweenMax.js](https://www.tweenmax.com.cn/) 配合使用的敲级酷炫的图片悬停效果

[direction-reveal](https://github.com/NigelOToole/direction-reveal)

-  根据鼠标进入位置，展现从不同方向 展现 hover 效果 
-  支持很多种效果，基本上包含了日常所有的情况 

## - 滚动展示动画

[laxxx](https://github.com/alexfoxy/laxxx)

- 滚动特效库，**推荐使用**
-  压缩完只有 2kb，很轻量 

[Wow.js](https://github.com/matthieua/WOW)

- 滚动展示动画

[ScrollReveal.js](https://github.com/scrollreveal/scrollreveal)

- 滚动展示动画

[Aos.js](https://github.com/michalsnik/aos)

- 滚动展示动画

[Skrollr.js](https://github.com/Prinzhorn/skrollr)

- 滚动展示动画，动画会逐帧执行，适合做背景视差滚动、

[Crossfade.js](https://github.com/mikefowler/crossfade.js)

- 当页面往下滚动的时候，crossfade.js 会让图片渐渐的模糊，就像是将要淡出的感觉；当页面往上滚动的时候，图片又会变的清晰。

## - 文本动画

[textillate](https://github.com/jschr/textillate/)

- 文本逐字动画

##  - 其他

[StackBlur.js](https://github.com/flozz/StackBlur)

- 图片高斯模糊

[NumberFlip](https://github.com/gaoryrt/number-flip)

- 数字老虎机滚动

[SVG-Loaders](https://github.com/SamHerbert/SVG-Loaders)

- svg制作的loading图标


# 滚动库

[Iscroll.js](https://github.com/cubiq/iscroll)

- 平滑滚动插件

[BetterScroll](https://github.com/ustbhuangyi/better-scroll)

- Iscroll优化版，移动端滑动体验更加流畅 

[Mescroll.js](https://github.com/mescroll/mescroll)

- 精致的下拉刷新和上拉加载 js框架.支持vue,完美运行于移动端和主流PC浏览器  

[JqueryScrollbox](https://github.com/wmh/jquery-scrollbox)

- 图片文字滚动插件

[Limarquee](https://github.com/omcg33/jquery.limarquee)

- 基于 jQuery 的无缝滚动插件，类似于 HTML 的 marquee 标签，但比 marquee 更强大。 它可以应用于任何 Web 元素 。

[Animatescroll.js](https://github.com/ramswaroop/animatescroll.js)

- 页面滚动到指定位置

[MalihuCustomScrollbarPlugin](https://github.com/malihu/malihu-custom-scrollbar-plugin)

- jQ滚动条样式美化

# 纯CSS背景

[css3patterns](https://github.com/LeaVerou/css3patterns)

- CSS一姐 [LeaVerou](https://github.com/LeaVerou) 用纯CSS写的一套背景图案

## - 全屏滚动

[fullPage](https://github.com/alvarotrigo/fullPage.js)

- 全屏网站制作



# 轮播

[Swiper](https://github.com/nolimits4web/swiper)

- 最常用的，各端都适用

[iSlider](https://github.com/be-fe/iSlider)

- iSlider是一个表现出众，轻量且高性能，无任何库依赖的跨平台滑动控件。它能够处理大多数的滑动场景，提供多种切换动画效果，展示多种类型的场景。 

[Smoothslides](https://github.com/kthornbloom/Smoothslides)

- 幻灯片内的图片可移动，并且可设置移动的方向（左/右/左上/右下等等），使幻灯片更加特别、有趣。

[OwlCarousel2](https://github.com/OwlCarousel2/OwlCarousel2)

- 支持拖动和滚轮的jQuery响应轮播，一般用在局部轮播



# 弹出框

[layer](http://layer.layui.com/)

- layui独立维护的web弹层组件，包含modal、toast等各种功能弹窗

[Bootstrap](https://v3.bootcss.com/javascript)

- Bootstrap3的插件，包含modal、toast、tooltips

IZI

- 最好看的基于jQuery的弹出框，不绷
- [iziModal](https://github.com/dolce/iziModal)、[iziToast](https://github.com/dolce/iziToast)

## - 消息通知

[notyf](https://github.com/caroso1222/notyf)

- 右下角出现

- 基于jQuery，支持成功（confirm）和失败（alert）两种主题，仅限文本信息

[pnotify](https://github.com/sciactive/pnotify)

- 右下角出现

- 基于jQuery，支持多种主题，多种内容（文字、图片、富文本）

[overhang.js](https://github.com/paulkr/overhang.js)

- 顶部出现
- 基于jQuery，支持多种主题，文字和表单

## - Alert

[sweetalert](https://github.com/t4t5/sweetalert)

- 好看好用

## - Popper

 [popper-core](https://github.com/popperjs/popper-core)

- 只有3kb





# 表单处理

## - 数据加密

[jsencrypt](https://github.com/travist/jsencrypt)

- OpenSSL生成的实际私钥对和公钥对

## - 表单验证

[validator.js](https://github.com/chriso/validator.js)

- 不依赖jQuery，适用于移动端

[jquery-validation](https://github.com/jquery-validation/jquery-validation)

- 基于jQuery，功能齐全

[validform](http://validform.rjboy.cn)

- 国产精品，基于jQuery

## - 日期处理

[moment](https://github.com/moment/moment)

- Moment.js 是一个解析，验证，操作和显示日期和时间的 JavaScript 类库

[dayjs](https://github.com/iamkun/dayjs)

- 2KB，中文文档

## - 按钮

[bttn.css](https://github.com/ganapativs/bttn.css)

- 按钮样式库

## - Select

### -- 下拉选择

[select2](https://github.com/select2/select2)

- 全场最佳

### -- 级联选择器

[ustbhuangyi/picker](https://github.com/ustbhuangyi/picker)

- 移动端最好用的的筛选器组件，高仿 ios 的 UIPickerView ，非常流畅的体验。

[distpicker](https://github.com/fengyuanchen/distpicker)

- 省市区三级联动

### -- 颜色选择

[bootstrap-colorpicker](https://github.com/farbelous/bootstrap-colorpicker)

- Bootstrap 4的组件

### -- 时间选择

[laydate](https://www.layui.com/laydate/)

- layui的时间选择组件





# AJAX

[axios](https://github.com/axios/axios)

- 使用`promise`语法的 ajax 封装

## - jsonp

[jsonp](https://github.com/webmodules/jsonp)

- 简单的jsonp实现

[jsonp-sandbox](https://github.com/aui/jsonp-sandbox)

- 可以安全加载（防xss）jsonp的运行沙盒



# 分页

[paginationjs](https://github.com/superRaytin/paginationjs)

- 基于jQuery



# 富文本

[wangEditor](https://github.com/wangfupeng1988/wangEditor/)

- 轻量化的富文本编辑器，IE10+

[ueditor](https://github.com/fex-team/ueditor)

- 百度UED的富文本编辑器，功能完善，可定制

[ckeditor5](https://github.com/ckeditor/ckeditor5)

- ckeditor5.0版本，好看

[medium-editor](https://github.com/yabwe/medium-editor)

- 专注文本编辑，只有文本编辑

[slate](https://github.com/ianstormtaylor/slate)

- UI好看，高度定制

## - Markdown

[editor.md](https://github.com/pandao/editor.md)

- 开源的、可嵌入的 Markdown 在线编辑器（组件），基于 CodeMirror、jQuery 和 Marked 构建。



# 树形结构

[zTree_v3](https://github.com/zTree/zTree_v3)

- 基于jQuery的多功能树形结构插件



# 定位

[tether](https://github.com/HubSpot/tether)

- 增强绝对定位的功能
- 自带选择框、下拉框、工具提示



# 图片

## - 预加载

[PreloadJS](https://github.com/CreateJS/PreloadJS)

- [CreateJs](http://www.createjs.cc/) 的 预加载模块

## - 懒加载

[jquery_lazyload](https://github.com/tuupola/jquery_lazyload)

- 基于jQuery的懒加载

[LazyImage](https://github.com/VikiLee/LazyImage)

- 个人制作的方法，即开即用

## - 瀑布流

[masonry](https://github.com/desandro/masonry)

- 比较好的一个库，[中文说明](https://www.cnblogs.com/cjc917/p/7402026.html)

## - 相册

[fancybox](https://github.com/fancyapps/fancybox)

- 基于jQuery

[viewerjs](https://github.com/fengyuanchen/viewerjs)

- PC端，不基于jQuery

[PhotoSwipe](https://github.com/dimsemenov/PhotoSwipe)

- 移动端

## - 主题色提取

[rgbaster.js](https://github.com/briangonzalez/rgbaster.js)

- 不基于jQuery

[color-thief](https://github.com/lokesh/color-thief)

- 高赞，名字骚

## - 占位

[holder](https://github.com/imsky/holder)

- 图片占位符插件

## - 滤镜

[CSSgram](https://github.com/una/CSSgram)

- CSS混合模式实现的Instagram的26种滤镜

## - Editor

[tui.image-editor](https://github.com/nhn/tui.image-editor)

- 图片编辑器

[image-cropper](https://github.com/elemefe/image-cropper)

- 图片裁剪，一般用来裁剪头像

# Canvas

[fabric.js](https://github.com/fabricjs/fabric.js)

- 基于canvas的自由创作库
- 提供简单的api

[spritejs](https://github.com/spritejs/spritejs)

- 基于canvas的高性能图形系统， 支持 web、node、桌面应用和小程序的图形绘制和实现各种动画效果 
- 360团队开发

# 导航

[okayNav](https://github.com/VPenkov/okayNav)

- 最OK的响应式导航菜单，不基于jQuery

# 唤醒APP

[callapp-lib](https://github.com/suanmei/callapp-lib)

- 大多数情况下能唤醒大多数APP

# 视频

[chimee](https://github.com/Chimeejs/chimee)

- 支持 mp4、flv 等多种格式，由奇舞团视频云前端组研发

[flv.js](https://github.com/Bilibili/flv.js)

- Bilibili开源纯JavaScript编写的Flash视频播放器

[多青](https://dogeek.net/)

- 视频存储平台，直接加入代码中插入视频

## - 带弹幕

[DanmuPlayer](https://github.com/chiruom/DanmuPlayer)

- Danmmu Player是一个轻量级具备弹幕功能的Html5视频播放器，仅63KB大小

[jquery.danmu.js](https://github.com/chiruom/jquery.danmu.js)

- 基于jQuery的弹幕效果插件，可以运用在网页的任何位置，不局限视频



# 复制粘贴

[clipboard.js](https://github.com/zenorocha/clipboard.js/)

- 仅有3kb



# 条码

## - 条形码

[JsBarcode](https://github.com/lindell/JsBarcode)

- 条形码生成，可以爱浏览器和Node运行

## - 二维码

[jquery-qrcode](https://github.com/jeromeetienne/jquery-qrcode)

- 基于jQuery的二维码生成插件



# 拖拽

[draggabilly](https://github.com/desandro/draggabilly)

- 支持IE10+ 和触摸设备。

[dragula](https://github.com/bevacqua/dragula)

- 拖动容器插件，类似于穿梭框，[中文说明](https://www.toutiao.com/a6491847196890104334)



# 移动端触摸事件

[hammer.js](https://github.com/hammerjs/hammer.js)

- 移动端触摸手势检测，[中文说明](https://www.jianshu.com/p/0b0b9364f967)

[fastclick](https://github.com/ftlabs/fastclick)

- 消除移动端点击300ms延迟



# 文件上传

[webuploader](https://github.com/fex-team/webuploader/)

- 简单的以HTML5为主，FLASH为辅的现代文件上传组件,兼容性好

[filepond](https://github.com/pqina/filepond )

- 好看就完了



# 代码

## - 代码高亮

[highlight.js](https://github.com/highlightjs/highlight.js)

- 在HTML中展示代码

## - 代码分享

[carbon](https://github.com/dawnlabs/carbon)

- 代码分享图片美化



# 前端国际化

[i18next](https://github.com/i18next/i18next)

- 前端国际化就是网站语言的切换
- [实现例子1](https://blog.csdn.net/aixiaoyang168/article/details/49336709)，[实现例子2](http://www.cnblogs.com/landeanfen/p/7581609.html)

[vue-i18n](https://github.com/kazupon/vue-i18n)

- i18n的Vue实现



#  地图

[百度地图](http://lbsyun.baidu.com/)

[高德地图](https://lbs.amap.com/)

[腾讯地图](https://lbs.qq.com/)

[谷歌地图](https://cloud.google.com/maps-platform/?hl=zh-cn)



# 即时通讯

[layim](http://layim.layui.com/)

- LayIM 是基于 layui 的一款独立的付费组件，它是网页即时通讯（WebIM） UI 解决方案，包含丰富的前端接口，您购买授权后得到的是一套前端源代码，而后端程序需自写。

[闲聊么](https://www.xianliao.me/)

- 聊天室



# 数据可视化

[echarts](https://github.com/apache/incubator-echarts)

- 百度出品，文档有点超啊

[antv](https://antv.alipay.com/zh-cn/index.html)

- 蚂蚁金服出品，图表参数稍微好配置一点

[SandDance](https://sanddance.js.org/ )

- 微软出品
- 图表类型很少，强在3d效果

[roughViz]( https://github.com/jwilber/roughViz )

- 手绘风图表
- 支持 Vue 和 React

# PDF阅读

[pdf.js](https://github.com/mozilla/pdf.js)

- P一其随



# 前端存储

[storage](https://github.com/ustbhuangyi/storage)

- 封装了sessionStorage和localStorage

[store.js](https://github.com/jaywcjlove/store.js)

- 封装了localstorage，提供强大的API

[localForage](https://github.com/localForage/localForage)

- 离线存储的改进，包含[IndexDB](https://www.zhangxinxu.com/wordpress/2017/07/html5-indexeddb-js-example/)、LocalStorage



# 数据模拟

[easy-mock](https://github.com/easy-mock/easy-mock)

[Mock](https://github.com/nuysoft/Mock)

[yapi](https://yapi.ymfe.org/)

- 鑫神推荐



# 分享

[bshare](http://www.bshare.cn/)

- jiaThis下线，首选

[share.js](https://github.com/overtrue/share.js/)

- 好看



# 评论

[gitalk](https://github.com/gitalk/gitalk)

- 基于 GitHub Issue 和 Preact 开发的评论插件。
- GitHub账号登录

[畅言](https://changyan.kuaizhan.com/)

- 定制化
- 自带过滤

[来必力](http://www.laibili.com.cn)

- 无需注册,使用已有社交账号便可方便快捷地登录。

## 代码截图分享

[carbon](https://github.com/dawnlabs/carbon)

- 创建漂亮的代码分享图片



# 计算

[number-precision](https://github.com/nefe/number-precision)

- 超小体积
- 完美支持浮点数的加减乘除、四舍五入等运算。



# 引导

[tourist](https://github.com/easelinc/tourist)

- Bootstrap风格

# Flutter

[flutter-go](https://github.com/alibaba/flutter-go)

- flutter 开发者帮助 APP，包含 flutter 常用 140+ 组件的demo 演示与中文文档
- 阿里出品

# 字体&图标

[fontmin](https://github.com/ecomfe/fontmin-app)

- 网易出品，中文生成字体文件
- 桌面应用

[simple-icons](https://github.com/simple-icons/simple-icons)

- 流行品牌的svg图标

# 项目流程

[elf](https://github.com/o2team/elf)

- 京东，h5项目快速构建

[parcel](https://github.com/parcel-bundler/parcel)

- 轻量级打包工具

# 人脸识别

[face-api](https://github.com/justadudewhohacks/face-api.js )

- 浏览器运行的人脸识别库
- 封装 tensortflow.js人脸识别核心库

# js工具

[javascript-obfuscator](https://github.com/javascript-obfuscator/javascript-obfuscator/)

- js代码混淆工具

[lodash](https://github.com/lodash/lodash/)

- 非常实用的工具库
- 内部封装了字符串、数组、对象等常见数据类型的处理函数

[jtools](https://github.com/Pasoul/jtools)

-   封装常用的工具函数，如日期格式化、浏览器判断等

-  提高开发效率

[jscodeshift](https://github.com/facebook/jscodeshift)

-  将 js 内容解析成 AST 语法树，并提供一些便利的操作接口，方便我们对各个节点进行更改 
-  如果需要去做一些底层的高级处理，就能用上这个插件

# 其他

[airbnb代码规范](https://github.com/airbnb/javascript)

- 爱彼迎js代码规范

[pinyin](https://github.com/hotoo/pinyin)

- 转换中文字符为拼音。可以用于汉字注音、排序、检索。

[github-markdown-toc](https://github.com/ekalinin/github-markdown-toc.go)

- README.md目录生成
- 多种语言

[eruda](https://github.com/liriliri/eruda)

- 专为手机网页前端设计的调试面板，类似 DevTools 的迷你版
- 捕获 console 日志、检查元素状态、捕获XHR请求、显示本地存储和 Cookie 信息等等。

[shields](https://github.com/badges/shields)

- readme徽章制作
- 样式有限制

#  polyfill

[focus-visible](https://github.com/WICG/focus-visible)

- css伪类`:focus-visible`  polyfill

[ieBetter](https://github.com/zhangxinxu/ieBetter.js)

- H5新特性兼容ie6~8

[classList.js](https://github.com/eligrey/classList.js/)

- H5 `classlist`属性增强

[object-fit](https://github.com/anselmh/object-fit)

- css `object-fit` 属性增强

[compass-flexbox](https://github.com/stevenbenisek/compass-flexbox)

- 所有浏览器更好的支持flexbox

[FormData](https://github.com/jimmywarting/FormData)

- 解决formdata在 ie 10+ 的兼容



# Gulp

[use-gulp ](https://github.com/Platform-CUF/use-gulp)

- gulp 插件整理

[purifycss](https://github.com/purifycss/purifycss)

-  移除没使用到的 css

[javascript-obfuscator](https://github.com/javascript-obfuscator/javascript-obfuscator/)

- js代码混淆工具

# Eslint

[eslint](https://github.com/eslint/eslint)

- Eslint官方

[eslint-plugin-vue](https://github.com/vuejs/eslint-plugin-vue)

- Vue 官方规范

[eslint-airbnb](https://github.com/airbnb/javascript)

- Airbnb 规范



# 组件库

[Bootstrap](http://www.bootcss.com/)

- 响应式

[lulu-ui](https://github.com/yued-fe/lulu)

- 兼容ie7/8
- 面向用户，阅文出品

[Semantic-UI](https://github.com/Semantic-Org/Semantic-UI)

- 响应式

[amazeui](https://github.com/amazeui/amazeui)

- 响应式，国产

[Flat-UI](https://github.com/designmodo/Flat-UI)

- pc

[ant-design](https://github.com/ant-design/ant-design)

- pc，移动端有[ant-design-mobile](https://github.com/ant-design/ant-design-mobile)

[bulma](https://github.com/jgthms/bulma)

- 移动，推荐

[weui](https://github.com/Tencent/weui)

- 移动，微信组件

[tailwindcss](https://github.com/tailwindcss/tailwindcss)

- 样式与结构分离集大成
- postcss语法，可以配合sass使用

## React

[material-ui](https://github.com/mui-org/material-ui)

- 最符合material-design

## 小程序

[vant-weapp](https://github.com/youzan/vant-weapp)

- 有赞团队

[iview-weapp](https://github.com/TalkingData/iview-weapp)

- 一套高质量的微信小程序 UI 组件库 

[minui](https://github.com/meili/minui)

- 基于规范的小程序 UI 组件库，自定义标签组件，简洁、易用、工具化

[wux-weapp](https://github.com/wux-weapp/wux-weapp)

- 组件比较丰富，值得使用。

# VUE

## 插件

[vueg](https://github.com/jaweii/vueg#/vueg)

- Vue转场

[cssfx]( https://github.com/jolaleye/cssfx )

- 常用按钮hover、文字effect、loading动画组件

[handsontable ](  https://github.com/handsontable/handsontable  )

-   Handsontable是用于Web应用程序的JavaScript数据网格组件。 
-  支持所有的标准操作，增删改查以及过滤排序，可以按需定制。 
-  可以导出为 csv 文件

[sheetjs]( https://github.com/SheetJS/sheetjs )

-  SheetJS是一个浏览器操作excel文件的JS库，支持每种Excel文件格式；
- 修改后能另存为 xlsx、xlsb、xls、ods、fods格式

[vue-bigdata-table]( https://github.com/lison16/vue-bigdata-table )

-  基于Vue.js的百万级数据表格组件，支持编辑、筛选、过滤、粘贴、拖动调整列宽等多种功能 
- 固定表头和列

[Mini Music Player]( https://codepen.io/JavaScriptJunkie/pen/qBWrRyg?__cf_chl_jschl_tk__=18657b00fd09c74cea6a7c3a90ea035047c42c0d-1575595345-0-Af-LEVuwxO-HYZZFjf-iTJBkljP7P_DTTUGQHA6GDlF65aKi3kuZtJhfQF5Pq2MSFRZj8DF9Tig_rnyw-EmPBa_lgjjDjhUMPwLW_dYJxugyBu-SSA100NxIa_doA6uuOVt3YwIbVK1izAD2n6vOKcnlTanHfngLnPO-tugb8YV_nAKZa38i7sbEBOFZuaNQAarOI6vIQo9MZDC8OowFqe4_lVHlN_WnwkTVePHiKUKPVKom-B-kAnhXpDKL9Y8Ecowsn7fEs2IPIpdNkqsidcvZyuJ2FiSdu0fu4qigT1wZBRiXWVF8i54SA1Q4lOQcxwDCc7Je1_FDyiK32Xo5STZTjpi1uHPBxjq8oj5fi1k2 )

-  国外友人写的一个`Vue.js`音乐播放器，好看的不得了 

[vue-interactive-paycard](https://github.com/muhammederdem/vue-interactive-paycard)

- 炒鸡好看的卡片验证
-  银行卡

[typed.js](https://github.com/mattboldt/typed.js )

-  Typed是一个专注打字动画的库

[Vue.Draggable](https://github.com/SortableJS/Vue.Draggable)

- 后台拖拽场景的完美方案

[vue-virtual-scroller](https://github.com/Akryum/vue-virtual-scroller)

- 性能不错的无限滚动方案

[vuescroll](https://github.com/yvescoding/vuescroll)

- 不错的PC端滚动美化

## 组件库

[cube-ui](https://github.com/didi/cube-ui)

- 移动

[element](https://github.com/ElemeFE/element)

- pc、管理系统

[mint-ui](https://github.com/ElemeFE/mint-ui)

- 移动

[iview](https://github.com/iview/iview)

- pc、管理系统

[muse-ui](https://github.com/museui/muse-ui)

- materia-ui风格
- pc、面向用户

[vant](https://github.com/youzan/vant)

- 有赞团队

[vux](https://github.com/airyland/vux)

- 移动端

[vuetify](https://github.com/vuetifyjs/vuetify)

- pc

[ant-design-vue](https://github.com/vueComponent/ant-design-vue)

- pc
- ant-design

[nutUI](https://github.com/jdf2e/nutui )

- 移动端
- 京东团队

# Chrome插件

[ColorPick Eyedropper](https://chrome.google.com/webstore/detail/colorpick-eyedropper/ohcpnigalekghcmgcdcenkpelffpdolg)

- 网页拾色器

[Window Resizer](https://chrome.google.com/webstore/detail/window-resizer/kkelicaakdanhinjdeammmilcgefonfh)

- 调整浏览器窗口大小

[Lightshot](https://chrome.google.com/webstore/detail/lightshot-screenshot-tool/mbniclmhobmnbdlbpiphghaielnnpgdp)

- 截图

[Dimensions](https://chrome.google.com/webstore/detail/dimensions/baocaagndhipibgklemoalmkljaimfdj)

- 测距

[Tampermonkey](https://chrome.google.com/webstore/detail/tampermonkey/dhdgffkkebhmkfjojejmpbldmpobfkfo)

- 油猴

[Click&Clean](https://chrome.google.com/webstore/detail/clickclean/ghgabhipcejejjmhhchfonmamedcbeod)

- 清理浏览器

[JetBrains IDE Support](https://chrome.google.com/webstore/detail/jetbrains-ide-support/hmhgeddbohgjknpmjagkdomcpobmllji)

- webstorm网页调试
- 一般来搞实时刷新

[LiveReload](https://chrome.google.com/webstore/detail/livereload/jnihajbhpnppcggbcgedagnkighmdlei)

- 实时刷新

[Allow-Control-Allow-Origin: *](https://chrome.google.com/webstore/detail/allow-control-allow-origi/nlfbmbojpeacfghkpbjhddihlkkiljbi)

- 允许跨域

[Vue.js devtools](https://chrome.google.com/webstore/detail/vuejs-devtools/nhdogjmejiglipccpnnnanhbledajbpd)

- Vue调试

[Essential SEO Toolkit (SEO Analysis Tool)](https://chrome.google.com/webstore/detail/essential-seo-toolkit-seo/icagkiolfkmndbggheneeamfbnobcdma)

- 集合SEO调试，性能分析（yslow，PageSpeed）等

[Full Page Screenshot](https://chrome.google.com/webstore/detail/full-page-screenshot/glgomjpomoahpeekneidkinhcfjnnhmb)

- 整站截图

[GitHub Repository Size](https://chrome.google.com/webstore/detail/github-repository-size/apnjnioapinblneaedefcnopcjepgkci)

- 显示GitHub每个文件的大小

[GitHub Hovercard](https://chrome.google.com/webstore/detail/github-hovercard/mmoahbbnojgkclgceahhakhnccimnplk)

- hover文件或作者的时候显示简介

[Charset](https://chrome.google.com/webstore/detail/charset/oenllhgkiiljibhfagbfogdbchhdchml)

- 改变当前页面编码

[Octotree](https://chrome.google.com/webstore/detail/octotree/bkhaagjahfmjljalopjnoealnfndnagc)

- 在GitHub项目中展示结构

[baiduyun](https://github.com/syhyz1990/baiduyun)

- 油猴脚本
- 直接下载百度网盘和百度网盘分享的文件,直链下载超级加速