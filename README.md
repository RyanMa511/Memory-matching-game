### 1. HTML結構

- 創建網頁標題為 "Memeory matching game"
- 在網頁中添加主要區塊，包含16個可點擊的網格
- 在頁腳部分顯示遊戲狀態信息

### 2. CSS樣式

- 為所有元素設定字體為 Arial
- 為網格設定灰色背景和點擊指示符
- 網格區塊居中顯示，每個網格項目均勻分布

### 3. Javascript邏輯

- 初始化：設定點擊次數從 0 開始
- 玩家點擊：
    - 若點擊次數為偶數，網格翻動其中一個網格
    - 若點擊次數為奇數，網格翻動第二個網格
    - 若點擊的兩網格是相同的，然後網格會保持翻動後狀態
    - 若點擊的兩網格是不相同的，然後網格會回到翻動前狀態
- 檢查是否獲勝：
    - 全部網格都保持翻動後狀態為獲勝條件
    - 滿足條件時顯示勝利者
- 遊戲結束：
    - 當出現獲勝者或所有網格被點擊後，顯示結果
    - 提供重新開始遊戲的選項
