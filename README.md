# KHU_2022_spring_KaggleCompetition

# 중요한 Hyperparameter는 다음과 같습니다.
## model : EfficientNet_b0
## Optimizer : RAdam
## lr : 0.01
## image size : 224 
## LR Scheduler : CosineAnnealingWarmUpRestarts
## weight decay : 5e-5
## dropout : 0.3

### data augmentation 기법으로 transform 외에 직접 코드를 구성하여 데이터를 늘린 코드가 초반에 있는데,
### 오늘 질문드린 결과, 쓸데없는 짓(?) 이었던 것 같습니다...
### 이거 외에는 다른 조들과 특별히 다른 사항은 없는 것 같네요.
### 가장 신경을 써서 하이퍼파라미터를 조정한 부분은 스케줄러랑 transform 부분이었습니다.

### 감사합니다.
