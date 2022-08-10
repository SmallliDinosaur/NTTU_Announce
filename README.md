# NTTU_Announce
Selenium爬學校公告網站並通知
<br>每二十分鐘爬取一次並覆蓋<br>
https://script.google.com/macros/s/AKfycbwY0ZK_uhQBdQ9PM547M-5CcXQUX_CuIkj7Rza-3XKXtHWFibslVMEy10uUlsBqd8Kk/exec?Title=Register
## 建置
* Django
* Pycharm
* Google Sheet
* Line Notify
* Heroku

## 示範
<img width="500" height="600" src="https://github.com/SmallliDinosaur/NTTU_Announce/blob/main/%E7%AF%84%E4%BE%8B.png"/>

## 過程
<img width="700" height="300" src="https://github.com/SmallliDinosaur/NTTU_Announce/blob/main/image/%E9%80%A3.png"/>
<img width="700" height="300" src="https://github.com/SmallliDinosaur/NTTU_Announce/blob/main/image/sheet.png"/>

<br>
### 遇到的問題
發生 status=500 錯誤，需要定義 Heroku 的環境變數，新增 ChromeDriver 的版本
