# 1 项目介绍

express-generator 脚手架生成的项目。

# 2 使用

## 2.1 安装依赖

```bash
npm i
```

## 2.2 运行项目（JS 版本）

```bash
DEBUG=express-generator-demo:* npm start
```

## 2.3 运行项目（推荐：TS 版本）

- 把 ./bin/www 文件下中的入口文件切换为 `var app = require("../app2.ts");`

- 然后运行下面的脚本指令：
  ```bash
  DEBUG=express-generator-demo:* npm run dev:ts
  ```
