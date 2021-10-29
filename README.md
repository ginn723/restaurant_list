### Introduction - 介紹
記錄8家最喜歡的餐廳，可以瀏覽餐廳、查找餐廳資訊、甚至連結到地圖。


### Features - 功能
定義「餐廳清單」的基本功能：

- 使用者可以看到首頁所有餐廳的**簡單資料**：
  餐廳**照片**
  餐廳**名稱**
  餐廳**分類**
  餐廳**評分**
  
- 使用者可以**再點進去看**餐廳的**詳細資訊**：  
  類別
  地址
  電話
  描述
  圖片
  
- 使用者可以透過**搜尋餐廳名稱**來找到特定的餐廳

- 使用者可以透過**搜尋餐廳類別**來找到特定的餐廳


### Tools - 開發工具
* Node.js 
* Express
* Express-Handlebars
* Bootstrap
* Font-awesome


### Technical Info - 技術内容
- [x] 讀取 JSON 檔案，將種子資料載入應用程式
- [x] 把資料帶入 handlebars 樣板中動態呈現
- [x] 操作 handlebars 中的 each 迴圈呈現出多張餐廳卡片
- [x] 應用 params 打造動態路由
- [x] 用 Query String 打造搜尋功能


## Installing - 安裝流程
1. 將此專案 Clone 至本機電腦 git clone https://github.com/ginn723/restaurant_list.git

2. 開啓 Terminal，切換進入此專案的資料夾 $ cd restaurant_list

3. 在 Terminal 安裝 npm (Node Package Manager) 套件
$ npm install

4. 安裝完成後，在 Terminal 輸入：
$ npm run start

5. 安裝成功會出現此訊息：
Listening on http://localhost:3000

6. 打開瀏覽器，並進入到此網址。
http://localhost:3000

7. 若要暫停使用，請在 Terminal 環境，連按兩下Ctrl+C 結束工作
^c

## Contributor - 開發人員
[Ginn Lee](https://github.com/ginn723)
