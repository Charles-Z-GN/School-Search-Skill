# School Research Skill 1.02

面向本科申请的院校与课程调研工具。根据用户指定的学校和课程，整理官方来源、申请要求与申请人画像之间的事实差距。

- 支持英国、美国、澳大利亚、加拿大。
- 每条已核实事实保留官方原文、来源和日期；学校域名须先由用户确认。
- 不提供选校推荐、录取概率、文书或面试训练。

## 使用

本仓库包含 ChatGPT / Codex Plugin 格式：根目录的 `plugin.json` 和 `skills/school-research/`。

需要独立 Skill 时，可在本仓库的 `skills/school-research/` 目录获取 `SKILL.md`、`references/` 和 `templates/`。导入方式取决于使用的客户端；联网及文件能力由客户端提供。

开始时可输入：

> 使用 school-research，先实测官方网页读取和文件读写能力，只报告结果，不生成学校事实。

本版本完成了打包及本地结构检查，**尚未完成 ChatGPT Work 和 Cherry Studio 的实际跑测，也未验证调研结果的准确性**。使用时请核对官方页面与目标入学年份。
