# Dacon_Jeju
데이콘 제주 빅데이터 경진대회

**EDA**: 

|  이름  |              내용              |
| :----: | :--------------------------: |
| [EDA 1](Jeju_01th.ipynb) |  value_count를 통한 지역별 업종 비중 확인 및 업종별 CNT, CSTMR_CNT 확인 |
| [EDA 2](Jeju_02th.ipynb) |  자동차 입출구 데이터와 AMT 관계 파악 |

**Data Preprocess**: 

|  이름  |              내용              |
| :----: | :--------------------------: |
| [Data Preprocess 1](Jeju_DataPreprocess_02th.ipynb) |  데이터프레임 결측치에 대한 고찰 |
| [Data Preprocess 2](Jeju_DataPreprocess_01th.ipynb) |  파생변수 제작: 전 기간의 수치(기준년월에 대한 3개월,6개월,9개월12개월 전의 AMT,CNT,CSTMR_CNT 의 변수를 삽입 |
| [Data Preprocess 3](Jeju_DataPreprocess_03th.ipynb) |  파생변수 제작 가이드라인: Jensen shannon divergence를 활용한 AgglomerativeClustering(계층적(합체) 군집화 적용) |
| [Data Preprocess 4](Jeju_DataPreprocess_04th.ipynb) |  Data_Preprocess_3 |


**Modeling**: 

|  이름  |              내용              |
| :----: | :--------------------------: |
| [LightGBM](Jeju_modeling_01th(LightGBM).ipynb) | Base Line 1: 일반 라벨인코딩 활용, Base Line 2: Categorical 변수 적용, Base Line 3: 업종별 Smote Oversampling 적용,Base Line 4: 전 기간 previous AMT,CNT,CSTMR_CNT 변수 생성 (Jeju_Preprocess_o1th에서 만든 데이터프레임 활용)  |
| [Catboost](Jeju_modeling_02th(catboost_just).ipynb) |범주형 변수를 활용한 Catboost 알고리즘 Baseline|
