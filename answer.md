# 第4次作業-作業-HW4
>
>學號：111111113
><br />
>姓名：張昕妤
><br />
>作業撰寫時間：40 (mins，包含程式撰寫時間)
><br />
>最後撰寫文件日期：2023/12/10
>

本份文件包含以下主題：(至少需下面兩項，若是有多者可以自行新增)
- [x] 說明內容
- [x] 個人認為完成作業須具備觀念

## 說明程式與內容
1.先clone老師的倉庫<br>
2.新增index.html<br>
3.body部分新增三個div區塊，分別擁有不同的類別class，分別呈現連結、主要內容和功能區塊。<br>
```csharp
<body>
    <div class="menu">
        <ul>
            <li>連結1</li>
            <li>連結2</li>
        </ul>
    </div>
    <div class="contentContainer">
        內容區塊
    </div>
    <div class="functionContainer">
        內容區塊
    </div>
</body>
```
4.在head輸入<br>
```csharp
<style>
        .menu {
            float: left;
            background-color: #FF0000;
            min-width: 30%;
            border: 1px solid blue;
            box-sizing: border-box;
        }

        .contentContainer {
            float: right;
            background-color: #00FFFF;
            min-width: 50%;
            border: 1px solid blue;
            box-sizing: border-box;
        }

        .functionContainer {
            float: right;
            background-color: #00FFFF;
            min-width: 20%;
            border: 1px solid blue;
            box-sizing: border-box;
        }

    </style>
```
5.git commit<br>
6.git push<br>

## 個人認為完成作業須具備觀念
在這次的作業中，這次作業加深了對CSS的佈局和樣式，學習掌握了CSS中的浮動float和盒模型box-sizing的基本概念。浮動用於控制元素在頁面中的位置，而盒模型則是確保元素的寬度和邊框計算的一種控制方式。這兩者的運用使得網頁佈局更靈活，能夠實現三欄式的結構。同時對於CSS樣式的屬性設定，如背景色、最小寬度、邊框等，也是實現設計的重要元素。