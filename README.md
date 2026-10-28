# pm-workflow-skill

`pm-workflow` 是个人产品方案协作 Skill。它引导 Agent 在同一评审版本中制作或修改需求说明与可操作 Demo，默认交付可阅读需求、进入 Demo、就近查看规则的 HTML 评审入口。

Skill 源文件位于 `skills/pm-workflow/`。在 Codex 中安装或引用该目录后，可从 `$pm-workflow` 开始，例如：“使用 `$pm-workflow`，把这项虚构需求做成业务评审版 HTML 评审入口、需求说明和可操作 Demo。”已有方案也可以直接要求修改某条规则或某个交互。

入口指令见 `skills/pm-workflow/SKILL.md`；按需读取 `references/review-stages.md`。需求源文件可用 Markdown；HTML 阅读视图由源内容生成或呈现，Demo 源码定义实际行为，评审页不另存一份待手工维护的规则正文。每个版本成套保存，入口可回看历史快照。评审产物应保存在使用者自己的工作目录，不属于本仓库。仓库仅维护通用 Skill 与从零虚构的示例；不得提交真实业务需求、数据、截图、原型、内部链接或试验产物，即使仓库是私有的。

本版提供协作方法，不含浏览器内文档编辑、批注回写或自动语义同步程序。Agent 应报告实际修改和检查证据；格式校验不能证明 Demo 行为正确。
