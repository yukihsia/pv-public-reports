# Pilot Ventures · 对外市场研究报告

Pilot Ventures 面向 LP、合作方、项目方公开分享的赛道洞察报告。

**站点**：https://yukihsia.github.io/pv-public-reports/

## 已发布报告

- **女性情绪消费与陪伴赛道洞察**（2026-07）
  `./female-emotional-consumption/` — 聚焦 AI 陪伴 + 乙女游戏两条主线，收敛在 4 个具体机会方向。

## 结构

```
pv-public-reports/
├── index.html                              ← landing 首页
├── <report-slug>/index.html                ← 每份报告一个子目录
├── .nojekyll                               ← 禁用 Jekyll 处理
└── README.md
```

## 新增报告的方式

1. 建子目录：`mkdir <report-slug>`
2. 放 HTML：`<report-slug>/index.html`
3. 更新根 `index.html` 里的报告列表
4. `git push` → GitHub Pages 自动 deploy

内容仅供参考，不构成任何投资建议。
