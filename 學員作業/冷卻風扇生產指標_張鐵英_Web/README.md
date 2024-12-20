## Cooling Fan python web homework
## 17 張鐵英的作業

## 1. 與冷卻風扇公司討論出的 AOI Block Diagram
![AOI Block Diagram](https://github.com/roberthsu2003/__2024_09_04_tvdi__/blob/main/%E5%AD%B8%E5%93%A1%E4%BD%9C%E6%A5%AD/%E5%86%B7%E5%8D%BB%E9%A2%A8%E6%89%87%E7%94%9F%E7%94%A2%E6%8C%87%E6%A8%99_%E5%BC%B5%E9%90%B5%E8%8B%B1_Web/img_proj/pythonweb.png)
### 2. 在FanAOI Inspection Subsystem 部份是使用了TensorFlow.karas 的CNN 訓練模型,完成了冷卻風扇影像的檢測
![block diagarm](https://github.com/roberthsu2003/__2024_09_04_tvdi__/blob/main/%E5%AD%B8%E5%93%A1%E4%BD%9C%E6%A5%AD/%E5%86%B7%E5%8D%BB%E9%A2%A8%E6%89%87%E7%94%9F%E7%94%A2%E6%8C%87%E6%A8%99_%E5%BC%B5%E9%90%B5%E8%8B%B1_Web/img_proj/CNN_DM.png)
## 3. Python window 部分
### 3.1 廠商未提供python window的input data, 故用程式模擬出（業務,客戶),(客戶,訂單),(訂單,生產)的relational database 做為python window的input.
![sim_input](https://github.com/Austin-Chang-zz/__2024_09_04_tvdi__fork/blob/main/%E5%AD%B8%E5%93%A1%E4%BD%9C%E6%A5%AD/%E5%86%B7%E5%8D%BB%E9%A2%A8%E6%89%87%E7%94%9F%E7%94%A2%E6%8C%87%E6%A8%99_%E5%BC%B5%E9%90%B5%E8%8B%B1/img_proj/sim_input.png)
### 3.2 完成RadioButton功能, 可選擇任一業務會顯示出該業務的客戶的radio button, 點選客戶後會顯示該客戶的訂單的部分明細,包括良率及直通率.
![radio_button](https://github.com/Austin-Chang-zz/__2024_09_04_tvdi__fork/blob/main/%E5%AD%B8%E5%93%A1%E4%BD%9C%E6%A5%AD/%E5%86%B7%E5%8D%BB%E9%A2%A8%E6%89%87%E7%94%9F%E7%94%A2%E6%8C%87%E6%A8%99_%E5%BC%B5%E9%90%B5%E8%8B%B1/img_proj/RadioButton.png)
## 4. Python web 部分
### 4.1 點選radio button 如yield rate, 再用dropdown 選擇業務如Charlie, table會顯示所有Charlie客戶訂單的yield rate, 下面圖表亦會顯示Charlie訂單的yield rate,x軸為訂單日期,非連續性,故用dot 來顯示yield rate.
![webpage](https://github.com/roberthsu2003/__2024_09_04_tvdi__/blob/main/%E5%AD%B8%E5%93%A1%E4%BD%9C%E6%A5%AD/%E5%86%B7%E5%8D%BB%E9%A2%A8%E6%89%87%E7%94%9F%E7%94%A2%E6%8C%87%E6%A8%99_%E5%BC%B5%E9%90%B5%E8%8B%B1_Web/img_proj/webpage.png)
