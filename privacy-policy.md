# Foodie Map 隱私權政策

最後更新：2026-06-22

## 1. 蒐集的資料

我們蒐集以下資料以提供服務：

| 資料類型 | 來源 | 用途 |
|---|---|---|
| 位置（使用中） | 裝置 GPS | 搜尋附近餐廳 |
| 帳號識別（UID） | Supabase Auth | 識別登入使用者 |
| 電子郵件 | 使用者於登入時提供 | 驗證身份 |
| 收藏 / 吃過紀錄 | 使用者主動輸入 | 個人化推薦 |
| 料理偏好 / 口味設定 | 使用者主動輸入 | 個人化推薦 |

## 2. 不蒐集的資料

- 我們**不蒐集**廣告識別碼（IDFA / IDFV）。
- 我們**不追蹤**跨 App 行為。
- 我們**不販售**任何使用者資料。

## 3. 第三方服務

- **Supabase**：後端資料庫與認證服務，資料儲存於 Supabase 雲端。[隱私權政策](https://supabase.com/privacy)
- **Google Places API**：餐廳搜尋，透過我們的伺服器轉呼叫（API Key 不進 App）。[隱私權政策](https://policies.google.com/privacy)
- **Google Sign-In / Apple Sign-In**：第三方登入，僅取得帳號識別。
- **TelemetryDeck**：匿名化使用分析（使用雜湊化 ID，無法反推個人身份）。[隱私權政策](https://telemetrydeck.com/privacy/)

## 4. 資料儲存與安全

所有使用者資料儲存於 Supabase，並以 Row Level Security (RLS) 確保每位使用者僅能存取自己的資料。

## 5. 帳號刪除

你可以隨時在 App 的「個人 → 刪除帳號」中永久刪除帳號。刪除後，所有相關資料（收藏、紀錄、偏好）將立即永久清除，無法復原。

## 6. 聯絡我們

有任何隱私問題，請來信：hello@<app-domain>
