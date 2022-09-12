# nongnet_AI

## modeling.ipynb
### target
* 단가(원)
* predict 1year(365days)
### val_loss(MSE)
1. LSTM : 0.01607
2. Random forest : 0.00029
3. fbProphet : 0.0024

## modeling_2weeks.ipynb
### target
* 해당일자_전체평균가격(원)
* predict 2weeks(14days)
### val_loss(MSE)
1. LSTM : 0.00290
2. Random Forest : 0.0008831665401987361
3. Prophet : 0.0018623818329433414
