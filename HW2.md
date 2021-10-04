### 甘特圖
```mermaid
gantt
    title 甘特圖練習

    section 計畫籌備階段
    研擬計畫:a1, 2021-10-04, 1d
    任務分配:a2,after a1,4d
    section 硬體開發階段
    取得硬體:a3,after a1,17d
    安裝硬體:a5,after a3,10d
    撰寫使用手冊:a7,after a5,25d
    section 軟體開發階段
    程式開發:a4,after a2,70d
    程式測試:a6,after a4,30d

