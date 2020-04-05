# programmers_machine_learning_jobfair

1. 기간 : 2019.12.02~2019.12.17  

2. 기술스택 : python, pandas, numpy, tensorflow, keras  

3. 내용 : 특정 기술스택을 가지고 있는 지원자가 특정 기술스택을 원하는 회사에 지원했을지 예측하는 모델 구현하기  
    1. 주어지는 정보
        - 회사에 대한 정보 : 원하는 기술스택, 회사의 규모 등.
        - 지원자에 대한 정보 : 지원자가 갖고있는 기술스택.
        - 지원여부 : 특정 회사에 특정 지원자가 지원했는지 여부.
    2. 모델1
        - 모든 기술스택 N개에 대해서 특정회사가 해당 스택을 원하면 1, 아니면 0의 값을 가지는 길이 N의 companyL 리스트 생성
        - 모든 기술스택 N개에 대해서 해당 지원자가 해당 기술을 갖고 있으면 1, 아니면 0을 가지는 길이 N의 userL 리스트 생성
        - companyL+userL 을 input으로 가지고, 지원여부를 output으로 하여 모델 학습
        - 모델구조
        ![noname01](https://user-images.githubusercontent.com/50386280/78499120-c8203400-7789-11ea-85ae-ffadcedc9180.png)

    
