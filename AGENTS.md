# AGENTS.md

## 專案

兒童遊戲樂園 — 三個網頁遊戲（記憶翻牌、打地鼠、點點樂）整合在單一 HTML 檔案中。

## 關鍵檔案

- `games.html` — 主遊戲頁面（所有遊戲 + 首頁 + 說明）
- `config.js` — 設定檔，請編輯 `USER_NAME` 和 `USER_ID`
- `遊戲說明.md` — 遊戲規則說明文件

## 開啟方式

直接用瀏覽器打開 `games.html` 即可，無需伺服器。

## 開發備註

- 所有遊戲共用同一份 HTML/CSS/JS
- `config.js` 需與 `games.html` 放在同一目錄
- 遊戲切換使用頁籤（tab）方式
