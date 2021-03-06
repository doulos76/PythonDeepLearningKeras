# Keras 기본 개념

## Dataset가져오기

- 원본 Data를 불러오거나 Simulation을 통해 Data생성
- Data로 부터 훈련셋, 검증셋, 시험셋을 생성함
- 딥러닝 모델의 학습 및 평가를 할 수 있도록 포멧 변환을 함

## Model 구성하기

- 시퀀스 모델을 생성한 뒤 필요한 레이어를 추가하여 구성함
- 복잡한 모델이 필요할 때 Keras함수API를 사요함

## Model 학습과정 설정하기

- 학습전 학습에 대한 설정을 수행함
- 손실 함수 및 최적화 방법을 정의함
- Keras에서는 compile() 함수를 사용함

## Model 학습시키기

- 구성한 모델을 훈련셋으로 학습시킴
- 케라스에서는 fit() 함수를 사용함

## 학습과정 살펴보기

- 모델 학습 시 훈련셋, 검증셋의 손실 및 정확도를 측정함
- 반복 횟수에 따른 손실 및 정확도 추이를 보면서 학습 상황을 판단함

## Model 평가하기

- 준비된 시험셋으로 학습한 모델을 평가함
- 케라스에서는 evaluate()함수를 사용

## Model 사용하기

- 임의의 입력으로 모델의 출력을 얻음
- 케라스에서는 predict()함수를 사용함.