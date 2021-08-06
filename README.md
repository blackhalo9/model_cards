# Model Card for Time-Series Analysis 

**[시계열 관련 그림]**  

**[간단한 소개 등]** 


## 1. Model Details

* Devloper: DX추진팀, 2021년

* Overview: 다른 메탈(원자재) 시황, 경제 지표를 활용하여 1년/3년 단위의 니켈 평균 가격을 분기 별(년도 별)로 예측하는 모델


## 2. Intended Uses

* Application: 예측된 중장기 니켈 가격 정보를 구매 계획에 반영하여 수립 

* Domain and users: 구매 부서 해당 원자재 (원재료/반제품) 구매 담당자

* Out-of-Scope Applications: 니켈(금속)이 아닌 다른 종류의 메탈(원자재) 시황 예측에는 부적합

```
예시??
```

## 3. Model Specifications

* Model Type (Architecture): ARIMA, Prophet, LSTM

* Inputs
```
주요 변수 설명
``` 
* Outputs
```
1~3년 일/주/분기 별 니켈 가격 
``` 
* Version History
```
v1.0 (2021-08-06): 주요 변경 사항 포함
```
* Owners
```
DX추진팀
```
* References

## 4. Data

* Train Set
```
 그래프 및 분포
```

* Evaluation Set
```
 그래프 및 분포
```

## 5. Evaluation Results (Quantitative Analysis)

*	Model Results

## 6. Evaluation Metrics

*	RMSE
 
*	MAE

## 7.	Considerations

*	Trade-Offs

*	Limitations
