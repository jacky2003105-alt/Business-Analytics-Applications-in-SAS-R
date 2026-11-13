# 商業分析：R｜課程筆記

第 1～8 章的課程筆記網站（純靜態 HTML，可直接用 GitHub Pages 發佈）。

- `index.html`：課程介紹、使用說明、環境設定、資料下載
- `ch01.html`～`ch08.html`：各章筆記與 Concept Check
- `assets/`：樣式、互動功能、搜尋索引、KaTeX、R 產生的圖
- `data/`：課堂資料檔

發佈：把這個資料夾的內容推到 GitHub repo，Settings → Pages → Deploy from branch（main / root）。
內容由 `網站原始檔/` 的 R Markdown 產生：`python3 build.py --all`（需要 R 與 knitr）。
