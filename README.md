# FFC_PDM_WPF_Mini_Project

팀 소개

# contents
1. 개요
2. 사용 데이터 및 데이터 분석 계획
3. 사용 기술 및 개발 계획
4. 기능 및 UI

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
<details>
<summary>1-1) 데이터 분석</summary>

&nbsp;&nbsp;&nbsp;&nbsp;A. 언어: python3.8

&nbsp;&nbsp;&nbsp;&nbsp;B. 라이브러리: numpy1.24.3, pandas2.0.3

&nbsp;&nbsp;&nbsp;&nbsp;C. 개발 툴: Visual Studio Code 1.84.2
</details>

<details>
<summary>1-2) GUI</summary>

&nbsp;&nbsp;&nbsp;&nbsp;A. 언어: C# 11.0

&nbsp;&nbsp;&nbsp;&nbsp;B. Framework: .NET 7.0

&nbsp;&nbsp;&nbsp;&nbsp;C. 라이브러리: scottplot 4.1.68
</details>



## 2) 개발 계획
A. 개발 기간: 2023.11.24(금) ~ 2023.11.30(목)
<details>
<summary>B. 상세 계획</summary>

&nbsp;&nbsp;&nbsp;&nbsp;A) 2023.11.24(금): 프로젝트 구조 설계 및 초기 세팅

&nbsp;&nbsp;&nbsp;&nbsp;B) 2023.11.27(월): 데이터 분석 모듈 개발

&nbsp;&nbsp;&nbsp;&nbsp;C) 2023.11.27(월) ~ 2023.11.28(화): UI 개발

&nbsp;&nbsp;&nbsp;&nbsp;D) 2023.11.29(수) ~ 2023.11.30(목): 통합 테스트 및 버그 수정
</details>

# 4. 기능 및 UI
<details>
<summary>1) 기능</summary>

&nbsp;&nbsp;&nbsp;&nbsp;A) 통계 탭을 통하여 전체 장비의 고장률, 오류 발생률 등 통계 정보를 보여준다.
&nbsp;&nbsp;&nbsp;&nbsp;B) 상세 보기 탭에서는 모델명, 모델ID를 선택할 수 있다.(다중 선택 가능)
&nbsp;&nbsp;&nbsp;&nbsp;C) 상세 보기 탭에서는 원하는 기간을 설정할 수 있다.
&nbsp;&nbsp;&nbsp;&nbsp;D) 선택한 장비와 기간에 대해서 위험 인자에 대한 정보를 보여준다.
&nbsp;&nbsp;&nbsp;&nbsp;E) 위험 인자에 대한 정보는 안정 범위(임계값)와 현재 위험한 장비의 모델ID, 차트가 있다.
&nbsp;&nbsp;&nbsp;&nbsp;F) 차트의 X축은 시간, Y축은 값으로 구성된다.
</details>

## 2) UI
