# 学习笔记

## 二月四日 2021 年

1. qs 是一个挺好的库，用来拼接 url 里的 param 2.注意项目的 util 库，里面的方法很好
2. hook 可以多次运行！
3. 注意 util 中的 customer hooks，hooks 的命名一定是 use 开头
4. 关键点，`React 何时清除 effect？` React 会在组件卸载的时候执行清除操作。正如之前学到的，effect 在每次渲染的时候都会执行。这就是为什么 React 会在执行当前 effect 之前对上一个 effect 进行清除 [传送门](https://zh-hans.reactjs.org/docs/hooks-effect.html#%E4%BD%BF%E7%94%A8-hook-%E7%9A%84%E7%A4%BA%E4%BE%8B)
