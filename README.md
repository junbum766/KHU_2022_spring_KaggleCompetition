# <KHU_2022_spring_KaggleCompetition>

## 안녕하세요 저희는 competition에서 99%의 accuracy로 7위를 차지한 Team7입니다.

## 중요한 Hyperparameter는 다음과 같습니다.
### model : EfficientNet_b0
### Optimizer : RAdam
### lr : 0.01
### image size : 224 
### LR Scheduler : CosineAnnealingWarmUpRestarts
### weight decay : 5e-5
### dropout : 0.3

### data augmentation 기법으로 transform 외에 직접 코드를 구성하여 데이터를 늘린 코드가 초반에 있는데,
### (class 별 데이터를 좌우 반전을 시켜 120개씩 늘린후, 다른 기법을 추가하여 100개씩 추가 생성하였습니다.)
### 오늘 질문드린 결과, 쓸데없는 짓(?) 이었던 것 같습니다...
### 하지만 다른 부분을 완벽히 고정시키고 비교해보지는 못한 것 같으나,
### 확실히 성능의 개선이 있었던 것을 보아, 이 이유에 대해 추후에 더 생각해보아야 할 것 같네요.
### 이거 외에는 다른 조들과 특별히 다른 사항은 없는 것 같습니다.
### 가장 신경을 써서 가장 많이 조정한 부분은 스케줄러랑 transform 부분이었습니다.

### 감사합니다.
