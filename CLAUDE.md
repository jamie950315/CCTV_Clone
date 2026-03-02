# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## 專案結構
此專案為單一頁面的純前端靜態網站。
- 專案根目錄下主要代碼位於 `szdh2023/`：
  - `szdh2023/index.html`：系統進入點。
  - `szdh2023/assets/`：存放各式靜態資源與樣式檔案（包含 CSS、JS、圖片等）。

## 開發與測試命令
- **本機預覽**：由於無任何複雜的構建流程，你可以直接用瀏覽器開啟 `index.html`。
- 若需要透過本機伺服器查看效果：
  ```bash
  python3 -m http.server 8000
  ```
  啟動後，開啟瀏覽器並訪問 `http://localhost:8000/szdh2023/`。
