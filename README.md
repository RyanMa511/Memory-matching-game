### 1. HTML結構
- 創建網頁標題為 "Memeory matching game"
- 在網頁中添加主要區塊，包含16個4x4可點擊的網格
- 在頁腳部分顯示遊戲狀態信息
- 創建一個按鈕

### 2. CSS樣式
- 為所有元素設定字體為 Arial
- 為網格設定灰色背景和點擊指示符
- 網格區塊居中顯示，每個網格項目均勻分布
- 把按鈕設定為"重新開始"

### 3. Javascript邏輯
- 初始化:
    - 當遊戲開始時隨機編配網格
- 玩家配對：
    - 若點擊一次，網格翻動其中一個網格
    - 若點擊第二次，網格翻動第二個網格
    - 若點擊的兩網格是不相同的，然後網格會回到翻動前狀態
    - 若點擊的兩網格是相同的，然後網格會保持翻動後狀態
    - 當玩家點擊多次但但還沒完成所有的配對便顯示出"愚蠢的人類"
- 檢查是否獲勝:
    - 全部網格都保持翻動後狀態為獲勝條件
    - 滿足條件時顯示勝利
- 遊戲結束：
    - 當出現獲勝，顯示結果
    - 提供重新開始遊戲的按鈕
    - 當點擊重新開始遊戲的按鈕重置所有網格

### 4. 添加進階功能，例如
當玩家點擊多次但還沒完成所有的配對便顯示出"愚蠢的人類"
