## 一个关于 Vue 路由切换动画的例子

### 简要实现步骤

1. 使用 Vue 内置组件 transition 包裹路由出口组件 router-view；
2. 在全局前置守卫中获取路由的 to 和 from 对象，并根据 router-link 的顺序判断当前路由的切换方向（从左到右或从右到左）；
3. 根据路由切换方向动态设置 transition 的 name 属性，并通过 CSS 过渡和变换实现不同的切换动画效果。
