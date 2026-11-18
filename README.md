# 中文正式写作

`chinese-formal-writing` 是用于编写、修改和审查简体中文正式文稿的 Codex 技能。它按文种查阅本地条款，可用于公文、学位论文、学术论文、科技报告、技术方案和操作说明，也可单独处理标题、摘要或一段正文。

## 安装

**通过 Git 安装。** 在 macOS 或 Linux 上，使用具有仓库读取权限的 Git 凭据，执行以下命令。

```sh
git clone https://github.com/iorimoe/chinese-formal-writing.git \
  "${CODEX_HOME:-$HOME/.codex}/skills/chinese-formal-writing"
```

**通过浏览器安装。** 登录有权访问仓库的 GitHub 账户，在仓库首页选择 **Code → Download ZIP**。解压后，将包含 `SKILL.md` 的目录重命名为 `chinese-formal-writing`，连同其中的文件一起放入用户主目录下的 `.codex/skills/`。如已设置 `CODEX_HOME`，则放入该目录的 `skills/` 子目录。

## 使用示例

安装后，在 Codex 中输入 `$chinese-formal-writing`，并提供文稿或编写所需的资料。以下请求分别对应三种交付方式。

| 任务 | 示例请求 | 交付内容 |
| --- | --- | --- |
| 编写 | `$chinese-formal-writing` 根据附件中的试验记录编写科技报告摘要，保留测量条件和单位。 | 依据所给记录编写的摘要 |
| 修改 | `$chinese-formal-writing` 修改选中的操作说明，写清校验失败后的处理步骤，保留原有验收指标。 | 指定范围的修订稿 |
| 审查 | `$chinese-formal-writing` 审查这段论文摘要，逐项指出术语、数字和单位的问题。 | 问题位置、判断依据和修改建议，原稿保留 |

文种和读者决定适用的规则。例如，修改学位论文摘要时查阅学位论文条款，编写技术方案时沿用项目已有模板。日常写作按固定版本的条款摘要执行。安装包附有九项标准的 PDF，可从[国家标准索引](references/standards.md)按编号打开，离线查阅完整条文、图表和附录。文种与摘要的对应关系见[技能说明](SKILL.md)。

## 反馈与贡献

欢迎报告规则歧义、提供写作示例或修正条款摘要。反馈时请附上相关文件位置和能说明问题的文稿片段。[提交问题](https://github.com/iorimoe/chinese-formal-writing/issues) · [贡献指南](CONTRIBUTING.md)

## 许可证

本项目的原创内容采用 MIT 许可证。随附的国家标准 PDF 及链接所指向的第三方资料沿用各自的使用条件。[MIT 许可证](LICENSE)
