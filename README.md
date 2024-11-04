<p align="center">
  <a href="/">
    <h1 align="center">Google Maps Review Dataset</h1>
  </a>
</p>

![](./img/home.png)

<p align="center">
  <a aria-label="John" href="https://www.facebook.com/profile.php?id=100004293253951">
    <img src="https://img.shields.io/badge/-John%20Lin-blue?style=for-the-badge&logo=facebook&logoColor=white&labelColor=gray&color=blue">
  </a>
  <a aria-label="TSDC" href="https://medium.com/tkustatdc">
    <img alt="" src="https://img.shields.io/badge/-TSDC%20CLUB-blue?style=for-the-badge&logo=&logoColor=white&labelColor=gray&color=blue">
  </a>
  <a aria-label="Follow me" href="https://medium.com/@xcswap.john">
    <img alt="" src="https://img.shields.io/badge/-FOLLOW%20ME-blue?style=for-the-badge&logo=Medium&logoColor=white&labelColor=gray&color=blue">
  </a>
</p>

這個專案提供了來自 Google Maps 的 329 景點的評論資料，非常適合進行文字探勘或自然語言處理（NLP）的相關研究練習。

#### Table of Contents

- [📄 資料集概述](#-資料集概述)
- [📝 資料內容說明](#-資料內容說明)
- [🚀 下載與使用](#-下載與使用)

## 📄 資料集概述

資料來源：Google Maps 景點評論
資料集包含：

- `景點名稱`：資料集名稱為該景點名稱
- `評論發布時間`
- `評論內容`
- `評分`
- `斷詞結果`

資料格式：CSV

## 📝 資料內容說明

資料集主要透過動態爬蟲自動爬取景點評論資料，使用時須注意：

1. 此為範例資料，僅包含評分與評論的重要資訊。
2. 原則上，資料不包含該景點的所有歷史評論或額外資訊（評論數少為例外）。
3. 資料集為 2023 年 6 月爬取，往前收集近一年的評論內容（不會更新資料集）。

## 🚀 下載與使用

下載資料集：直接從 GitHub 儲存庫中下載，或透過以下指令。

```bash
git clone https://github.com/Lin-Wei-Han/google_spotcomment_data.git
```
