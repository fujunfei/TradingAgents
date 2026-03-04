# Git Safe Commit

执行安全的 git 提交流程，包括代码审核、冲突检查、自动生成 commit message 等功能。

## 使用方法

当您需要提交代码时，直接说"提交代码"或"提交代码吧"，AI 助手会自动使用 `.cursor/skills/git-safe-commit/SKILL.md` 中定义的完整提交流程。

## 功能特性

- ✅ 代码审核（在 git pull 之前）
- ✅ 自动拉取远程分支
- ✅ 冲突检查（区分真正的冲突和格式问题）
- ✅ 自动生成符合规范的 commit message
- ✅ 从分支名中提取数字并添加到 commit message
- ✅ 用户确认机制（使用 AskQuestion 工具）

## 相关文件

- Skill 定义：`.cursor/skills/git-safe-commit/SKILL.md`
- 代码审核规则：`.cursor/skills/git-safe-commit/code-review-rules.mdc`
