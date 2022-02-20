# PTT 熱門文章爬蟲 - 根據 推,噓,→ 數加總並用Line Notify傳文章
---
## Why I wanna make this project 
1. Google PTT熱門文章發現沒有附上 "推,噓,→"數量
2. 一般爬蟲 PTT 教學因只根據 "推" 數量導致推噓相抵但其實很多人關注的文章被漏掉
3. Google 搜尋到的熱門文章沒有排序
4. Google 搜尋到的熱門文章似乎不是即時的
5. 我用 Line Notify 傳文章給我，比較方便，因有另外一台電腦所以不佔效能
---

## Steps
* Step1. 選擇PTT版，及對應的Line群組token
* Step2. get 今日所有文章連結
* Step3. 根據連結 get 每篇文章內容
* Step4. 整理資料/傳送訊息/存成excel(.xlsx)
## 備註
* Line notify 要自行去官方設定
* 因為是自己學習coding所以其實有很多可以加強的地方，比如在傍晚時八卦版會爬不動
