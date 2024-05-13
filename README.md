# 생체 신호 데이터를 이용한 흡연 여부 예측 모델링


> Period: 2023.11 ~ 2024.02
> 
> Subject: Classification
> 
> Role: 데이터 선정 및 수집, 시각화 및 전처리, 모델링



##### 24.02.01 last edit
---

## 0. Environment

+ Language : R

+ Editor : RStudio
---
## 1. Introduction

**Background**

흡연자의 생체 신호 데이터 분석을 통해 흡연과 관련된 주요 위험 요인을 식별하고 개인화된 예방 및 치료 계획을 수립하고자 함.

---
## 2. Data Set

**Dataset Info.**

https://www.kaggle.com/competitions/playground-series-s3e24

**Size**

159,256 * 24

---
## 3. Summary

**(1) Data Preprocessing**

- 탐색적 데이터 분석
- 데이터 시각화, 필터링, 스케일링
- 시각화를 통한 이상치, 결측치, 상관 관계 확인

<br/>

**(2) Model & Algorithms**
- 10-fold cross validation 적용

![image](https://github.com/HappyJieun/Smoking/assets/166107244/f1d2adba-0810-4215-8e12-4034744549f3)

<br/>
 
**(3) Evaluation**

![image](https://github.com/HappyJieun/Smoking/assets/166107244/21df43a7-6722-4c42-8acb-3f9db962f11e)


**(4) Review**

- 최적의 모델 선정: Randomforest 
- 흡연의 위험 요인 확인: Hemoglobin, HDL
- 특정 질병 유발 생체 신호 확인
