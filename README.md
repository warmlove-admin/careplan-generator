
# CarePlan Generator — 多段落 / 可編輯 / 靜態版

- 單一 `index.html`，無需建置或後端。
- 段落可勾選產生；每段含「勾選項目 + 自由輸入」欄位；右側輸出可編輯。

## 客製
在檔案底部 `<script>` 內調整：
- 各段落選項常數（NEEDS、GOALS、SERVICES、EDU_TOPICS、FOLLOW_TYPES 等）。
- 產文函式 `genSection1~6()` 的模板字句。

## 發佈
直接以 GitHub + Vercel 靜態部署即可。
