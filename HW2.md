### 甘特圖
![gantt](git用.png)
```mermaid
gantt
    title 甘特圖練習

    section 計畫籌備階段
    研擬計畫:a1,2021-10-03,1d
    任務分配:a2,after a1,4d
    取得硬體:a3,after a1,17d
    程式開發:a4,after a2,70d
    安裝硬體:a5,after a3,10d
    程式測試:a6,after a4,30d
    撰寫使用手冊:a7,after a5,25d
    轉換檔案:after a5,20d
    系統測試:a8,after a6,25d
    使用者訓練:after a7,20d
    使用者測試:after a8,25d
```

