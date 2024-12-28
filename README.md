# A-VIEW:AI-Powered Personalized_Interview_chatbot_application

## 프로젝트 개요
A-View는 AI를 활용하여 구직자가 현실적이고 개인맞춤형 면접을 준비할 수 있도록 돕는 어플리케이션이다. 최근 기업에서 AI 면접 시스템 도입이 증가함에 따라 A-View는 실제 면접 환경과 유사한 환경을 제공함으로써 이를 지원한다. 이 플랫폼은 면접 준비 과정에서 다음과 같은 세 가지 주요 문제를 해결하고자 개발하였다.

1. 현실감 있는 면접 연습 부족: 기존의 모의 면접은 몰입감과 동적인 경험을 제공하지 못하는 경우가 많다.

2. 맞춤형 질문과 피드백 부재: 일반적인 연습 질문은 개인의 고유한 자격과 상황을 반영하지 못한다.

3. 자기 평가의 어려움: 자신의 답변을 비판적으로 평가하고 개선점을 찾는 것이 어렵다.

A-View는 맞춤형 질문 생성, 실시간 음성 상호작용, AI 기반 피드백 등 혁신적인 기능을 통해 이러한 문제를 해결한다.

## 주요 기능

1. 맞춤형 질문 생성

  - Assistant API와 파일 검색 기능을 활용하여 업로드된 자기소개서를 분석.

  - 사용자 자기소개서 내용을 기반으로 면접 질문을 자동 생성.

  - 사용자의 답변에 따라 후속 질문을 동적으로 업데이트하여 현실감 있는 면접 환경 제공.

2. 실시간 음성 상호작용

  - TTS(Text-to-Speech)와 STT(Speech-to-Text) 기술을 통합하여 실제 면접과 유사한 환경 제공.

  - 사용자가 음성으로 답변하면, 실시간으로 피드백과 후속 질문을 음성으로 전달.

  - 실시간 대화를 통해 면접의 긴장감과 몰입감을 강화.

3. AI 기반 답변 분석 및 리포트 제공

  - 면접 세션 중 사용자의 답변을 기록하고 분석.

  - 강점, 개선점, 추천 답변 등을 포함한 상세 보고서 제공.

OpenAI ChatCompletion API를 활용하여 답변 평가 및 피드백 생성.

4. 면접 기록 관리

  - 완료된 모든 면접 세션을 저장하여 향후 복습 가능.

  - 이전 질문, 답변 및 피드백을 다시 확인할 수 있도록 지원.

  - 기록 삭제를 통해 원하는 기록 관리 가능.

5. 사용자 인증 및 프로필 관리

  - 안전한 로그인 및 회원가입 시스템 제공.

  - 사용자별 개인화된 설정과 면접 환경 관리.

## 프로젝트 시연
데모 영상은 사용자 등록, 자기소개서 업로드, 동적 면접, 상세 보고서 등 플랫폼의 주요 기능을 시연한다.

## ER Diagram
![image](https://github.com/user-attachments/assets/d31336c5-3efd-483a-9cf2-41b5ddef1860)

## 개발요약 
개발 기간: 2.5개월

팀 역할:

frontend: 모바일 앱 인터페이스 디자인 및 클라이언트 연동.

backend: 서버 통합 및 데이터베이스 설계.

AI: 프롬프트 엔지니어링, Assistant와 chatcompletion ,login등 개별 서버개발 및 시스템 아키텍처 설계.

워크플로우: 매주 2회 이상의 팀 회의를 통해 개발 진행 및 문제 해결.

## 프로젝트 참여멤버
정현정 : 프로젝트 기획, AI파트 담당

유시연 : frontend

전지연 : backend



소속: 성신여자대학교 


