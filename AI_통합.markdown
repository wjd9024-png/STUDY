# 1-1 기계학습
## 1. 지도학습의 개념

## 2. 회귀 (Regression)
: 연속적 수치

### 2-2 평균제곱오차(MSE)
- 정답과 예측의 평균 제곱 차이값
- 틀린 정도를 제곱해서 더 큰 오류에 패널티

### 2-3 결정계수(R**2)
- 모델이 실제값을 얼마나 더 잘 맞추는지를 0~1 사이 값으로 표현

## 3. 분류

### 3-2. 정확도(Accuracy)

### 3-3. 혼동행렬
- 1종 오류(FP)
  - 실제 음성인데 양성(오탐)
-  2종 오류(FN)
   - 실제 양성인데 음성(누락)

  | 정밀도(Precision)
    "양성 판정" 중 진짜 양성
    = TP/(TP+FP)
  | 재현율(Recall)
    "진짜 양성" 중 예측한 양성
    = TP/(TP+FN)
  | F1-score
    정밀도와 재현율의 조화평균


# 4-1 LangChain

## 1. Environment Representation & Understanding

(밝혀지지않은)복잡합 환경 보완
1. 프로프트
2. 비지도 프롬프트 유도
   - 명령을 검색을 해오고 이용
      
      (부족한 경험을 검색을 통해 보완)
   - 환경탐색
      
      호기심 기반 보상


3. 탐색 기반 궤적 기억
   - LM-agent 환경 탐색
   - LM-labeler 자기 교정

## 2. Reasoning & Planning

- Local Planning
  - 툴(tool)
  - 추론 - 관측(action) 순환
  - 웹 탐색, Q&A 강점
  
- Global Planning
  

| 오류 식별과 회복(Error identification and Recovery)
- Reflexion (Shinn et al.. 2023)
  - 수행 - 오류 분석 - 재시도 - 회복
  
| 계획 재검토(Revisiting Plans)
- CoAct (Hou et al.. 2024)
  - 두 개의 에이전트가 서로 협력 

## 3. Langcahin

- 다양한 데이터/ 툴