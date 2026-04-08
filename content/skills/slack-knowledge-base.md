---
title: Slack 知識庫系統
tags:
  - skill
  - slack
  - knowledge-base
---

# Slack 知識庫系統

## 功能說明

AI 自動抓取網頁內容、解析分類、發布到 Slack 知識庫頻道。

## 工作流程

1. **📥 輸入** - 收到 URL
2. **🔍 抓取** - 使用 Jina Reader 提取內容
3. **🧠 AI 分類** - 自動判斷類型
4. **📤 發布** - 發送到對應頻道

## 分類架構

```
📚 #knowledge-base（總入口）
   ├── #kb-ai-news（AI 產業新聞）
   ├── #kb-tutorials（教程/技術文）
   ├── #kb-tools（工具介紹）
   ├── #kb-research（研究論文）
   └── #kb-other（其他）
```

## 快捷指令

| 指令 | 動作 |
|------|------|
| `存到知識庫 {url}` | 直接處理並發布 |
| `幫我收藏 {url}` | 處理並發布 |
| `分類這篇 {url}` | 分析分類但不發布 |

---

*分類：系統與整合*
