# my-cat-chart（靜態圖表頁）

顯示 my cat 血糖線圖的靜態網頁，可放上 GitHub Pages。只有網頁和資料，不含任何帳號密碼。

- `index.html`：上方下拉選單選擇 CSV，用 Chart.js 畫線圖
- `data/*.csv`：血糖資料（`date,value,isHigh,isLow,trend`）
- `data/files.json`：下拉選單的檔名清單

資料由私有專案 `my-cat` 的 `bun run export` 產生並同步過來，不要手動編輯 `files.json`。

## 放上 GitHub Pages

1. 把這個資料夾推到 GitHub（公開 repo）
2. repo 的 Settings → Pages → Source 選 `Deploy from a branch`，分支選 `main`、資料夾選 `/ (root)`

## 本機預覽

需要用網頁伺服器開啟（直接雙擊 index.html 讀不到資料），例如：

```bash
bunx serve .
```
