# toc-project-what-to-eat

	The Linebot for TOC project.

## 吃啥吃啥小幫手

	每天都很煩惱要吃什麼嗎 ?

	讓小幫手解決您的選擇困難 !


## 好友資訊
![image](https://github.com/Shulammiteya/toc-project-what-to-eat/blob/main/img_fix/%E8%9E%A2%E5%B9%95%E6%93%B7%E5%8F%96%E7%95%AB%E9%9D%A2%20(61).png?raw=true)

## FSM Diagram
![image](https://raw.githubusercontent.com/Shulammiteya/toc-project-what-to-eat/main/received_890917781680792.webp)


## 使用說明

小幫手有四項服務，可分為兩類 : 1. 食物方面的服務、  2. 紀錄。


* 第一類：

	* 若使用者已經想好要吃什麼了，便告訴小幫手『我想吃．．．』，之後便可以看食物照片與使用ｇｏｏｇｌｅ地圖搜尋附近相關的店家；
	
	* 若使用者還沒想好要吃什麼，便選擇『小幫手推薦．．．』，小幫手便會根據過去的紀錄來推薦使用者最高機率愛吃的食物。
	
* 第二類：

	* 吃完飯後，可以用『紀錄一下我吃了什麼』來做紀錄；
	
	* 點選『看看過去我吃了什麼』則是可以查看紀錄。


## 使用示範

* 首先，傳任意文字訊息喚醒小幫手，小幫手會傳給使用者flex message，可以快速選擇想要的服務。

* 選擇『我想吃．．．』，再選擇想吃的食物（若是選項中沒有使用者想吃的，可以直接輸入訊息），
* 接著從flex message看網路上抓取的相關食物照片，每次照片可能不同，因為有在所有抓取到的相關食物照片中隨機選擇，避免使用者因為每次都一樣照片而感到無聊。
* 而flex message除了圖片外，還有兩個按鈕，一個是看原圖，一個是連接到 google map，方便使用者前往想要的餐廳。
	![image](https://github.com/Shulammiteya/toc-project-what-to-eat/blob/main/img_fix/%E5%9C%96%E7%89%873.png?raw=true)
	
* 選擇『看看過去我吃了什麼』，再做紀錄幾次。而小幫手會根據以前吃過的東西來做推薦喔，（若無紀錄便隨機推薦）。
	![image](https://github.com/Shulammiteya/toc-project-what-to-eat/blob/main/img_fix/%E5%9C%96%E7%89%874.png?raw=true)
