
# 2023 서울시 인공지능(AI) 아이디어 챌린지
* `서비스 아이디어 제안유형: 복지`
![image](https://github.com/user-attachments/assets/ed986545-8ce0-4381-9adb-b9458006cccd)


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
* Problem Definition: `FA 계약규모가 점점 커지면서 실력 대비 과도한 연봉을 받는 사례가 늘어나고 있다.`
* Project Purpose: `지난 5년간 FA 선수들와 비FA 선수들의 기록 통하여 2024년 FA를 자격을 갖출 예정인 KBO 선수들의 FA권리 행사시 1년치 연봉 예측`


![기계학습_텀프로젝트_디자인공학전공_4조](https://github.com/jaejunchoe/2023-1_Machine-Learning-Class/assets/157339263/da855a1e-01ec-437a-9d89-0dfacc2c1a31)


<br/><br/>
## 3. Modeling
- AI 모델 구현 로드맵
![기계학습 4조_발표 PPT_ver 06](https://github.com/user-attachments/assets/3b38857c-4ccf-437f-b962-13c19fd98192)

<br/>

- 사용 알고리즘: `RandomForestRegressor`

- 하이퍼파라미터: `GridSearchCV를 사용하여 n_estimators, max_depth, min_samples_split, min_samples_leaf 도출`


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





