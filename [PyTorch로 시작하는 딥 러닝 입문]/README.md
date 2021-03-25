# PyTorch로 시작하는 딥 러닝 입문
![image](https://user-images.githubusercontent.com/79825411/112557291-7b58c180-8e0f-11eb-9ecf-8b41f7013d70.png)

## 1. torch
- 메인 네임스페이스. 텐서 등의 다양한 수학 함수가 포함되어져 있으며 Numpy와 유사한 구조를 가진다.

## 2. torch.autograd
- 자동 미분을 위한 함수들이 포함되어져 있다.
- 자동 미분의 on/off를 제어하는 콘텍스트 매니저(enable_grad/no_grad)나 자체 미분 가능 함수를 정의할 때 사용하는 기반 클래스인 'Function'등이 포함되어져 있다.

## 3. torch.nn
- 신경망을 구축하기 위한 다양한 데이터 구조나 레이어 등이 정의되어져 있다. 
- RNN,LSTM과 같은 레이어, 
- ReLU와 같은 활성화 함수, 
- MSELoss와 같은 손실 함수들이 있다.

## 4. torch.optim
- 확률적 경사 하강법(Stochastic Gradient Descent, SGD)를 중심으로 한 파라미터 최적화 알고리즘이 구현되어져 있다.

## 5. torch.utils.data
- 확률적 경사 하강법(SGD)의 반복 연산을 실행할 때 사용하는 미니 배치용 유틸리티 함수가 포함되어져 있다.

## 6. torch.onnx
- ONNX(Open Neural Network Exchange)의 포맷으로 모델을 익스포트(export)할 때 사용하낟.
- ONNX는 서로 다른 딥 러닝 프레임워크 간에 모델을 공유할 때 사용하는 포맷.
