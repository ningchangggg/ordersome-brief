# 來點什麼 創作者拍攝指南（手機版）

來點什麼 KOL 拍攝企劃 #1–#5 與創作者合作提案整合成的手機版單頁，照片已內嵌於 HTML，單一檔案即可離線瀏覽。

公開網址：https://ningchangggg.github.io/ordersome-brief/

直接開到某一篇：網址後面加 `#ep1`～`#ep5`，例如 https://ningchangggg.github.io/ordersome-brief/#ep3 （粉漿蛋餅篇）。

- `index.html` — 產出的網頁（勿直接手改，會被 build.sh 覆蓋）
- `build.sh` / `wrap.py` — 由 iCloud「◼︎來點什麼/_來點什麼創作者主題」資料夾中的成品檔重新產生 index.html
- 已設定 `noindex` 與 `robots.txt`，有連結的人可以打開，但不會被搜尋引擎收錄

更新流程：改好 iCloud 的成品檔 → `./build.sh` → `git commit -am "更新" && git push`
