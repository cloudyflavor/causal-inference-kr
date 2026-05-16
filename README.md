# causal-inference-kr

인과추론 개념을 게임 데이터로 설명하는 노트북 모음입니다.

## 노트북

### 18_hatarogeneous_treatment_effects_ko.ipynb

게임 유저 행동 로그를 사용해 이질적 처치 효과(HTE)를 설명합니다.

- ATE: 전체 평균 처치 효과
- HTE: sub-group analysis로 효과 이질성 확인
- CATE: 상호작용 모델로 연속적 추정

## 데이터

`backend-ts_v0.1/GAME_C_JUL/` 폴더가 필요합니다. 노트북과 같은 위치에 두세요.

## 패키지

```
pandas
numpy
matplotlib
pyarrow
```
