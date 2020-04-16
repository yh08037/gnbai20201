# Lab 2 : Regularized Regression
## Data
|파일명|파일 형식|
|-------------|---------------------------|
|data_lab2.txt|tab으로 구분된 200행 2열 데이터|
## Tasks
1. data_lab2.txt의 데이터를 읽고, train 데이터 70%, test 데이터 30%로 분할하여라.
2. 다음의 가설 함수들에 대해 파라미터의 최적값을 구하여라.
    
    (비정규화 회귀는 최소 제곱법, 정규화 회귀는 closed-form solution 사용)
    
    * 비정규화 회귀 – 선형 모델
    * 비정규화 회귀 – 2차 다항식 모델
    * 비정규화 회귀 – 5차 다항식 모델
    * 정규화 회귀 – 5차 다항식 모델 (Ridge)

3. train 데이터 위에 학습된 회귀자들을 plot하고, train error를 구하여라.
4. test 데이터 위에 학습된 회귀자들을 plot하고, test error를 구하여라
