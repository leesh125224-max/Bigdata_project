# 반도체 제조 공정 데이터 분석 및 불량 예측 모델링

## 프로젝트 소개
본 프로젝트는 반도체 제조 공정에서 발생하는 센서 데이터와 공정 기록을 바탕으로 **수율 향상 및 불량 원인 분석**을 수행한 종합 데이터 분석 프로젝트입니다. 
통계적 공정 관리(SPC) 기법을 활용하여 공정의 이상 상태를 탐지하고, 머신러닝 모델을 도입하여 불량 칩 발생을 사전에 예측하며, 최종적으로 불량률을 최소화할 수 있는 핵심 공정 파라미터의 최적 구간을 도출했습니다.

## 핵심 목표
1. **공정 이상 탐지 (SPC):** C-관리도를 활용하여 Wafer 단위의 불량 칩 수를 모니터링하고 이상 공정(Out of Control) 식별.
2. **탐색적 데이터 분석 (EDA):** 생산 부하(Path) 및 주요 공정 변수가 불량률에 미치는 영향 분석.
3. **불량 예측 모델링:** 제조 공정 데이터의 고질적인 클래스 불균형 문제를 해결하고, 재현율(Recall)과 F1-Score를 극대화하는 예측 모델 구축.
4. **공정 최적화:** 주요 설비 파라미터(Source Power, RTA Temp, Bake Temp 등)의 최적 운전 구간 산출을 통한 수율 개선 가이드 제시.

## 기술 스택
- **Language:** Python
- **Data Analysis & Processing:** Pandas, NumPy
- **Visualization:** Matplotlib, Seaborn
- **Machine Learning:** Scikit-learn, Imbalanced-learn (SMOTE)
