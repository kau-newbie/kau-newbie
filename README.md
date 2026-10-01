<!---
kau-newbie/kau-newbie is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
# 블로그
https://kau-newbie.github.io/

---

# 소개

항공전자정보공학부 정보통신공학 전공하고 있습니다(2027년 2월 졸업 예정). 

### 주요 프로젝트

**[touchWhere](https://github.com/kau-newbie/touchWhere)** · Kotlin, Android · 졸업 프로젝트(3인 팀), 학부 우수상
- 고령층의 스마트폰 사용을 돕는 GUI Agent. 음성 요청을 텍스트로 바꾸고, 접근성 서비스로 수집한 화면 정보를 LLM에 전달해 다음 행동을 화면에 안내합니다.
- 약 460개의 학습 데이터로 Gemma4-E4B를 QLoRA 방식으로 파인튜닝해, 기본 모델 대비 작업 수행 정확도를 180% 높였습니다.

**공시 질의응답 RAG Agent** · Python, LangGraph · 미래에셋 AI Festival 2026 (비공개 저장소)
- 70개 기업의 공시 문서를 바탕으로 기업 재무 질문에 답하는 RAG Agent.
- LangGraph로 에이전트 실행 흐름을 구현하고, 그래프를 18개 노드에서 11개로 줄여 Supervisor 노드로 통합했습니다.
- XML 파서 오류로 사업보고서 207건 중 37건의 재무제표가 색인에서 빠진 문제를 찾아 고쳤습니다.

**[LG Aimers 9기 해커톤](https://github.com/lg-first-penguin/lgaimers9-ensemble-v1)** · Python, MLP, CatBoost · 1,090팀 중 162등 
- 야구 투구 제구 예측. 피처 검증과 모델 실험을 맡아, 실제 추론에서 상수가 되던 피처 64개를 찾아 제거해 제출 점수를 24.03점 올렸습니다.

**[lecture-sync](https://github.com/kau-newbie/lecture-sync)** · Python · Claude Code 플러그인
- 강의자료가 추가되면 장별 보충본과 퀴즈, 과목별 지식 그래프를 만들고 Gmail로 알려 줍니다.

**[couple-cam](https://github.com/kau-newbie/couple-cam)** · Java, Spring Boot, Docker
- 커플을 위한 원격 영상 연결 서비스.
- 라즈베리 파이를 캠으로 이용, 서버에서는 mediaMTX로 스트리밍 중계를, Spring Security와 JWT로는 인증을 구현했습니다.

### 좀 더 low-level인 과제

- **[simple-concurrent-server-and-client-program](https://github.com/kau-newbie/simple-concurrent-server-and-client-program)** · C · 멀티스레딩 TCP 에코 서버와 클라이언트
- **[simple-calculator](https://github.com/kau-newbie/simple-calculator)** · Verilog HDL · 2의 보수 기반 사칙연산 계산기(제어기, 레지스터 설계)

### 기술

- 언어: Python, Kotlin, Java, C, Verilog
- AI: LangGraph, QLoRA 파인튜닝, RAG
- 인프라: Docker, AWS, Hadoop


