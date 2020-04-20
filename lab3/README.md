# Lab 3 : Multilayer Perceptron
## Data
|파일명|파일 형식|
|-------------|---------------------------|
|data_lab2.txt|space로 구분된 51행 3열 데이터|
|iris.csv|150행 5열 csv데이터|
## Tasks
1. data_lab3.txt의 데이터를 읽어서 x, y를 반환하는 함수를 작성하여라. data_lab3.txt는 x_1, x_2, y의 3개의 열로 이루어진 데이터이다. 
2. MLP를 통한 분류기 모델을 구현하여라. 단 MLP는 3개의 층을 가지며, 은닉층은 5개의 뉴런으로 이루어져있다. 
3. 은닉층과 출력층의 파라미터 값 v, w의 최적값은 무엇인가? 
4. 학습한 모델이 (x_1,x_2)=(2,2)와 (x_1,x_2)=(4,4)를 올바르게 분류하는지 검증하여라. 
5. iris.csv 데이터를 읽어서 x_train, y_train, x_test, y_test를 반환하는 함수를 작성하여라. 단, 함수 내에서 무작위로 순서를 섞은 뒤 7:3으로 train-test split을 하여라. 은닉층이 10개의 뉴런을 가지는 모델을 생성하고 100epoch마다 1번씩 train/test 데이터 각각의 error와 accuracy를 출력하여라.
