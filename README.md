## 텍스트 마이닝을 활용한 한국은행 기준금리 예측 프로젝트
> 새싹 Bok 1조(박정은, 박수정, 최보겸, 정우경, 정찬영)   
프로젝트 기간: 2023.08.30~
<br/>

### 프로젝트 목표
금융통화위원회 의사록, 금리 키워드 관련 뉴스, 채권 보고서를 데이터로 sentiment analysis를 진행해 context에 대한 기준금리 변동의 영향력을 증명하고, 이를 바탕으로 최종 기준금리까 예측

- 텍스트 마이닝을 활용한 통화정책 분석 논문을 재현   
- 연도별 비정형 텍스트의 어조를 추출하여 지수화   
- 기준 금리의 변동에 대한 설명력과 예측력을 검증   
<br/>

### 1) 프로젝트 기획
**1) 논문선정**   
   > **Deciphering Monetary Policy Board Minutes through Text Mining Approach: The Case of Korea**  
저자 : 박기영(연세대학교 경제학부), 이영준(연세대학교 경영대학), 김수현(한국은행 경제연구원 국제경제연구실)

**2) 분석방법**   
   ① Market Approach: 콜금리 변화로 극성 label을 추가하여 Navie Bayes Classifier 직접 구현   
   ② Lexical Approach: 모든 문서에 대하여 token을 구하고, ngram2vec로 각각 25개로 구성된 Seed words와의 PMI를 계산하여 단어의 긍부정을 분류

**3) 분석절차**   
   ① 데이터 수집   
   ② 데이터 EDA 및 전처리   
   ③ Featur Selection   
   ④ Polarity Classification   
   ⑤ 회의록 tone 계산 및 기준금리 예측   

   
<br/>

### Stacks
<img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=Python&logoColor=white"> <img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=GitHub&logoColor=white">
<img src="https://img.shields.io/badge/Notion-000000?style=for-the-badge&logo=Notion&logoColor=white"> <img src="https://img.shields.io/badge/visualstudiocode-007ACC?style=for-the-badge&logo=visualstudiocode&logoColor=white"> <img src="https://img.shields.io/badge/googlecolab-F9AB00?style=for-the-badge&logo=googlecolab&logoColor=white"> 
<br/>
<br/>
