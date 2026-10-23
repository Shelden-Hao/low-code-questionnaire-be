# low-code-questionnaire-be

低代码问卷系统的 Mock 后端服务：用 Koa + Mock.js 提供问卷相关的假数据接口，方便前端在没有真实服务端时联调。

## 技术栈

| 项 | 说明 |
| :--- | :--- |
| 运行时 | Node.js |
| Web 框架 | Koa + @koa/router |
| 数据 Mock | Mock.js |
| 开发热重载 | nodemon |

## 目录结构

```
low-code-questionnaire-be/
├── index.js        # 服务入口，注册路由与 mock 数据
├── mock/           # Mock.js 数据模板
└── package.json
```

## 启动

```bash
npm install
npm run dev     # nodemon 启动，改动自动重启
```

默认由 `index.js` 中的端口配置决定监听地址。

## 配套仓库

前端见 [low-code-questionnaire-fe](https://github.com/Shelden-Hao/low-code-questionnaire-fe)。
