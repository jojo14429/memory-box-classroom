# 回憶機關盒 — H5 課室版

GitHub Pages: Settings → Pages → Deploy from a branch → main → /(root)。
整個資料夾（包含 .wasm、.pck、.js、.nojekyll 及 LICENSES.txt）一併上載。
使用網站的 HTTPS 網址開啟，再按「開始遊戲」。不要雙擊本機 index.html。
沒有使用 SharedArrayBuffer／threads，不需要 COOP／COEP 標頭。

本機預覽：python -m http.server 8765 --bind 127.0.0.1
在瀏覽器開啟 http://127.0.0.1:8765/，完成後關閉伺服器。
只使用最新 Chrome／Edge（WebGL 2、WASM、IndexedDB）。

按「全螢幕」用於課室大螢幕；遊戲預設大字模式，可按「大字：開」切回。
進度保存在同一網站／瀏覽器的 IndexedDB，與 EXE 或其他瀏覽器不共用。
無痕模式、清除網站資料、改網站網址可能失去進度；退出前稍候讓存檔同步。
首次需要下載資源；未設定 PWA，不保證離線可重開。

使用者已確認遊戲內容及圖片可公開；未另行核實外部生成服務條款。
勿上載私人存檔、art_source、測試／工具或 Windows EXE。
