---
title: Slack 整合技能
tags:
  - skill
  - slack
  - integration
---

# Slack 整合技能

## 功能說明

讓雷姆能夠透過 OpenClaw 與 Slack 頻道互動。

## 主要功能

| 功能 | 說明 |
|------|------|
| 發送訊息 | 傳送文字、圖片到頻道或 DM |
| 頻道管理 | 列出頻道成員、查詢頻道資訊 |
| Emoji 反應 | 添加/移除 emoji 反應 |
| 釘選訊息 | Pin/Unpin 重要訊息 |

## 連線模式

### Socket Mode（推薦）
WebSocket 為基礎的即時連線，不需要公開 Webhook。

### HTTP Events API
傳統 Webhook 模式，需要公開可訪問的端點。

## 所需 Token

- **Bot Token** (`xoxb-...`)
- **App Token** (`xapp-...`)

## 相關連結

- 技能位置：`~/.openclaw/workspace/skills/slack-integration/`
- 官方文檔：[Slack API](https://api.slack.com/)

---

*分類：系統與整合*
