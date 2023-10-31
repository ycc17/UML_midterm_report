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
![image](https://github.com/ycc17/UML_midterm_report/blob/main/%E6%9C%9F%E4%B8%AD%E9%A1%9E%E5%9C%96.jpg)

### 依賴關係
虛線箭頭表示：

<img width="410" alt="依賴" src="https://github.com/ycc17/UML_midterm_report/assets/91513230/70eeccda-f718-425f-8fc0-8f18b48bf757">

### 繼承關係
實線空心三角形箭头表示：

<img width="106" alt="繼承" src="https://github.com/ycc17/UML_midterm_report/assets/91513230/7aa96363-c8ba-48fb-9007-80f838129630">

### 實現關係
虛線空心三角形箭头表示：

<img width="111" alt="實現" src="https://github.com/ycc17/UML_midterm_report/assets/91513230/ec4875f7-4e16-491d-9dc8-0efc11f9c46d">

### 關聯關係
實線表示：

<img width="256" alt="關聯" src="https://github.com/ycc17/UML_midterm_report/assets/91513230/f5946158-88ea-4adb-8a22-5eee6b3c1b00">

### 組合關係
實線黑色菱形表示：

<img width="338" alt="組合" src="https://github.com/ycc17/UML_midterm_report/assets/91513230/133bf85d-ba7a-411b-b76e-9b8d4b2b6c6d">

### 聚合關係
實線空心菱形表示：

<img width="305" alt="聚合" src="https://github.com/ycc17/UML_midterm_report/assets/91513230/65ccddc3-b4e2-4a74-bce3-9372500a0f2c">

## UML物件圖
顯示了某一時刻的一組物件及它們之間的關係。物件圖可被視為類別圖的實例,用來表達各個物件在某一時刻的狀態。

### 物件圖實作
![image](https://github.com/ycc17/UML_midterm_report/blob/main/UML%E5%B0%8D%E8%B1%A1%E5%9C%96.jpg)

### 物件圖說明
* stu 實例名稱，Student 所屬類別。
1. 第一行：物件名稱
2. 第二行：實例屬性具體值
* stu:Student 標準表示法
* :Student 匿名表示法
* stu 省略類別名表示法

## 參考文章
* https://zhuanlan.zhihu.com/p/553581694
