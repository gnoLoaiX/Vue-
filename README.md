# Vue-demo

看着文档学习Vue的一些小demo
从demo01 至 demo11：
<hr>
总结: 当前学习了几个 Vue 提供的标签了? <br>
component,  template,  transition,  transitionGroup 
<hr>
路由步骤：<br>
1.点击触发url地址的改变，url地址改变之后 触发路由监听进行路由规则匹配 看有没有匹配到的path规则 如果有匹配到的路由规则 代表说展示path 所对应的component 组件 组件要想展示到页面上 那个区域呢? 用router-view 展示到页面中去 （这是路由的匹配的过程）<br>
2.每次都是手动修改链接 那么vue提供了方式 （渲染结果是a标签） <br>
3.tag属性 可以修改渲染的标签<br>
4.但是 默认展示的是根路径  这样不合理，展示的应该是默认的组件 （既然能监听到url地址 那么能不能到没有改变 或者说 是根路径 "/"） 通过配置path可以解决 但是不推荐 因为根路径和login 都是展示一个组件 重叠混淆了。推荐使用重定向（redirect）<br>
5.优化 模拟路由高亮显示 （发现 点击的时候会进行class类的切换 那么Vue可不可以设置一些样式呢？来达到目的） 猜测可能是官方提供的 看文档<br>
6.那怎么添加动画呢？结合使用 实现为路由添加启动动画 <br>
7.导包、创建组件、创建路由规则、挂载、展示（切换）<br>

