# programmers_machine_learning_jobfair

1. **기간 : 2019.12.02~2019.12.17**

2. **기술스택 : python, pandas, numpy, tensorflow, keras**

3. **내용 : 특정 기술스택을 가지고 있는 지원자가 특정 기술스택을 원하는 회사에 지원했을지 예측하는 모델 구현하기**
    1. 주어지는 정보
        - 회사에 대한 정보 : 원하는 기술스택, 회사의 규모 등.
        - 지원자에 대한 정보 : 지원자가 갖고있는 기술스택.
        - 지원여부 : 특정 회사에 특정 지원자가 지원했는지 여부.
    2. 모델1
        - 모든 기술스택 N개에 대해서 특정회사가 해당 스택을 원하면 1, 아니면 0의 값을 가지는 길이 N의 companyL 리스트 생성
        - 모든 기술스택 N개에 대해서 해당 지원자가 해당 기술을 갖고 있으면 1, 아니면 0을 가지는 길이 N의 userL 리스트 생성
        - companyL+userL 을 input으로 가지고, 지원여부를 output으로 하여 모델 학습.
        - 모델구조  
        ![noname01](https://user-images.githubusercontent.com/50386280/78499120-c8203400-7789-11ea-85ae-ffadcedc9180.png)
    3. 모델2 (모델1보다 우수한성능, 최종제출)
        - 모들 기술스택 N에 대해서, 지원자와 회사가 모두 원하면 0.9, 지원자만 원하면 0.5, 회사만 원하면 0.3, 둘다 원하지않으면 0.1 갖는 tempL 리스트 생성
        - tempL를 input값으로 가지고, 지원여부를 output으로 하여 모델 학습.
        - 모델구조  
        ![2](https://user-images.githubusercontent.com/50386280/78499209-4977c680-778a-11ea-8b98-02833449d80f.png)

4. **파일설명**
    **[input file : (잡페어 규정상 공개불가), output model : donghyun_model.h5, donghyun_model2.h5]**  
    1. model1.ipynb : 모델1의 전처리, DNN모델.
    2. model2.ipynb : 모델2의 전처리, DNN모델.
    3. donghyun_model.h5 : 모델1
    4. donghyun_model2.h5 : 모델2
    5. test1.ipynb : 모델1로 답안 추출
    6. test2.ipynb : 모델2로 답안 추출
    
5. **순위**  
    ![4위](https://user-images.githubusercontent.com/50386280/78499410-82646b00-778b-11ea-943e-01bb35a533ce.png)


    
