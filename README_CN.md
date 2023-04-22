<div align="center">
<img src="./docs/images/icon.svg" alt="预览"/>

<h1 align="center">ChatGPT Web</h1>

一键免费部署你的私人 ChatGPT 网页应用。

 [反馈 Issues](https://github.com/langbro/ChatGPT-Web/issues) 

[![Deploy with Vercel](https://vercel.com/button)](https://vercel.com/new/clone?repository-url=https%3A%2F%2Fgithub.com%2Flangbro%2FChatGPT-Web&env=OPENAI_API_KEY&env=CODE&project-name=chatgpt-web&repository-name=ChatGPT-Web)

</div>

## 主要功能

- 在 1 分钟内使用 Vercel **免费一键部署**
- 精心设计的 UI，响应式设计，支持深色模式
- 极快的首屏加载速度（~100kb）
- 海量的内置 prompt 列表，来自[中文](https://github.com/PlexPt/awesome-chatgpt-prompts-zh)和[英文](https://github.com/f/awesome-chatgpt-prompts)
- 自动压缩上下文聊天记录，在节省 Token 的同时支持超长对话
- 一键导出聊天记录，完整的 Markdown 支持
- 拥有自己的域名？好上加好，绑定后即可在任何地方**无障碍**快速访问

## 开始使用

1. 准备好你的 [OpenAI API Key](https://platform.openai.com/account/api-keys);
2. 点击上方按钮开始部署：
3. 部署完毕后，即可开始使用；
4. （可选）[绑定自定义域名](https://vercel.com/docs/concepts/projects/domains/add-a-domain)：Vercel 分配的域名 DNS 在某些区域被污染了，绑定自定义域名即可直连。


## 环境变量

> 本项目大多数配置项都通过环境变量来设置。

### `OPENAI_API_KEY` （必填项）

OpanAI 密钥，你在 openai 账户页面申请的 api key。

### `CODE` （可选）

访问密码，可选，可以使用逗号隔开多个密码。

**警告**：如果不填写此项，则任何人都可以直接使用你部署后的网站，可能会导致你的 token 被急速消耗完毕，建议填写此选项。

### `BASE_URL` （可选）

> Default: `https://api.openai.com`

> Examples: `http://your-openai-proxy.com`

OpenAI 接口代理 URL，如果你手动配置了 openai 接口代理，请填写此选项。

> 如果遇到 ssl 证书问题，请将 `BASE_URL` 的协议设置为 http。

### `OPENAI_ORG_ID` （可选）

指定 OpenAI 中的组织 ID。


## 鸣谢

### 捐赠者

> 见英文版。

## 开源协议
