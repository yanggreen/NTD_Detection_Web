# Coin_Detection_Web
## 硬幣辨識的小網站
該網站將辨識硬幣的模型建立成一個有WEB UI測試網站

開始前請先確認python環境是否已經建置完成，也確認tensorflow版本與建立的模型一致
```python
pip install -r requirements.txt
```

將辨識硬幣的模型建立好後，將產生的.pb檔放入inference_graph資料夾，也將pbtxt檔案放入training資料夾

確定環境以及model file都放置好後，執行app.py檔
```python
python app.py
```
接著至　http://localhost:5000/
就可以看到網頁開啟的畫面

<img src="https://user-images.githubusercontent.com/30551460/123747357-68113280-d8e5-11eb-9784-1d93f8619f7f.png" width="50%">


接著下載一張範例圖檔，然後將這張範例圖檔上傳進行辨識

<img src="https://user-images.githubusercontent.com/30551460/123747130-1c5e8900-d8e5-11eb-9ad9-b54a4ded3fcc.png" width="50%">

此web app也可以部署到azure cloud或是heroku cloud搭建成一般的雲端服務

https://pidvalve.herokuapp.com/
