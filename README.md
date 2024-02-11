<p align="center">
  <img alt="Web client demo" src="./demos/client.png?v=3">
</p>

# PandoraAI

PandoraAI 是一个网络聊天客户端，基于 [node-chatgpt-api](https://github.com/waylaidwanderer/node-chatgpt-api), 允许用户轻松与多个人工智能系统聊天，同时还提供对自定义预设的支持。 凭借其无缝且便捷的设计，PandoraAI 提供了引人入胜的对话式 AI 体验。

构建使用 [Nuxt 3](https://v3.nuxtjs.org/), a Vue 3 框架.  
只要端点兼容，您也可以将 PandoraAI 与其他 API 服务器实现一起使用。

## 功能

- 与`node-chatgpt-api`支持的所有 AI 聊天，包括`gpt-3.5-turbo`、`text-davinci-003`、ChatGPT 和 Bing。
- 支持为每个客户端创建多个预设。
![Client Settings](demos/client-settings.png) 
- 在不同的客户端或自定义预设之间进行选择。
![Client Dropdown](demos/client-dropdown.png)
- 所有内容都存储在本地存储中，因此您无需帐户即可使用此客户端，并且可以将其导入或导出到其他设备。

<details>
<summary><strong>Nuxt 3 Setup</strong></summary>

访问 [Nuxt 3 documentation](https://nuxt.com/docs/getting-started/introduction) 来学习。

## 设置

确保安装依赖项：

```bash
# yarn
yarn install

# npm
npm install

# pnpm
pnpm install
```

## 开发服务器

在 http://localhost:3000 上启动开发服务器

```bash
npm run dev
```

## 产品

构建生产应用程序：

```bash
npm run build
```

本地预览生产版本：

```bash
npm run preview
```

访问 [deployment documentation](https://nuxt.com/docs/getting-started/deployment) 获取更多信息。
</details>

## 设置

1. 请按照上面的 Nuxt 3 设置说明进行操作。
2. R从 [node-chatgpt-api](https://github.com/waylaidwanderer/node-chatgpt-api#api-server)运行 API 服务器。
3. Copy `.env.example` to `.env` and fill in the `API_BASE_URL` variable with the URL of the API server.
4. 将 `.env.example` 复制到 `.env` 并使用 API 服务器的 URL 填充 `API_BASE_URL` 变量。
   1. 将 `.env.example` 复制到 `.env` 并使用 API 服务器的 URL 填充 `API_BASE_URL` 变量。

## 贡献
如果您想为此项目做出贡献，请创建一个拉取请求并详细描述您的更改。

## 注册表
该项目已获得 MIT 许可证的许可。
