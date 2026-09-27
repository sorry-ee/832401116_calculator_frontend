# 前端代码规范

规范来源：[Google JavaScript Style Guide](https://google.github.io/styleguide/jsguide.html)，并结合本项目的原生 JavaScript 规模做简化。

- HTML 使用语义化标签，并为交互区域提供必要的无障碍属性。
- CSS 类名使用小写短横线形式，相关规则集中排列。
- JavaScript 使用 2 个空格缩进、单引号和分号。
- 变量默认使用 `const`，仅在需要重新赋值时使用 `let`。
- 函数只承担一个清晰职责，异步网络请求使用 `async/await`。
- 前端不计算最终结果；所有结果、历史和错误信息来自后端 API。
- 使用 `textContent` 渲染外部数据，避免将用户内容插入 `innerHTML`。
