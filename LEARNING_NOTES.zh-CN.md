# GitHub 入门速查

这份中文笔记用于复习仓库中的 GitHub Skills 练习，不替代 [练习 issue #1](https://github.com/return-sin/skills-introduction-to-github/issues/1) 的逐步提示。

## 核心概念

- **Repository（仓库）**：保存项目文件及修改历史。
- **Branch（分支）**：让修改与 `main` 分开，便于比较和讨论。
- **Commit（提交）**：记录一次修改，提交说明应描述修改目的。
- **Pull request（PR）**：提出将分支修改合入目标分支的请求。
- **Merge（合并）**：把 PR 中的修改纳入目标分支。

## 完成一次修改

1. 从最新的 `main` 创建工作分支。
2. 修改文件并提交，避免把无关修改混在一起。
3. 创建 PR，确认 base 是 `main`、compare 是工作分支，并写清修改和验证方式。
4. 在 **Files changed** 检查差异；查看自动检查和评审要求。
5. 按仓库要求处理评审及检查，再合并 PR。
6. 回到 `main` 验证文件内容已更新。

## 本课程的注意事项

- 引导练习第一步要求分支名为 `my-first-branch`。其他分支可用于额外练习，但不会替代课程步骤。
- 以 issue #1 的最新提示为准，等待课程机器人确认后再进行下一步。
- 若没有反馈，先检查分支名，再查看 **Actions** 中相应工作流的状态。
- PR 处于 **Closed** 不一定表示已合并，应确认 **Merged** 状态。
- 不要为了完成练习关闭保护规则；共享仓库应遵循其评审与合并要求。

## 继续阅读

- [English workflow quick reference](LEARNING_NOTES.md)
- [课程步骤原文](.github/steps/1-create-a-branch.md)
