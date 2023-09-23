# JS30-challenge

挑戰 JavaScript30 題庫

### 第二天

#### 目的:製作一個時鐘

#### 自行解題

思路:

1.加上旋轉動畫

2.建立時間並每秒偵測

3.將時間改變事件綁定 並改變 css 的旋轉角度

#### 正解:

與我的做題思路相同

#### 比較:

1. ` const minsDegrees = ((mins / 60) * 360) + ((seconds/60)*6) + 90;`
   ` const hourDegrees = ((hour / 12) * 360) + ((mins/60)*30) + 90;`
   能更細微的表達分針及時針每一秒也會緩慢的移動，是我做題沒有考慮到的地方

2.`  setInterval(setDate, 1000);
  setDate();`
直接呼叫可以確保在網頁一開始顯示可以直接顯示正確的時間

### 學習到的技術:

1.transition-timing-function 調整動畫讓停格與動畫效果更接近時鐘跳轉指針的樣式
2.transform-origin 調整動畫的原點

##### 參考網站

- transform-origin
  https://developer.mozilla.org/en-US/docs/Web/CSS/transform-origin
