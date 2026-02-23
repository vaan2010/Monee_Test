# Monee

## Google Drive 備份設定

雲端備份已改為使用 Google Drive。使用前請：

1. 前往 [Google Cloud Console](https://console.cloud.google.com/)
2. 建立專案或選擇現有專案（可沿用 Firebase 專案）
3. 啟用「Google Drive API」
4. 建立 OAuth 2.0 用戶端 ID（應用程式類型：網頁應用程式）
5. 在 `index.html` 中將 `GOOGLE_DRIVE_CLIENT_ID` 設為您的 Client ID

登入後會在 Google Drive 自動建立「Monee」資料夾，每次開啟 App 會自動備份一次。

---

## 已知問題 (Known Issues)

- **記帳圓餅圖無法上下滑動**：記帳頁面的圓餅圖有時會發生無法上下滑動的情況，請先等待約一秒後再次滑動即可。

---

## 更新紀錄 (Changelog)

> 每次新增功能或修改時，請在此處加上日期與說明。

### 2025-02-23

- **雲端備份改為 Google Drive**：登入後連結自己的 Google Drive，自動建立「Monee」資料夾存放 JSON 備份檔，每次開啟 App 自動備份一次
- **新增銀行支援**：新增 9 家銀行至 `BANK_DATA`
  - 高雄銀行 (016)
  - 台中銀行 (053)
  - 京城銀行 (054)
  - 瑞興銀行 (101)
  - 華泰銀行 (102)
  - 新光銀行 (103)
  - 板信商業銀行 (118)
  - 將來銀行 (823)
  - LINE Bank (824)
- **建立 README.md**：新增更新紀錄
