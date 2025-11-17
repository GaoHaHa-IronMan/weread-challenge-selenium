## 如何参与开发

```bash
# 安装依赖
npm install selenium-webdriver nodemailer dotenv
```

从 `.env.example` 复制创建 `.env` 文件，并填入本地开发所需配置。

`vscode` 内按 `F5` 运行, 选择 `node`, 开始调试, 默认使用 `chrome` 浏览器.

## 已知问题

- [ ] `safari`的网页解析不同于`chrome`，暂未测试`safari`的兼容性。