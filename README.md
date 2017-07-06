# vue_basic_test
vue基础练习

按照vue官网（https://cn.vuejs.org/）上的教程进行的练习 

demo:熟悉了vue的基础语法

nav:非常简单的下拉菜单，熟悉了vue的组件分发机制，数据传输
通过v-on:click和v-show来实现

submit:简单的表单练习，熟悉了计算属性的用法
用v-model在input上创建双向数据绑定
简单逻辑用Computed开销更小，更方便
相较于Methods和Watchers：
Computed:基于它们的依赖进行缓存，只有在它的依赖发生变化时，才会重新计算。
Methods:只要发生重新渲染，method总会调用执行函数。
Watchers:在数据变化响应时，执行异步操作或开销较大的操作。限制我们执行该操作的频率，并在我们得到最终结果前，设置中间状态。
