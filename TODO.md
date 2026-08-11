# TODO / 进度任务清单

这个文件由 GitHub Copilot Chat Assistant 根据你的要求创建，便于跟踪项目的后续工作与分工。

## 当前优先级（建议）
1. 改进 README（高）
   - 添加 badges（build、license、npm version、coverage）
   - 增加「快速开始」示例与 Node 版本说明（推荐 Node 14）
   - 展示 screenshots 中的示例图并补充运行截图
   - 增加贡献指南链接（CONTRIBUTING.md）和 PR 模板

2. 添加仓库协作文件（中）
   - CONTRIBUTING.md
   - CODE_OF_CONDUCT.md
   - .github/ISSUE_TEMPLATE.md
   - .github/PULL_REQUEST_TEMPLATE.md

3. CI / 测试（中）
   - 增加 GitHub Actions workflow：npm install → npm test → build
   - 在 README 放置 CI badge

4. 安全与敏感信息检查（高）
   - 在代码库中扫描潜在的 API keys / 私钥 / 凭证字符串
   - 如果发现，立即替换并发布说明

5. 文档与本地开发说明（低）
   - 补充 .env 示例与本地运行配置（包含私有/本地 horizon 示例）
   - 增加常见问题（FAQ）节

6. 其他（可选）
   - 在仓库根目录添加 `progress.md` 或 `milestones` 跟踪里程碑
   - 将之前的截图（你上传的 token 分析截图）放入 `screenshots/` 并在 README 中引用

## 待办项状态（你可以手动更新）
- [ ] 改进 README（待办）
- [ ] 添加 CONTRIBUTING.md（待办）
- [ ] 添加 CI workflow（待办）
- [ ] 敏感信息扫描（待办）
- [ ] 上传并引用 screenshots（待办）

---

如果你允许，我可以为其中一项创建分支并提交初始 PR（例如：`improve-readme` 分支包含改进后的 README 草稿）。回复时请告诉我：
- 想让我先做哪一项（例如 `改进 README`）？
- 是否要我直接创建 PR（需要我提交到默认分支）？

