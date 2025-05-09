# 贡献

> 有关所有贡献事项的文档网站。从这里开始你的贡献之旅。

欢迎来到 freeCodeCamp.org “Contribute” 网站的代码仓库。

你可以在这里找到如何为 freeCodeCamp 做贡献的信息，以及本网站的源代码。本网站使用 [Astro](https://astro.build/) 构建，这是一个现代静态网站生成器。我们的目标是让这里成为 freeCodeCamp 贡献相关内容的一站式平台。

项目看板：https://github.com/orgs/freeCodeCamp/projects/40 展示了项目的当前状态。

如果你想为本项目做贡献，请在 [issues 标签页](https://github.com/freeCodeCamp/contribute/issues) 查找 help wanted 问题。

> [!WARNING]
> 本仓库正在经历大量重构/开发阶段。我们正在为贡献者打造全新的体验。如果你有任何问题或需要帮助，请加入我们的 Discord: https://chat.freecodecamp.org 联系我们。

## 入门指南

你的典型开发流程如下：

1. **Fork** 本仓库到你的 GitHub 账户。
2. **Clone** 你 fork 的仓库副本。
3. **设置 upstream** 指向原始仓库。
4. **创建新分支** 用于你的更改。
5. **对网站进行更改**。
6. **提交** 你的更改到分支。
7. **推送** 分支到你 fork 的仓库。
8. **向原始仓库发起 Pull Request**。

如需更详细的说明，请参阅本指南（_待补充_）。

开发项目：

```bash
npm install -g pnpm
pnpm install
pnpm develop
```

构建并部署项目（虚拟机）：

```bash
pnpm build
pnpm start
```

构建并部署项目（Cloudflare Pages）：

在构建配置中设置如下：

- 框架预设：`none` - Astro 虽然有预设，但我们未使用。
- 构建命令：`pnpm build`
- 构建目录：`dist`

其余设置保持默认。

# 许可证

版权所有 © 2024 freeCodeCamp.org，遵循 [BSD 3-Clause License](LICENSE) 许可协议。
