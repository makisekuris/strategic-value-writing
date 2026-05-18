# strategic-value-writing

> 头疼给领导汇报的时候不知如何组织语言？ 被领导反馈格局过小或者不会宣传工作内容？ 那让我们把文字增加一个赢学（winnology）

中文写作用于向上汇报的文章、ppt文字稿的 agent skill。带有赢学色彩的向上汇报风格，隐藏技术人员的自嗨、转化非技术人员看不懂的细节，输出富有战略远见的文字

## 适用场景

- 在写面向高层的技术汇报、年终总结、晋升 PPT 演讲稿
- 在改写一篇充满了技术细节、报错日志、过程推演的实施记录，使其适合向上级展示
- 在为纯内部的研发效能工具（如脚本、内部后台）包装业务价值
- 在将个人的开源贡献、补丁修复升维成团队或部门的"技术沉淀"

## 不适用：

- 团队内部的纯技术架构评审( 推荐：[luoling8192/technical-writing](https://github.com/luoling8192/technical-writing) )
- 面向一线开发者的 Runbook、排障指南、API 文档
- 开源社区的 Issue 讨论或 PR 描述

## 安装 QUICK START

通过 [skills.sh](https://skills.sh) 一行装，自动检测当前 agent 并写入对应目录：

```bash
 npx skills add makisekuris/strategic-value-writing
```

支持 Claude Code、Cursor、Codex、GitHub Copilot、Windsurf、Gemini、Cline、AMP 等主流 agent runtime。装完在对应 agent 里用 Skill 工具调用 `technical-writing` 即可，也可以在项目的 CLAUDE.md / AGENTS.md 里把它列为常用 skill。

### 手动安装（fallback）

如果不想用 skills.sh，可以直接 clone 后软链接：

```bash
git clone https://github.com/makisekuris/strategic-value-writing.git ~/repos/strategic-value-writing
mkdir -p ~/.claude/skills
ln -s ~/repos/strategic-value-writing ~/.claude/skills/strategic-value-writing
```

OpenAI Codex 用户可参考 `agents/openai.yaml`，按 Codex 文档注册到本地。

## Credits

灵感来源于 [luoling8192/technical-writing](https://github.com/luoling8192/technical-writing) 

感谢作者帮助了我节省了不少时间对文档遣词造句

## License

MIT
