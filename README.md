# Calculator Frontend

作者：林昊旻（学号：832401116）

前后端分离计算器的 Web 前端，只负责输入、界面显示和调用后端 API，不在浏览器内计算结果。

## 技术栈与环境

- HTML5
- CSS3
- 原生 JavaScript Fetch API

## 启动

先启动后端，再双击 `index.html`；也可以在当前目录运行：

```bash
python3 -m http.server 5500
```

然后打开 `http://127.0.0.1:5500`。

## 配置与前后端对接

开发环境后端地址为 `http://127.0.0.1:8000`。部署时修改 `index.html` 中的 `API_BASE` 为公网后端地址。

前端调用三个接口：

- `POST /api/calculate`
- `GET /api/history`
- `DELETE /api/history/{id}`

停止后端后，前端仍可输入表达式，但无法产生新计算结果，证明核心计算不在前端。
