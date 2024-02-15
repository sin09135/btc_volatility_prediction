### 2024-1 데이터 학회 연합 ASCEND 채용 연계 데이터 분석 공모전

<img src="https://img.shields.io/badge/BTC-F7931A?style=flat&logo=bitcoin&logoColor=white"> **틱데이터 활용 비트코인(BTC)의 단기 변동성 예측 모델링**

주관/ 주최 : BDA , ASCEND(퀀트 트레이딩 기업)

참여 학회 : BDA, KUBIG, KHUDA, ESAA, ESC, PARROT

사용 모델 : Random Forest 

데이터 : 2023.01 ~ 2024.01 10분 단위 BTC 틱데이터 

평가 방법 / 성능평가지표 : 향후 7일 동안의 ‘실제 시장 데이터’에 적용해 성능을 평가 / mape

---

### Files

1. requirements.txt 
   - 제출 코드 재현을 위한 라이브러리 & 패키지 목록(python 3.11.4)
   - [![Generic badge](https://img.shields.io/badge/Python-3.11.4-3776AB.svg)](https://shields.io/)![Generic badge](https://img.shields.io/badge/Pandas-1.5.3-150458.svg)![Generic badge](https://img.shields.io/badge/Numpy-1.24.3-013243.svg)![Generic badge](https://img.shields.io/badge/ScikitLearn-1.3.0-F7931E.svg)<img src="https://img.shields.io/badge/Pmdarima-2.0.4-7F2B7B.svg"/>![Generic badge](https://img.shields.io/badge/statsmodels-0.14.0-150458.svg)![Generic badge](https://img.shields.io/badge/matplotlib-3.7.1-150458.svg)![Generic badge](https://img.shields.io/badge/seaborn-0.12.2-DD0700.svg)
2. 소스 코드.ipynb
   - jupyter notebook 파일
3. [ASCENDxBDA] submission.csv
   - Pred_volatility 값 작성



<br>
</br>



### 소스코드.ipynb

0. **Loading Data**

1. **Preprocessing**
   1. **Checking Missing Value**
      - OHLC, quote_qty
      - returns
      - volatility
   2. **Interpolate Missing Value - functions**
   3. **Interpolate Missing Value - interpolate**
      - OHLC, quote_qty
      - returns
      - volatility
   4. **Technical indicators**
      - MACD
      - Stochastic Oscillator 
      - ATR
      - Boolinger Bands
      - ROC
      - RSI
      - Ultimate Oscillator
   5. **Checking Missing Value - interpolate**



2. **Feature Engineering**
   1. **Feature combination optimization**
      - 기본 컬럼 및 파생변수 1차 선별
      - 파생변수 별 2차 선별



3. **Model Efficiency Optimization**
   1. **Optimization**
   2. **Model Selection**

---



