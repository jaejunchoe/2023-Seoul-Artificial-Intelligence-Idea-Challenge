
# 2023 서울시 인공지능(AI) 아이디어 챌린지
* `서비스 아이디어 제안유형: 복지`
  
![image](https://github.com/user-attachments/assets/c907d13f-20ea-4ce9-8785-13f1cf07a29d)


<br/><br/>

# ✨ Team
- 구성원
* 팀장: 정민규 - 국립금오공과대학교 디자인인공학전공 3학년
* 팀원: 전민욱, 최재준 - 국립금오공과대학교 산업경영공학전공 3학년 

<br/><br/>

# 🗂 Presentation
## 1. Data
- KOSIS 국가통계포털(통계청, 한국노인인력개발원)
- 서울 열린데이터광장(서울특별시)

![image](https://github.com/user-attachments/assets/9319d24f-ff46-40ec-83dc-25f2fd897868)



<br/><br/>
## 2. Problem Definition & Project Purpose
* Problem Definition: `'고령화 사회로 진행되며 노인들이 느끼는 외로움과 문화/사회활동 필요성 증가'` + `'국공립 유치원 충원률, 채용률 감소 문제'가 동시에 발생하고 있다.`
* Project Purpose: `국공립 유치원의 존폐 위기를 해소하고자 일부 국공립 유치원을 노치원으로 활용하는 아이디어 제시함과 동시에 AI를 활용한 최적 위치 선정을 도출하여 노인들의 삶의 질 향상 및 사회적 문제에 대한 대안을 제시한다.`

![image](https://github.com/user-attachments/assets/cc8e2197-319f-464e-a18c-9c161d2a975a)


![image](https://github.com/user-attachments/assets/8aa10eda-3514-4102-9987-af54e5f83dbe)
![image](https://github.com/user-attachments/assets/dc29cff1-9d46-4151-943d-5cb5c8e68b8c)




<br/><br/>
## 3. Modeling
- 최적의 위치선정을 위한 AI 모델 구현 로드맵
![프레젠테이션1](https://github.com/user-attachments/assets/1965516b-e291-485f-9994-e4cf113a39b9)


<br/>

- Clustering 기법: `DBSCAN`

- 하이퍼파라미터: `Grid Search를 사용하여 eps, min_samples 도출`


<br/><br/>
## 4. Data Analysis And Results 
- 예측 결과


     (1) 예측된 FA 최고 금액 계약 예상자 TOP 4
  
     ![슬라이드17](https://github.com/user-attachments/assets/a6163416-a5df-4c34-ba4a-cd53b85e5435)



     (2) 나머지 2024 FA 취득 예정자의 연봉 예측
  
     ![슬라이드18](https://github.com/user-attachments/assets/7c9d0e10-e224-4c65-a823-174d3663352f)



<br/><br/>
## 5. Conclusion & Comment
- 결정계수(R2 Score)값이 타자의 경우에는 약 0.52로 나왔지만 투수의 경우에는 약 0.31로 나와 전체적으로 봤을 때, 좋은 모델이라고 보기에는 어렵다.
- Correlation 분석에서 세이버매트릭스 지표가 FA금액을 결정하는데 있어 많은 연관성을 가졌다는 점에서 
- 세이버매트릭스(sabermetrics)처럼 통계적으로 세부적이고 과학적 지표가 효과가 있음을  확인할 수 있었다.
- 투수의 데이터 수가 타자에 비해서 적었다는 점에서 투수의 모델을 구성하고 분석하는데 있어서 아쉬움이 존재했다.
- 선수들의 FA금액을 판단하는데 있어서 지표만으로 판단하는 것을 섣부른 판단이라는 것을 알게 되었다.





