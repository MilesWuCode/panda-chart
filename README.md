# panda-chart（靜態圖表頁）

- `index.html`：上方下拉選單選擇 CSV，用 Chart.js 畫線圖
- `data/*.csv`：血糖資料（`date,value,isHigh,isLow,trend`）
- `data/files.json`：下拉選單的檔名清單

## 放上 GitHub Pages

1. 把這個資料夾推到 GitHub（公開 repo）
2. repo 的 Settings → Pages → Source 選 `Deploy from a branch`，分支選 `main`、資料夾選 `/ (root)`
