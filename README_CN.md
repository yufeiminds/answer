<a href="https://answer.dev">
    <img alt="logo" src="docs/img/logo.svg" height="99px">
</a>

# Answer - 构建问答社区

一款极简的、问答形式的知识社区开源软件，用来快速构建产品你的产品问答支持社区、用户问答社区、粉丝社区等。

了解更多关于该项目的内容，请访问 [answer.dev](https://answer.dev).

[![LICENSE](https://img.shields.io/badge/License-Apache-green)](https://github.com/answerdev/answer/blob/main/LICENSE)
[![Language](https://img.shields.io/badge/Language-Go-blue.svg)](https://golang.org/)
[![Language](https://img.shields.io/badge/Language-React-blue.svg)](https://reactjs.org/)
[![Go Report Card](https://goreportcard.com/badge/github.com/answerdev/answer)](https://goreportcard.com/report/github.com/answerdev/answer)

## 截图

![screenshot](docs/img/screenshot.png)

## 快速开始

### 部署 Demo

[![Deploy to Render](https://render.com/images/deploy-to-render-button.svg)](https://render.com/deploy?repo=https://github.com/yufeiminds/answer/tree/deploy-demo-site)

### 使用 docker 快速搭建

```bash
docker run -d -p 9080:80 -v answer-data:/data --name answer answerdev/answer:latest
```

其他安装配置细节请参考 [INSTALL.md](./INSTALL.md)

## 贡献

我们随时欢迎你的贡献!

参考 [CONTRIBUTING.md](CONTRIBUTING.md) 开始贡献。

## License

[Apache License 2.0](https://github.com/answerdev/answer/blob/main/LICENSE)
