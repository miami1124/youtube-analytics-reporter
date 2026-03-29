# 📊 YouTube 雙週報自動化
**YouTube Analytics API × n8n × Google Sheets × LINE**

---

## 背景與痛點

媒體公司攝影中心每兩週需要彙整 YouTube 頻道表現數據，人工從後台逐一複製觀看數、分類整理、填入報表，耗時且容易出錯。

## 解決方案

1. 接收指定日期區間，自動對應正確月份報表
2. 抓取該區間所有影片的 YouTube Analytics 數據
3. 依橫式、短影音分類分別統整
4. 自動填入 Google 表單，完成後 LINE 通知

## 實際成果

- ✅ 雙週報從人工作業改為全自動，大幅節省統計時間
- ✅ 支援橫式影片、短影音分類分別計算
- ✅ 目前於媒體公司內部實際使用中

## 技術棧

`n8n` `YouTube Analytics API` `Google Sheets` `OpenAI` `LINE Messaging API` `Webhook`

---
*Built by Sam｜AI Automation Engineer*
