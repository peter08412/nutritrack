NutriTrack PWA

部署：將此資料夾內所有檔案上傳至支援 HTTPS 的靜態網站空間（例如 GitHub Pages 或 Cloudflare Pages）。使用 iPhone Safari 開啟網站，點分享→加入主畫面。

功能：每日熱量/蛋白質、手動紀錄、編輯刪除、日期歷史、目標、照片預覽、JSON 備份還原、離線快取。

重要：AI 自動食物辨識尚未實作；照片目前只供手動參考。資料儲存在瀏覽器 localStorage，請定期匯出備份。不能直接開啟本機 file:// 檔案就期待 PWA 離線安裝生效，需 HTTPS 部署。

第二版新增每日維持熱量、按日期輸入有氧與重訓消耗、熱量赤字／盈餘估算。
