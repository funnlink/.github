# 贡献指南

[English](./CONTRIBUTING.md) | 中文版

感谢你有兴趣为 FunnLink 开源项目做贡献！修 Bug、加功能、写文档、提 Issue，都欢迎。

---

## 工作流

1. Fork 本仓库
2. 创建特性分支: `git checkout -b feature/your-feature` 或 `git checkout -b fix/your-bug`
3. 提交改动，遵循 `type: 简短描述` 的 commit 规范（feat / fix / refactor / docs / style / test / chore）
4. 推送到你的 fork: `git push origin feature/your-feature`
5. 在 Gitea / GitHub 上发起 Pull Request

## 提交前自检

- 跑 `composer pint`（PHP）或对应语言的 linter
- 跑 `composer phpstan`（PHP）或对应静态分析
- 跑测试套件，确保全绿
- 用户可见文案同步更新 `lang/*.php` 多语言文件

## 报告 Bug

用 [Bug 报告模板](https://github.com/funnlink/.github/issues/new?template=bug_report.md) 提交，包含：

- 复现步骤
- 预期 vs 实际行为
- 环境信息（产品 / 版本 / 运行时）

## 提议新功能

用 [Feature 请求模板](https://github.com/funnlink/.github/issues/new?template=feature_request.md) 提交，先描述痛点与方案，再写代码。

## 代码风格

- PHP：Laravel Pint preset
- JavaScript / TypeScript：项目内 ESLint / Prettier 配置
- Python：项目内 ruff / black 配置
- 命名遵循各项目 CLAUDE.md / CONTRIBUTING
  （InnoShop 见 https://github.com/innocommerce/innoshop）

## 行为准则

本项目遵守 [Contributor Covenant Code of Conduct](https://www.contributor-covenant.org/)，参与即表示同意其条款。

## 联系方式

- 技术问题：在对应仓库开 issue
- 商务合作：edward@innoshop.com