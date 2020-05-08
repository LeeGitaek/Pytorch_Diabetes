# Pytorch_Diabetes
Pytorch / Logistic Classifier 를 사용하여 당뇨병 예측

로지스틱 분류기는 범주형 데이터 ( Binary data , 0 or 1)를 분류합니다.

Kaggle - Me : https://www.kaggle.com/coolfamily77

## 모델 학습 <br>
**[1] H(x) = sigmoid 함수로 가설을 설정하였습니다.**  <br>
 > 시그모이드 함수를 가설함수로 설정하여 0 과 1 사이의 값으로 설정하도록 하였습니다.
    
**[2] 비용 함수 ( Cost Function ) 또는 Loss Function** <br>
 > cost = -(y_train * torch.log(hypothesis) + (1-y_train) * torch.log(1-hypothesis)).mean()
 
**[3] cost 비용을 최소화 하기 위한 최적화 알고리즘 / 경사하강법** <br>
 > learning _ rate = 1e-3 로 설정하였으며,<br>
   epoch = 50001 만큼 학습하였습니다.<br>
   
**[4] 데이터 예측**<br>
 > 
