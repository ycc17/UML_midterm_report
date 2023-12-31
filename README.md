# **詳解UML類別圖&物件圖**
## UML 類別圖
描述類別、介面、協作及他們之間的關係的圖。顯示系統中類別的靜態結構。
## 有什麼作用？
描述軟體系統的靜態結構- 對系統的詞彙建模- 對簡單協作建模- 對邏輯資料庫模式建模
## 類別圖說明
- 類別名為斜體則為抽象類別類別
- 方法為斜體則為抽象方法

1. 第一行：類別名稱
2. 第二行：類別屬性
3. 第三行：類別方法

- 類別/屬性/方法說明：
1. '-' 表示私有(private)
2. ' #'表示保護(protected)
3. '+'表示公開(public)

## 類圖實作
![image](https://github.com/ycc17/UML_midterm_report/blob/main/image/%E6%9C%9F%E4%B8%AD%E9%A1%9E%E5%9C%96.drawio.png)

### 依賴關係
虛線箭頭表示：

![image](https://github.com/ycc17/UML_midterm_report/blob/main/image/%E4%BE%9D%E8%B3%B4.png)

### 繼承關係
實線空心三角形箭头表示：

![image](https://github.com/ycc17/UML_midterm_report/blob/main/image/%E7%B9%BC%E6%89%BF.png)

### 實現關係
虛線空心三角形箭头表示：

![image](https://github.com/ycc17/UML_midterm_report/blob/main/image/%E5%AF%A6%E7%8F%BE.png)
### 關聯關係
實線表示：

![image](https://github.com/ycc17/UML_midterm_report/blob/main/image/%E9%97%9C%E8%81%AF.png)
### 組合關係
實線黑色菱形表示：

![image](https://github.com/ycc17/UML_midterm_report/blob/main/image/%E7%B5%84%E5%90%88.png)
### 聚合關係
實線空心菱形表示：

![image](https://github.com/ycc17/UML_midterm_report/blob/main/image/%E8%81%9A%E5%90%88.png)
## UML物件圖
顯示了某一時刻的一組物件及它們之間的關係。物件圖可被視為類別圖的實例,用來表達各個物件在某一時刻的狀態。

### 物件圖實作
![image](https://github.com/ycc17/UML_midterm_report/blob/main/image/UML%E7%89%A9%E4%BB%B6%E5%9C%96.drawio.png)

### 物件圖說明
* stu 實例名稱，Student 所屬類別。
1. 第一行：物件名稱
2. 第二行：實例屬性具體值
* stu:Student 標準表示法
* :Student 匿名表示法
* stu 省略類別名表示法

## 參考文章
* https://zhuanlan.zhihu.com/p/553581694
