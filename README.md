# Workout HUD (運動專注儀表板)

專為「做二休二」受限器材（彈力繩 + 門擋錨、可調壺鈴、健力腳踏車）設計的極簡 100vh 運動計時與進階追蹤應用。

## 特色與技術亮點

1. **零外部依賴 (Zero Dependency)**：純單一 `index.html` 檔案（HTML5 + 原生 CSS + Vanilla JavaScript），可直接在任何電腦/手機瀏覽器雙擊開啟，或加到手機主畫面（PWA 體驗）。
2. **滾動狀態機 (Rolling Queue)**：擺脫固定日曆死板綁定；完成 A 自動跳 B，完成 B 自動跳 A，中間因排班調休停頓幾天都不影響進度，頂部支援一鍵手動覆蓋。
3. **極簡點擊記錄 (Zero Keyboard Input)**：運動中不打字，自動帶出上次成績與目標次數；加減鍵加大至 44px 方便手汗手震時點擊，輸入框字體鎖死 16px 防止 iOS Safari 自動放大。
4. **絕對時間差防漂移 (Timestamp Delta + Wake Lock)**：計時器在手機休眠或切換背景時不漂移；超組休息倒數完畢自動合成嗶聲與觸覺振動，免開外掛計時器。
5. **Stuart McGill 脊柱核心黃金三角**：
   - **Day A**：抗伸展（死蟲式 / 彈力繩前推）避免與 Day B 壺鈴 RDL 產生腰椎剪力疲勞疊加。
   - **Day B**：抗旋轉（門錨 Pallof Press）。
6. **Zone 2 呼吸節奏引導 (Breathing Circle)**：內建 1:1 鼻吸鼻呼動態光環（4秒吸、4秒呼），專注粒線體心肺恢復與副交感神經修復。
7. **本地優先 (Local-First)**：所有數據長存瀏覽器 `localStorage`，支援一鍵 JSON 備份匯出與還原。

## 快速開始

直接在瀏覽器開啟同目錄下的 [index.html](file:///c:/Users/join6/AI-Agent/100_Todo/projects/workout-hud/index.html) 即可開始使用。
