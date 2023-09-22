# JS30-challenge

挑戰 JavaScript30 題庫

### 第一天

#### 目的:製作一個按鍵盤按鍵可以播放打擊音效的電子鼓

#### 自行解題

思路:

1.訂定 keydown 要改變 class 的函式

2.訂定 keyup 要改變 class 的函式

3.將兩個函式綁上事件監聽

#### 正解:

1. 設定音效播放 移除 css 樣式的函式

2. querySelectorAll 取得所有的 key

3.forEach 將每個 key 加上 transitionend 的監聽 4.監聽 keydown

#### 比較:

1.正解的方式將特定樣式的移除和播放音訊的邏輯分開 容易理解和維護

2.使用 Array.from 和 forEach 循環來處理按鍵元素 更彈性和可擴展性

##### 參考網站

https://www.w3schools.com/jsref/dom_obj_audio.asp
