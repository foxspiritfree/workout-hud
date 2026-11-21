# Workout HUD (運動專注儀表板)

專為「做二休二」受限器材（彈力繩門錨、可調壺鈴、健力腳踏車）與居家雙樓層動線設計的極簡 100vh 運動計時與進階追蹤應用。

## 特色與技術亮點 (v1.2.0)

1. **空間動線解耦 (Floor-Based Routing)**：
   - 預設「2F 樓上集中（彈力帶門錨 ＋ 墊上核心）➔ 移動至 1F 樓下（可調壺鈴 ＋ 腳踏車 Zone 2）」，消除上下樓梯折返跑的物理與心理摩擦。
   - 支援卡片 `▲ / ▼` 上下自訂排序，持久儲存於本地。
2. **底部常駐懸浮計時器 (Bottom Sticky Floating HUD)**：
   - 打勾完成任何一組後，計時器從底部平滑滑出，大字體顯示、單手即可操作 `-15s` / `+15s` / `跳過`，不隨頁面滾動消失。
3. **組間休息彈性自訂**：
   - 每個動作提供 `[30s] [45s] [60s] [90s] [120s]` 快捷點選，個別記憶不同肌群的恢復節奏。
4. **實體器材點選器 (Hardware-Aligned Selectors)**：
   - 可調壺鈴 4 段重量（12 / 16 / 20 / 24 kg 快捷點選，可自訂）。
   - 彈力帶 4 強度（極輕/輕/中/重）× 7 環設計（R1 ~ R7 快速切換）。
5. **神經動作外部焦點 (External Focus Cues)**：
   - 關注外在環境效果或參照物（如推穿地板、手肘往牆壁推、屁股撞關身後門），消除內部意識干預引發的動作僵硬與代償。
   - 每張卡片配備常駐口訣 Badge 與 `ℹ️ 外部焦點與要領` 折疊面板。
6. **做二休二滾動狀態機 (Rolling Queue)**：
   - 擺脫固定日曆綁定；完成 A 自動跳 B，完成 B 自動跳 A，支援頂部手動覆蓋與雙重進階（Double Progression）達標提示。
7. **絕對時間差防漂移 (Timestamp Delta + Wake Lock)**：
   - 手機休眠不漂移，倒數完畢自動以 Web Audio API 合成音訊並觸發震動。
8. **本地優先 (Local-First)**：
   - 純單一 `index.html` 零外部依賴，數據長存瀏覽器 `localStorage`，支援 JSON 一鍵匯出與備份還原。

## 快速開始

直接在瀏覽器開啟同目錄下的 [index.html](file:///c:/Users/join6/AI-Agent/100_Todo/projects/workout-hud/index.html) 即可開始使用。
線上展示版：[https://foxspiritfree.github.io/workout-hud/](https://foxspiritfree.github.io/workout-hud/)
