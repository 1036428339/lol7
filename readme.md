# 要点

- 可以使用html表达的一定不要用图
- inline 元素不能直接设置宽与高
  display: inline-block
- 节日活动页
- bg.jpg 是雪碧图 sprites 
  网页打开速度 速度杀手是 http请求数
  img src
  link href
  script src
  发起 http请求 去下载
  并发HTTP请求数是有限的
- html css 类名 积累取名词汇量
- 背景很华丽 导致页面写法很难
  将背景分离出来盒子 单独做
  用bg-$n 组合将背景铺在下面
  z-index 上下层的关系
  .bg z-index:1
  .mian z-index:2
  .bg position:absolute 定位之后离开正常的文档流
  .mian 将会跟他重合