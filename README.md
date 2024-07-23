
# 2023 서울시 인공지능(AI) 아이디어 챌린지
* `서비스 아이디어 제안유형: 복지`
  
![image](https://github.com/user-attachments/assets/c907d13f-20ea-4ce9-8785-13f1cf07a29d)


<br/><br/>

# ✨ Team
- 구성원
* 팀장: 정민규 - 국립금오공과대학교 디자인인공학전공 3학년
* 팀원: 전민욱, 최재준 - 국립금오공과대학교 산업경영공학전공 3학년 

<br/><br/>

# 👑 My Roles and Responsibilities
- 독거노인 수와 주거복지시설 현원의 파트의 분석 및 지역 특징 추출	
- 서울시 노인 인구 증가 추세, 고령화 지수, 여가활동에 대한 현 상황 자료수집 및 분석

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


     (1) Clustering을 통한 데이터 분석

        1) 노년 부양비와 출생 수 클러스터링 결과
    ![image](https://github.com/user-attachments/assets/5ede12ab-66d5-4b42-b658-370ac64fbee4)


        2) 독거노인 수와 복지시설 수 클러스터링 결과
    ![image](https://github.com/user-attachments/assets/bd5856a1-fd93-4969-919e-733fb0929c4c)

        3) 독거노인 수와 주거복지시설 현원 클러스터링 결과  
    ![image](https://github.com/user-attachments/assets/77dde4b6-fb56-46e1-88d2-9a496210abeb)

     
  
     (2) 최적 위치선정 도출
  
     ![image](https://github.com/user-attachments/assets/71a3d936-ccde-4b37-92f7-167dc4b93695)



<br/><br/>
## 5. Conclusion & Comment
- '국공립 노치원의 사회적 효과', '노인복지시설 확충과 만족도 증강', '유치원 과잉 문제 해결'라는 3가지의 기대효과가 존재한다.
- 노원구, 강서구, 양천구, 송파구, 성북구의 노치원 수요가 많을 것으로 예상한다.
- 선정한 예상 구에서 세부지역은 다음과 같다.
  `강서구: 염창동, 공항동`
  `송파구: 삼전동, 석촌동, 오금동`
  `성북구: 종암동을 제외한 동`
- 사용한 데이터의 수집년도가 상이하다. 
- 수요 에상 지역에 대한 설문조사를 통해 검증하는 작업을 진행하지 못해 깊이성이 아쉬었다.





