# MAP.md：目录与配置映射

核验日期：2026-11-08，范围：项目根目录现有文件（不含 `个人文件/`，见 [AGENTS.md](../../AGENTS.md) 第 1 节）。

## 1. 当前实际结构

```text
.gitignore
AGENTS.md
PROJECT_INDEX.md
README.md
docs/
  钢材表面缺陷分类项目_需求说明与验收标准_V0.2.md
  项目开发方案_V1.0.md
  项目选题建议与需求确认.md
  context/
    NOW.md  MAP.md  RUNBOOK.md  DECISIONS.md  RISKS.md
    history/README.md
```

代码、配置、数据、模型目录均未创建。

## 2. 计划结构

计划的完整目录与各模块职责以开发方案第 4 章为准（链接见 [PROJECT_INDEX.md](../../PROJECT_INDEX.md)），此处不复制。创建后更新第 1 节。

## 3. 配置、版本与运行位置

| 项目 | 状态 |
|---|---|
| 公共配置 `configs/base.yaml` | 未创建；字段约定见开发方案第 5.1 节 |
| Python / PyTorch / CUDA 版本 | 待核实（计划 Python 3.11） |
| 训练主机 | 待核实 |
| 代码仓库 | 已在项目根目录初始化本地 Git 仓库，分支 `main`；远程 `origin`：[GitHub 仓库](https://github.com/OHYEAH-42/Steel-Defect-Detection)；提交与同步状态以 `git status` 为准 |
| 数据存放 | 计划 `data/raw/`，不提交 |
| 最终权重发布位置 | 待定（网盘或 GitHub Release） |
| 部署 | 不部署，仅本地运行 Streamlit |
