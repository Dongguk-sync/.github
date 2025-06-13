<div align="center">
  <img src="https://capsule-render.vercel.app/api?type=venom&color=B2DAF7&height=300&section=header&text=BeakJi&fontSize=90&fontColor=303030" />
</div>


# _BeakJi_ 서비스란?

> **음성 기반 AI 복습 도우미**입니다.  
> 사용자가 학습한 내용을 말로 설명하면, AI가 이를 분석하고 채점 및 피드백을 제공합니다.  
> 교안 기반 자동 평가와 챗봇 질의응답 기능으로, 자기 주도적 복습을 지원합니다.


## 프로젝트 구조

| 레포지토리 | 설명 |
|------------|------|
| [Frontend](https://github.com/Dongguk-sync/2025-capstone-sync-AI.git) | 사용자 웹 인터페이스 |
| [Server](https://github.com/Dongguk-sync/2025-capstone-sync-server.git) | 백엔드 API 및 서비스 관리 로직 |
| [DB](https://github.com/Dongguk-sync/2025-capstone-sync-AI.git) | 데이터베이스 설정 및 스키마 관리 |
| [AI](https://github.com/Dongguk-sync/2025-capstone-sync-AI.git) | AI 모델 관련 (RAG 챗봇, 교안 전처리, 채점/피드백) |


## 핵심 기능

### 음성 복습 & 자동 채점
- 음성 인식으로 학습 내용을 입력
- 교안 기반 AI 채점
- 누락된 개념 피드백 제공

### 교안 분석
- PDF 업로드 (텍스트/이미지 지원)
- 핵심 개념, 정의, 공식, 연습문제 등으로 자동 분류

### RAG 기반 AI 챗봇
- 교안 및 복습 내용 기반 질의응답
  - 특정 개념 위치 질문 → **교안 열람 버튼 생성**
  - 개념 설명 질문 → **연관 교안 내용 포함 응답**
  - 복습 피드백 질문 → **사용자 피드백 기반 응답**


## 기술 스택

| 분류 | 기술 |
|------|------|
| 프론트엔드 | React, Tailwind CSS |
| 백엔드 | Node.js, Spring |
| AI / NLP | Whisper, LangChain, OpenAI, Python(FastAPI) |
| 데이터베이스 |  |
| 벡터스토어 | Chroma |


## 대상 사용자

- 중·고등학생
- 대학생
- 자격증 준비생

