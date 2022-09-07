# XGBoost_Stock_Prediction

**- Data Set :** KOSPI200 Index(Close) (2009-11-01 ~ 2017-12-29), Samsung Electronics Stock Price(Close) (2016-01-04 ~ 2021-12-30)<br/>
**- Tool :** Python, Jupyter Notebook, Keras<br/>
**- Model :** XGBoost Regression<br/>
**- Purpose :** Predict stock price direction<br/>
**- Reference :** XGBoost 모형을 활용한 코스피 200 주가지수 등락 예측에 관한 연구 <br/>
      DOI : 10.7465/jkdi.2019.30.3.655


# Reference Review & Applying

**1. Paper Accuracy**<br/>
<br/>
In the ref, the accuracy of predicting the direction of KOSPI 200 is **81.36%**<br/><br/>
![acc](https://user-images.githubusercontent.com/60992415/188822463-153f7593-0492-4169-a361-4c43192834c4.png)<br/>
So.. my purpose is to see if this acc is real a number, and if it's real, I'm going to apply it to stock predictions.<br/>
<br/>
<br/>
**2. Build Model and Check Regression**<br/>
<br/>
I made it as similar as possible to the refference.<br/><br/>
![accc](https://user-images.githubusercontent.com/60992415/188849272-9cd6c1e3-53af-4306-8428-ecfdd9a7c544.png)<br/><br/>
Direction accuracy is **75.53%**. But prediction movement is...<br/>
![predict_kospi200](https://user-images.githubusercontent.com/60992415/188846329-53289f99-7e14-45ca-8cee-12451d41ffff.png)<br/><br/>


**3. Apply Stock Prediction**<br/>
![predict_samsung](https://user-images.githubusercontent.com/60992415/188851003-d4ca8316-5882-4b42-b207-0a291ca06ab1.png)<br/>
Data is Samsung Electronics Stock Price and model, parameters, indicators are same things<br/><br/>

![acccc](https://user-images.githubusercontent.com/60992415/188851661-ee8b9e2f-77be-495a-8b63-bf175f1f096f.png)<br/>
Direction acc is **58.97%**...  :(<br/><br/>
I think the KOSPI200 is an index, so the accuracy is high because movement is not complicated,<br/>
and individual stocks are difficult to predict because movement is complicated.<br/><br/>

**If you see a problem while looking at my code, please let me know.**<br/>
<br/>
**Thanks!**<br/>
