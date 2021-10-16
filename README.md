# Benchmark-interest-rate-prediction


2021년 6월 현재 코로나 바이러스로 인하여 대부분의 나라들이 저금리 기조를 띄고 있습니다.
우리나라도 마찬가지인데, 미국이 금리를 올리기전에 선제 대응하는 것이 무엇보다 중요합니다.
그렇다면 과연 미국은 언제 금리를 올릴까요 ?
그리고 우리나라의 환율은 곧 강달러가 될까요 ? 약달러가 될까요 ? 딥러닝을 통해 예측해봅니다. 

단순히 LSTM 층을 구성해보고 진행해보는 것에 의의를 둡니다. 

- To predict American(Fed) benchmark interest rate 
- To predict Won ₩ : USD dollar $ price 

Data : Financial data reader , FRED , Etc,,, 


# No update -  Failure

1. Multicollinearity
2. Causality 
3. LSTM - Because it is difficult to find a pattern, there is also a tendency to predict with an ambiguous intermediate value.
4. LSTM - Just predict the day tomorrow by using yesterday's data - Not overall, but partially predicted data 

MODEL - LSTM 



