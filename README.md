# github-weekly-brief

每周 GitHub 热门简报 HTML 存档。每周日生成一份单页报告，按 **综合热门 / 网络安全 / Agent / AI** 四个板块
收录当周（执行日往前 7 天）新建并快速冲榜的项目，每张卡片展开后给出三段内容：

- **能怎么用** — 实际用途、典型用法、上手命令
- **能否结合当前 agent 实际** — 与具体在跑的工作对得上还是弱关联
- **如何优化当前 agent 任务处理** — 可落地的结合点与下一步

## 入口

- 索引页：<https://maisukrajima.github.io/github-weekly-brief/>
- 最新一期：<https://maisukrajima.github.io/github-weekly-brief/report-20261108.html>

## 归档

| 周次 | 日期 | 项目数 | 报告 |
| --- | --- | --- | --- |
| W45 | 2026-11-08 | 41 | [report-20261108.html](report-20261108.html) |
| W44 | 2026-11-01 | 38 | [report-20261101.html](report-20261101.html) |
| W43 | 2026-10-25 | 34 | [report-20261025.html](report-20261025.html) |
| W42 | 2026-10-14 | 31 | [report-20261018.html](report-20261018.html) |

## 说明

- 数据源：GitHub REST API 搜索 `created:>=YYYY-MM-DD` 且按 stars 排序，窗口为执行日往前 7 天。
- 星数与语言以 API 实际返回为准；报告为单文件 HTML，内联 CSS/JS、无外部依赖，可离线双击打开。
- 卡片为服务端渲染（无 JS 也能读全文），`<details>` 原生折叠，支持键盘与移动端。
- 每期取数后会人工剔除「破解安装包 / 投毒仓库 / 外挂」类项目（识别信号：语言为空、星数整齐、topics 带安装包词）。
- 由 WorkBuddy + github-weekly-brief 流程自动生成并归档。
