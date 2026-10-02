# HW1 - Static Visualization using D3.js

## 基本資料

課程：資料分析與視覺化應用  
作業：HW1 - Static Visualization using D3.js  
姓名：姚博智  
學號：414226307

---

## 1. 專案主題

### 台灣人口連續 32 個月負成長

本專案使用 D3.js 建立靜態資料視覺化，
比較 2026 年 8 月台灣部分縣市的人口年增減率。

截至 2026 年 8 月底，
台灣總人口為 23,224,721 人，
較去年同期減少 103,622 人，
年增減率為 -0.44%。

---

## 2. 視覺化目的

雖然台灣整體人口呈現負成長，
但不同縣市的人口變化並不相同。

因此本專案使用發散型水平長條圖，
以 0% 作為基準線：

- 正值代表人口增加
- 負值代表人口減少
- 長條長度代表人口增減幅度

藉此讓使用者快速比較不同縣市的人口變化。

---

## 3. 使用技術

- HTML
- CSS
- JavaScript
- D3.js v7
- CSV

---

## 4. 資料內容

| 縣市 | 人口年增減率 |
|---|---:|
| 連江縣 | +0.32% |
| 桃園市 | +0.25% |
| 新竹縣 | +0.22% |
| 彰化縣 | -1.07% |
| 嘉義縣 | -1.16% |
| 金門縣 | -1.55% |

---

## 5. 操作流程

1. 建立 HTML 網頁。
2. 使用 CSV 儲存人口資料。
3. 使用 D3.js 的 `d3.csv()` 載入資料。
4. 使用 `scaleLinear()` 建立人口增減率比例尺。
5. 使用 `scaleBand()` 建立縣市排列。
6. 使用 SVG `rect` 繪製水平長條圖。
7. 使用不同顏色區分人口增加與人口減少。
8. 加入數值標籤與 0% 基準線。
9. 將專案上傳至 GitHub。
10. 使用 GitHub Pages 發布網站。

---

## 6. 專案執行

使用 VS Code 開啟專案後，
透過 Live Server 執行 `index.html`。

或直接使用 GitHub Pages 開啟。

---

## 7. GitHub

Repository：

https://github.com/yao911001/1151VIS-HW1-414226307-BoZhiYao

GitHub Pages：

https://yao911001.github.io/1151VIS-HW1-414226307-BoZhiYao/

---

## 8. 執行結果

<img width="1206" height="2622" alt="image" src="https://github.com/user-attachments/assets/cb68d90d-d750-468b-a403-f4909057de3a" />

<img width="1206" height="2622" alt="image" src="https://github.com/user-attachments/assets/64d0827f-b23e-4064-ad60-2ce5aa2bda76" />

---

## 9. 資料來源

- 中華民國內政部戶政司
- 聯合新聞網人口相關新聞
