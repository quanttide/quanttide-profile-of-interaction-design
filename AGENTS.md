# AGENTS.md

## 概览

量潮交互设计档案，是交互设计领域的知识整合场：采集各产品（`apps/`）的实际界面与交互经验，提炼为一套统一的交互设计语言（术语、组件、模式、原则、规范），反向指导各产品。

## 目录结构

```
language/           # 交互设计语言（统一语言的载体）
  <topic>.md        # 术语、组件、模式、原则、规范
products/           # 各产品交互设计档案（语言提炼的素材）
  <product>/
    index.md        # 产品交互档案：设计语言、界面布局、交互概览
    patterns.md     # 交互模式档案：关键任务的操作路径、状态流转与反馈
```

## 建设规范

- **以实际产品为准** — 内容从各产品的实际界面与交互采集，而不是凭空设计
- **产品即目录** — `products/` 下每个产品一个目录，目录名与领域仓库 `apps/` 子模块名一致
- **从档案到语言** — 多个产品反复出现的界面与交互，提炼为统一语言条目进入 `language/`
- **语言回流工具** — 语言条目成熟后，固化为设计工具与规范，回流 `packages/quanttide-design-toolkit`

## 参考

- 领域使命：`data/intention/index.md`（quanttide-design 仓库）
- 领域结构：`data/context/design-domain-structure.md`（quanttide-design 仓库）
