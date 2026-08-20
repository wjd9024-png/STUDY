




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