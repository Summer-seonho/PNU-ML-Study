# 1주차 문제
 ## 인터넷 사용량 예측 (KNN)
  * **문제:** 다음 특성값을 토대로 Heavy 유저인지, Light 유저인지 판단하는 KNN 모델을 작성하세요.
    * 데이터셋: */datasets/internetlogit.csv*
  * **Features**: 각 데이터 포인트는 한 사람이다.
    * income: 매달 수입
    * videohours: 매주 동영상 시청량
    * webpages: 매주 방문하는 웹사이트 수
    * gender: 0 = 여성, 1 = 남성
    * age: 나이
  * **Class**: usage 컬럼 
    * Heavy 유저: (=1) 매주 인터넷 사용량이 15,000mb 이상인 경우
    * Light 유저: (=0) 매주 인터넷 사용량이 15,000mb 미만인 경우
  * **사용 모듈**
  ```python
  import numpy as np
  import statsmodels.api as sm
  import pandas as pd
  from sklearn.model_selection import train_test_split
  from sklearn.preprocessing import MinMaxScaler
  from sklearn.neighbors import KNeighborsClassifier
  import matplotlib.pyplot as plt
  import mglearn
  import os;
  ```
  * **비고**
    * MinMaxScaler는 모든 컬럼의 값 범위를 [0, 1]로 한정하기 위한 것으로, 옵션 사항입니다.
    * k값을 조절해가면서 최적의 k값을 찾을 필요가 있습니다.
  * **출처**: [Data Science Central](https://www.datasciencecentral.com/profiles/blogs/k-nearest-neighbors-knn-solving-classification-problems)
 ## NumPy 연습
  * **문제:** NumPy Exercise.ipynb의 각 셀에 알맞은 코드 넣기  
  * **관련 강의**
    * [NumPy 강의(유튜브, 30분, 한글)](https://www.youtube.com/watch?v=OIV14ItViP0)
    * [NumPy 강의(유튜브, 1시간, 영어)](https://www.youtube.com/watch?v=QUT1VHiLmmI)
  * **출처:** Udemy 
  * **비고:** 교재에서 짤막하게 짚고 넘어간 NumPy 라이브러리 연습용 문제입니다. 
