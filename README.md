## 개요

이 프로젝트는 **KML Challenge 2023F**에서 주어진 문제를 해결하기 위해 개발되었습니다. 문제는 "각 패널에게 어떤 온라인 설문조사를 요청해야 응답할까?"를 예측하는 모델을 구축하는 것입니다.

## 데이터셋

- **train.csv**: 학습 데이터
- **test.csv**: 평가 데이터
- 각 데이터 포인트는 패널 정보, 설문정보, 응답여부(STATUS)로 구성되어 있습니다.

## 사용된 라이브러리

본 프로젝트에서는 다음과 같은 라이브러리들이 사용되었습니다:
- 데이터 처리: `pandas`, `numpy`
- 시각화: `seaborn`, `matplotlib`
- 머신러닝: `scikit-learn`, `catboost`, `lightgbm`, `xgboost`
- 기타: `optuna` (Hyperparameter tuning)

## 모델

사용된 모델은 다음과 같습니다:
- 로지스틱 회귀 (`Logistic Regression`)
- 랜덤 포레스트 (`Random Forest`)
- XGBoost
- LightGBM
- SVM (`Support Vector Machine`)
- 신경망 (`Neural Network`)
- 나이브 베이즈 (`Naive Bayes`)
- 결정 트리 (`Decision Tree`)

## 결과 및 성능 평가

모델의 성능은 주로 정확도(Accuracy)를 기준으로 평가되었습니다.

## 파일 구조

- `ML_final_report.ipynb`: Jupyter Notebook 파일로, 모델 개발 및 평가 과정이 포함되어 있습니다.
- `data/`: 데이터셋 파일들이 위치한 폴더입니다.
- `src/`: 코드 파일들이 위치한 폴더입니다.

