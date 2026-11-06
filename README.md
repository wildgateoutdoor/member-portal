# 入野門會員中心（前台）

網址：https://member.wildgateoutdoor.com/

**會員頁只在這個專案維護**：`index.html`（會員頁）、`privacy.html`（隱私權政策）、`images/`（logo）。

會員系統的其他部分在 [`wildgateoutdoor/hiking-dashboard`](https://github.com/wildgateoutdoor/hiking-dashboard)：

- 後台「會員管理」：`index.html`（網址 https://admin.wildgateoutdoor.com/）
- 資料庫與後端（Supabase）：`supabase/migrations/`、`supabase/functions/member-api/`
- 設定與金流設計說明：`MEMBER_SETUP.md`

改會員頁時如果後端 API 格式也要變，兩個專案要一起改、一起上線。
