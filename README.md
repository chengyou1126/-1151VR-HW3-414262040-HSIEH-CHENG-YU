# 1151VR-HW3

## 1. 專案截圖
<img width="865" height="442" alt="image" src="https://github.com/user-attachments/assets/ebcc8c42-bc43-4ed1-a718-005aebba3d70" />



## 2. GitHub 連結
https://github.com/chengyou1126/-1151VR-HW3-414262040-HSIEH-CHENG-YU/blob/main/README.md

## 3. YouTube 連結
https://youtu.be/uMi0GjY-gZg


## 4. 說明製作流程和相關操作
* **場景建置**：建立一個 Unity 2D 專案，匯入輪盤與指針素材，將背景圖片的圖層設為最底層 (Order in Layer: -1) 避免遮擋輪盤。
* **程式邏輯** (C#)：撰寫控制腳本，設定點擊螢幕時給予初始轉速（rotSpeed = 80），並透過每幀乘以 0.96f 來達成自然減速至停止的效果。
* **音效對齊**：掛載 AudioSource，設定每旋轉 60 度觸發一次「搭」的音效，並加入 30 度的起始角度補償，讓聲音精準對齊輪盤角度分隔線。
* **手機連動測試**：透過設定 Unity Remote 5 與電腦安裝 iTunes 驅動，成功將畫面串流至手機來進行實機遊玩測試。
