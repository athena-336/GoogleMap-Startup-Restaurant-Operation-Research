# 餐廳開店指南 | Restaurant Opening Guide: Data Analytics Project

## 專案概述 | Project Overview
本專案為政治大學數據分析課程（NCCU DA）的 Kaggle 專案。透過分析 Bengaluru 地區超過 10,000 間餐廳的資料，進行選址分析、顧客情緒分析與營收預估, 我們旨在為創業者提供一套科學的開店指南，目標是在六個月內協助新餐廳達成評分 4.0 以上的目標, 提升新創餐廳的成功率。

This project is a Kaggle data analytics study for the NCCU DA course. By analyzing data from 10,000+ restaurants in Bengaluru, we provide strategic insights for entrepreneurs to achieve a rating of 4.0+ within six months.

## 核心分析 | Key Analyses
我們針對 **Malleshawram** 地區進行了五大維度的深入分析：
* **餐廳定位 (Rest Type):** 推薦 Casual Dining 與 Cafe 的複合式經營。
* **菜色口味 (Cuisines):** 以 North Indian 為主打菜色。
* **額外服務 (Extra Services):** 驗證發現「訂位服務 (Book Table)」對提升評分與收益有顯著幫助。
* **顧客評論 (Customer Sentiment):** 利用文字雲分析，發現顧客最在乎服務 (Staff)、餐點 (Meal) 與環境 (Ambience)。
* **營收估算 (Revenue Estimation):** 透過 `approx_cost` 建立定價模型，預估獲利門檻。

We conducted in-depth analysis on the **Malleshawram** area across five dimensions:
* **Rest Type:** Recommended a hybrid of Casual Dining & Cafe.
* **Cuisines:** North Indian as the primary cuisine.
* **Extra Services:** Confirmed that "Book Table" service significantly boosts ratings and revenue.
* **Customer Sentiment:** Word cloud analysis shows Staff, Meal, and Ambience are top priorities.
* **Revenue Estimation:** Built a pricing model using `approx_cost` to estimate profit thresholds.

## 技術棧 | Tech Stack
* **Tool:** Python (for data cleaning and analysis)
* **Data Processing:** Missing value handling, field splitting, and text cleaning.
* **Visualization:** Word Cloud (文字雲), Box plots (盒狀圖), Distribution plots.

## 主要發現 | Key Findings
1.  [cite_start]**服務至上:** 員工專業度與態度是高評分的關鍵 [cite: 6, 11]。
2.  [cite_start]**訂位優勢:** 提供訂位服務平均可提升評分約 0.4 分，增加收益約 $73/人 [cite: 9, 27]。
3.  [cite_start]**環境與地點:** 交通便利性（鄰近地鐵、商場）與素食選項是吸引顧客的重要因素 [cite: 11, 15]。

## 團隊成員 | Team Members
* [cite_start]呂宜珊、張嘉妤、黃筠茜、劉語安、許庭瑀 [cite: 1]
