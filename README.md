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

![image](https://github.com/ycc17/UML_midterm_report/blob/main/%E7%AF%84%E4%BE%8B%E9%A1%9E%E5%9C%96.jpg)
### 依賴關係
虛線箭頭表示：

![依賴關係](https://github.com/ycc17/UML_midterm_report/assets/91513230/2c672e71-aa7a-4b32-b8e1-e26b21d4325f)
### 繼承關係
實線空心三角形箭头表示：

![繼承關係](https://github.com/ycc17/UML_midterm_report/assets/91513230/5298b90c-4a29-4d63-a3fe-794036c140f6)
### 實現關係
虛線空心三角形箭头表示：

![實現關係](https://github.com/ycc17/UML_midterm_report/assets/91513230/56de1579-dc1d-437e-a888-42fad93b22c0)
### 關聯關係
實線表示：

![關聯關係](https://github.com/ycc17/UML_midterm_report/assets/91513230/9b69e15c-a51f-4038-b10e-d2ac4331c09d)
### 組合關係
實線黑色菱形表示：

![組合關係](https://github.com/ycc17/UML_midterm_report/assets/91513230/fe63587e-5bc9-4813-b585-96d0bbe565c6)
### 聚合關係
實線空心菱形表示：

![聚合關係](https://github.com/ycc17/UML_midterm_report/assets/91513230/191bd031-f73b-4941-a9ac-60416bb36226)

## 類圖實作
![image](https://github.com/ycc17/UML_midterm_report/blob/main/%E6%9C%9F%E4%B8%AD%E9%A1%9E%E5%9C%96.jpg)

## UML物件圖
顯示了某一時刻的一組物件及它們之間的關係。物件圖可被視為類別圖的實例,用來表達各個物件在某一時刻的狀態。

![對象圖範例](https://github.com/ycc17/UML_midterm_report/assets/91513230/c2984313-9e1b-4203-ab31-4e8cf933ca32)

### 物件圖說明
* stu 實例名稱，Student 所屬類別。
1. 第一行：物件名稱
2. 第二行：實例屬性具體值
* stu:Student 標準表示法
* :Student 匿名表示法
* stu 省略類別名表示法
## 物件圖實作
![image](https://github.com/ycc17/UML_midterm_report/blob/main/UML%E5%B0%8D%E8%B1%A1%E5%9C%96.jpg)

#### 參考文章
* https://zhuanlan.zhihu.com/p/553581694
