# FFC_PDM_WPF_Mini_Project

팀 소개

# contents
1. 개요
2. 사용 데이터 및 데이터 분석 계획
3. 사용 기술 및 개발 계획
4. 핵심 기능 및 UI

# 1. 개요
예측 정비를 통해 운전 중 고장의 위험도를 감소시켜 설비 고장으로 생기는 금전, 시간, 인적 자원을 절약한다.

# 2. 사용 데이터 및 데이터 분석 기획
## 1) 사용 데이터
캐글의 xinjang(Predictive Maintenance)의 PdM 데이터 활용(https://www.kaggle.com/datasets/yuansaijie0604/xinjiang-pm/code)
## 2) 데이터 분석 계획
A. 장비 가동 데이터, 장비 정보, 설비 고장 이력 데이터, 경고 이력 데이터, 유지 보수 이력 데이터를 활용하여 고장에 위험을 주는 요소를 선별한다.
B. 각각의 고장 위험 요소에 대해 임계값을 설정하고, 해당 값들을 초과할 경우 위험 상태로 판단하도록 분석 기준을 수립한다. 

# 3. 사용 기술 및 개발 계획
## 1) 사용 기술
### 1-1) 데이터 분석
A. 언어: python3.8
B. 라이브러리: numpy1.24.3, pandas2.0.3
C. 개발 툴: Visual Studio Code 1.84.2

### 1-2) 화면
A. 언어: C# 11.0
B. Framework: .NET 7.0
C. 라이브러리: scottplot 4.1.68
