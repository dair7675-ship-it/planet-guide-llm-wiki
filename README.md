# 星球小百科｜太陽系五顆行星 LLM Wiki 與教學 HTML 簡報

這是一份全新、獨立於「網頁製作入門」的第十週作業初版。內容取自 NASA Science 的五篇官方 Facts，整理成繁體中文 Wiki 與 10 頁互動簡報。

## 直接開啟
- `index.html`：10 頁 HTML 教學簡報，上一頁／下一頁及左右方向鍵。
- `wiki/index.html`：可瀏覽的 Wiki，含五個行星介紹與來源入口。
- `raw/`：五篇 NASA Facts 的繁中摘要筆記。
- `wiki/sources/`：五篇來源條目的 Markdown 與網頁。
- `wiki/concepts/`：五篇概念條目的 Markdown 與網頁。
- `wiki/log.md`：本地 ingest／編纂記錄。
- `WORKFLOW.md`：Loop / Graph、檢查與反思。
- `CHECKS.md`：本地驗證結果（後續更新）。
- `SUBMISSION.md`：可直接修改的繳交草稿。

## GitHub Pages 發布
1. 建立新的 Public Repository，建議 `planet-guide-llm-wiki`。
2. 解壓後，**把所有內容檔案與資料夾上傳到儲存庫根目錄**，而不是上傳 ZIP。
3. Settings → Pages → Deploy from a branch → main / (root) → Save。
4. 打開 `https://你的帳號.github.io/planet-guide-llm-wiki/`，再點 `查看 LLM Wiki`。

## 資料來源
五篇皆為 NASA Science：水星、金星、地球、火星、木星 Facts；各來源 URL 參見 `manifest.json` 與 Wiki 卡片。

## 對 ingest 的說明
本專案已把 5 篇 NASA 來源**以本地 Markdown 條目方式納入自建 Wiki**。這不同於某一個第三方 LLM Wiki 平台的自動匯入流程；是否完全符合課堂 ingest 定義仍須依教師說明。

## 教學使用
NASA 原文不直接複製全文，本站改寫重點並保留來源連結。內容為教學摘要，不是 NASA 官方譯本。


## 視覺風格更新（白底科普教學版）

改為白色教材背景、深藍標題、五顆行星的個別色彩、清楚的淺色導覽按鈕。簡報與 Wiki 頁面共用 `style.css`，保留原本的十頁內容、Wiki 資料及互動功能。


## 簡報操作（左右側箭頭版）
- 簡報左右兩側的 ‹ / › 按鈕可切換上一頁與下一頁；第一頁的上一頁箭頭、最後一頁的下一頁箭頭會停用。
- 也可以使用鍵盤左右方向鍵切換。
- 頁碼及進度條仍保留在簡報底部，沒有底部翻頁按鈕。
- 本次只修改導覽位置及樣式，保留原有 NASA 來源、五個 Wiki 主題、十頁教學內容及測驗功能。
