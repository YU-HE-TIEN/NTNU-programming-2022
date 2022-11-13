# NTNU-programming-2022
## 111-1師大科技系程式設計  
#### 授課老師：蔡芸琤老師

>歡迎來到 雨禾 程式設計的學習歷程，這裡會記錄111-1修習程式設計的筆記、作業、專題和心路歷程~
***

## 📜目錄
- [關於我](#關於我)
- [課程筆記](#課程筆記)
- [課程作業](#課程作業)
- [相關專題](#相關專題)
- [課程心得](#課程心得)

## 🙋‍♀️關於我
#### 姓名：田雨禾
![image](https://github.com/YU-HE-TIEN/PL/blob/main/self-intro.jpg?raw=true)
>系級：地理系三年級</br>
>我是一位熱愛地理愛爬山的女孩，也喜歡在山上唱歌，歡迎找我一起練程式🥲，也歡迎找我一起爬山!

## 📘課程筆記
- #### week 01(9/8)
  - int型態：整數 / float型態：小數 ／ str型態：'文字'or"文字"
  - bool：布林值（true/false）
  - "="：賦值／"=="：相等
  - 變數：具有名稱和值的記憶體位置
    - 1.使用英文字母命名
    - 2.不能是保留字、內建函數或有空白
    - 3.英文大小寫不同是不同變數
- #### week 02(9/15)
  - dataframe資料格式
  - pd.read.csv -> 讀取csv方法-> 1. 絕對路徑 2. 相對路徑
  - []：數列：有順序
  - {}：集合：沒順序
  - [W2 練習一](https://github.com/YU-HE-TIEN/PL/blob/main/practice/week02_practice01.ipynb)
- #### week 03(9/22)
  1. 一般變數：一個變數只能存一個數
  2. dataframe：CSV或txt檔案格式存資料的方式
  3. list：數列，只能儲存相同資料格式
  4. set：集合，都可以放
    - 資料比對
    - 差集：set1-set2 
    - 聯集：set1+set2 
    - 兩者交集：Intersection(set1,set2) 
    - 對稱差集：set1.symmetric_difference(set2))
    - 詳見[W3 作業一](https://github.com/YU-HE-TIEN/PL/blob/main/homework/Week03_homework01.ipynb)
- #### week 04(9/29)
  1. dictionary 巢狀應用：
     - 觸犯條例人員名單
     - 修課列表
     - 商品型錄
  2. json 資料格式
  - [W4 練習一](https://github.com/YU-HE-TIEN/PL/blob/main/practice/week04_practice01.ipynb)
  - [W4 練習二](https://github.com/YU-HE-TIEN/PL/blob/main/practice/week04_practice02.ipynb)
- #### week 05(10/7)：巢狀資料
  1. 結構化資料－表格：csv/xls...
  2. 結構化資料－半巢狀結構資料：json/xml/html...
  3. 非結構化資料－文字資料、圖：pdf/png...
- #### week 06(10/13)：資料正則化
    - [找資料字串程式大表格](http://perso.ens-lyon.fr/lise.vaudor/strings-et-expressions-regulieres/?fbclid=IwAR0IHvNKp43Qrfo0TqpolYPpMUfViSrCBDY8SmBveKm01yZ6PzHPxspVaNI)
    - [練習資料查找字串網頁](https://www.google.com/url?q=https://regexr.com/&sa=D&source=editors&ust=1665624637181435&usg=AOvVaw2OlkT5ZPwv2qGOwedi1gg1)
    - [編輯json檔:檢查dict結構](https://jsoncrack.com/editor)
  - regular expression
    - import re
      - 尋找配對:re.search('目標字串','資料')
      - 尋找所有匹配:re.findall('目標字串','資料')
      - 替換字元:re.sub('原來字串','改變的字串','資料')
      - 拆開:re.split('預刪除的字串','資料')
      - 包裝:re.compile(預使用字串)，後結合上述函數
    - [範例](https://github.com/pecu/LawTech/blob/main/Learning-Materials/C3_Python_%E8%B3%87%E6%96%99%E6%AD%A3%E8%A6%8F%E5%8C%96/python_%E8%B3%87%E6%96%99%E6%AD%A3%E5%89%87%E5%8C%96_code.ipynb)
- #### week 07(10/20)：網路爬蟲
     - 讓電腦模擬使用者抓取網站上的資訊
- #### week 08(10/27)：資料彙整&資料視覺化
     - [實用的資料視覺化網站:有地圖!!](https://www.google.com/url?q=https://plotly.com/python/&sa=D&source=editors&ust=1667009293913850&usg=AOvVaw1cRoMdl0wPqFmnif6cbLsf)
- #### week 09(11/03)：文字探勘
     - [文字探勘](https://www.youtube.com/watch?v=HGPPoaBxyb0)
- #### week 10(11/10)：鱸魚演講
     - what->how->why
     - 冒險
     - 追求生命體驗
- #### week 11(11/17)：


## 📝課程練習
  - [W2 練習一](https://github.com/YU-HE-TIEN/PL/blob/main/practice/week02_practice01.ipynb)
  - [W4 練習一](https://github.com/YU-HE-TIEN/PL/blob/main/practice/week04_practice01.ipynb) 
  - [W4 練習二](https://github.com/YU-HE-TIEN/PL/blob/main/practice/week04_practice02.ipynb)
  - [W6 練習一](https://github.com/YU-HE-TIEN/PL/blob/main/practice/week06_practice01.ipynb)
  - [W7 練習一](https://github.com/YU-HE-TIEN/PL/blob/main/practice/week07_practice01.ipynb)
  - [W8 練習一](https://github.com/YU-HE-TIEN/PL/blob/main/practice/week08_practice01.ipynb)

## 🖊課程作業
- [作業一](https://github.com/YU-HE-TIEN/PL/blob/main/homework/Week03_homework01.ipynb)
- [作業二](https://github.com/YU-HE-TIEN/PL/blob/main/homework/week05_homework02.ipynb)
- [作業三](https://github.com/YU-HE-TIEN/PL/blob/main/homework/week07_homework03.ipynb)
- [作業四](https://medium.com/@just_copper_cattle_786/利用python文字探勘功能分析全台景點個數及特定縣市景點關鍵詞-d2e254c39b0e)
- 作業五

## 💻相關專題

## 🉐課程心得
