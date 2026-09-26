# 桃太妹種單字 V4

手機優先的個人英文單字卡網站。

## 部署
將此資料夾整包部署至 Vercel，Framework Preset 選 Other，Build Command 留空，Output Directory 留空／根目錄即可。

## 更新單字
主要單字資料目前內嵌於 index.html 的 `window.VOCABULARY` 陣列。新增單字後，更新 `sw.js` 內 CACHE 名稱版本，以避免舊快取。

## 個人紀錄
「會／模糊／不會」保存在瀏覽器 LocalStorage，不會上傳伺服器，也不會跨裝置同步。
