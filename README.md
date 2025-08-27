
# 照顧計畫敘述產生器（靜態網頁版，免安裝）

這是單檔前端工具，無後端、無資料庫。放到 GitHub 後用 Vercel/Netlify 部署即可。

## 使用者操作
1. 勾選選項 → 右側即時產生敘述。
2. 按「複製文字」，貼到 Word 照顧計畫。

## 結構
- 只有 `index.html` 與此說明文件。
- 所有樣式與邏輯都在 `index.html`（方便維護、部署快速）。

## 上傳到 GitHub
1. 新增一個 repository（例如 `careplan-generator`）。
2. 把 `index.html` 與 `README.md` 上傳到 repo 根目錄。
3. 之後要更新內容，只要改 `index.html` 再 push 即可。

## 部署到 Vercel
1. 到 <https://vercel.com> 用 GitHub 登入。
2. New Project → 選你的 repo。
3. Framework 選 **Other** 或讓 Vercel自動偵測（這是純靜態網頁）。
4. 建置完成後會給你一個網址（例如 `https://careplan-generator.vercel.app`）。

## 自訂與擴充
- 在 `index.html` 最下方的 `<script>` 內可調整選項常數（HOSPITALS、DISEASES 等）。
- 可繼續加入多段模板（生活史、家庭支持、風險與照護問題、目標、服務計畫、追蹤）並以相同方式組句。
- 若想要 Word 檔匯出，可再加入 docx 套件（如 PizZip + docxtemplater）或 serverless 函式。

---

Made for quick internal use.
