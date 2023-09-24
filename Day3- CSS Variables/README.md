# JS30-challenge

挑戰 JavaScript30 題庫

### 第三天

#### 目的:製作能調整圖片外框邊距、顏色、模糊度的調整器

#### 自行解題

思路:

1.分別寫調整邊距 顏色 模糊度 的函式

2.加上事件監聽

#### 正解:

1.設定 CSS 變數

2.寫觸發函式

3.加入事件監聽

#### 比較:

1.正解使用 css 變數來減少重複定義，增加可讀性和維護性。

2.正解使用 change 和 mousemove 來做事件監聽，而我使用 input，差別在 change 需要當焦點轉移才會觸發，input 只需要有值改變接會變動。

### 學習到的技術:

1.CSS 變數使用

2.input 和 change 事件的差別

##### 參考網站

- blur()
  https://developer.mozilla.org/en-US/docs/Web/CSS/filter-function/blur
