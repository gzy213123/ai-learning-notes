# AI Learning Notes

这是我的学习仓库工作区，当前重点记录 `domains/ai-interview-engineer/` 这条学习线。

## 目录说明

- `domains/ai-interview-engineer/docs/`
  - 知识文档，按日期和主题记录
- `domains/ai-interview-engineer/sessions/`
  - 每次学习会话的记录和诊断
- `domains/ai-interview-engineer/knowledge-graph.json`
  - 概念掌握状态
- `domains/ai-interview-engineer/learner-profile.json`
  - 常见误区、解释偏好、学习特征
- `domains/ai-interview-engineer/meta.json`
  - 学习域元信息

## 推荐工作流

每次学习后：

```powershell
git status --short -- .gitignore README.md domains/ai-interview-engineer
git add .gitignore README.md domains/ai-interview-engineer
git commit -m "learn: refine notes on a topic"
git push
```

## 跨设备继续学习

在另一台设备上：

```powershell
git clone https://github.com/gzy213123/ai-learning-notes.git
cd ai-learning-notes
git pull
```

学习前先 `git pull`，学习后再 `git commit` 和 `git push`。

## 提交信息建议

- `learn: add note on ...`
- `learn: refine ...`
- `progress: update knowledge graph`
- `review: reorganize roadmap`
