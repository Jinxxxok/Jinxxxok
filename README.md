<picture>
  <source media="(prefers-color-scheme: dark)" srcset="assets/header-dark.png">
  <img src="assets/header-light.png" alt="안혁진 · AI-Native Product Engineer — LLM 에이전트 · 데이터 파이프라인 · 실서비스 배포" width="100%">
</picture>

안녕하세요, **안혁진**입니다. LLM 에이전트와 데이터 파이프라인을 만들고 실서비스까지 배포합니다.<br>
"지어내지 마"라고 모델에게 부탁하는 대신 **도구 목록 · 자리표시자 · 기계 대조**로 코드가 규칙을 지키게 만들고,<br>
고치기 전에 재고, 목표에 못 미친 수치까지 기록합니다.

<a href="mailto:hyeokjiny01@gmail.com"><img src="https://img.shields.io/badge/hyeokjiny01%40gmail.com-2F5BFF?style=flat-square&logo=gmail&logoColor=white" alt="Email"></a> <a href="https://fee-di-t-frontend.vercel.app"><img src="https://img.shields.io/badge/FEEDiT%20Live-3A3A40?style=flat-square&logo=vercel&logoColor=white" alt="FEEDiT Live"></a>

<br>

## Selected Work

<table>
<tr>
<td width="50%" valign="top">

<a href="https://fee-di-t-frontend.vercel.app"><img src="assets/cover-feedit.png" alt="FEEDiT 데스크톱 · 모바일 화면" width="100%"></a>

### [FEEDiT](https://github.com/feedit-official/feedit)
AI 패션 트렌드 분석 & 구매 판단 플랫폼<br>
<sub>2026.08 – 10 · AI 캠프 최종 프로젝트 · 5인 · AI 챗봇 에이전트 + Frontend</sub>

- 20개 도구로 움직이는 **LLM 에이전트** 설계
- 숫자 환각을 막는 **사실 검증 계층** (L3)
- 커밋 **136건 · 팀 1위** · 해커톤 **인기 2위**

`Django` `OpenAI` `Celery` `PostgreSQL` `Docker`

**[Live ↗](https://fee-di-t-frontend.vercel.app)** · [Repo](https://github.com/feedit-official/feedit) · [발표 사이트](https://feedit-official.github.io/feedit-presentation/)

</td>
<td width="50%" valign="top">

<a href="https://jinxxxok.github.io/eden/"><img src="assets/cover-eden.png" alt="Eden 별자리 홈 · 상담 화면" width="100%"></a>

### [Eden](https://jinxxxok.github.io/eden/)
하이브리드 RAG(Vector + Graph) 상담 챗봇<br>
<sub>2026.07 – 08 · 3 · 4차 프로젝트 · PM + Frontend</sub>

- 벡터 검색 + **Neo4j 그래프** 하이브리드 RAG
- **RAGAS**로 재고, 낮은 점수까지 원인 분석
- Streamlit → **React SPA + DRF + SSE** 재구축

`React` `TypeScript` `LangChain` `Neo4j` `pgvector`

**[Demo ↗](https://jinxxxok.github.io/eden/)** · [Repo](https://github.com/SKNETWORKS-FAMILY-AICAMP/SKN31-4th-3Team) · [3차 Repo](https://github.com/SKNETWORKS-FAMILY-AICAMP/SKN31-3rd-3Team)

</td>
</tr>
<tr>
<td width="50%" valign="top">

<a href="https://github.com/SKNETWORKS-FAMILY-AICAMP/SKN31-2nd-1Team"><img src="assets/cover-voters.png" alt="유권자들 — 기권 예측 모델링 흐름" width="100%"></a>

### [유권자들](https://github.com/SKNETWORKS-FAMILY-AICAMP/SKN31-2nd-1Team)
시군구별 투표 이탈(기권) 예측<br>
<sub>2026.05 – 06 · 2차 프로젝트 · 5인 · ML/DL 모델링 · 전처리</sub>

- 개표 · 인구 · 설문 데이터 정규화 · 피처 생성
- 정답이 새는 **누수(Leakage) 피처** 탐지 · 제거
- Ridge → Lasso · LightGBM, **RMSE · R²** 평가

`Python` `scikit-learn` `LightGBM` `Pandas`

**[Repo ↗](https://github.com/SKNETWORKS-FAMILY-AICAMP/SKN31-2nd-1Team)**

</td>
<td width="50%" valign="top">

<a href="https://github.com/Parkdongkwan/Brainslap"><img src="assets/cover-brainslap.png" alt="BrainSlap — 개입 단계" width="100%"></a>

### [BrainSlap](https://github.com/Parkdongkwan/Brainslap)
LLM 페르소나가 잔소리로 집중을 지키는 크롬 확장<br>
<sub>2026.07 · 제8회 K-디지털 트레이닝 해커톤 출품 · 사용자 행동 제어 파트</sub>

- 딴 페이지 5초 체류 → **LLM이 판정** → 개입
- **개입 메커니즘 10종** — DM → 채팅 → 화면 점령
- 읽씹하면 **강도 +1**로 잔소리를 다시 생성

`Chrome MV3` `JavaScript` `Flask` `LangChain`

**[Repo ↗](https://github.com/Parkdongkwan/Brainslap)**

</td>
</tr>
</table>

## Tech Stack

<table>
<tr><td width="130"><b>AI · LLM</b></td><td><img src="https://img.shields.io/badge/OpenAI%20API-F3F4F7?style=flat-square&logo=data:image/svg+xml;base64,PHN2ZyBmaWxsPSIjMDAwMDAwIiAgZmlsbC1ydWxlPSJldmVub2RkIiBoZWlnaHQ9IjFlbSIgc3R5bGU9ImZsZXg6bm9uZTtsaW5lLWhlaWdodDoxIiB2aWV3Qm94PSIwIDAgMjQgMjQiIHdpZHRoPSIxZW0iIHhtbG5zPSJodHRwOi8vd3d3LnczLm9yZy8yMDAwL3N2ZyI+PHRpdGxlPk9wZW5BSTwvdGl0bGU+PHBhdGggZD0iTTkuMjA1IDguNjU4di0yLjI2YzAtLjE5LjA3Mi0uMzMzLjIzOC0uNDI4bDQuNTQzLTIuNjE2Yy42MTktLjM1NyAxLjM1Ni0uNTIzIDIuMTE3LS41MjMgMi44NTQgMCA0LjY2MiAyLjIxMiA0LjY2MiA0LjU2NiAwIC4xNjcgMCAuMzU3LS4wMjQuNTQ3bC00LjcxLTIuNzU5YS43OTcuNzk3IDAgMDAtLjg1NiAwbC01Ljk3IDMuNDczem0xMC42MDkgOC44VjEyLjA2YzAtLjMzMy0uMTQzLS41Ny0uNDI5LS43MzdsLTUuOTctMy40NzMgMS45NS0xLjExOGEuNDMzLjQzMyAwIDAxLjQ3NiAwbDQuNTQzIDIuNjE3YzEuMzA5Ljc2IDIuMTg5IDIuMzc4IDIuMTg5IDMuOTQ4IDAgMS44MDgtMS4wNyAzLjQ3My0yLjc2IDQuMTYzek03LjgwMiAxMi43MDNsLTEuOTUtMS4xNDJjLS4xNjctLjA5NS0uMjM5LS4yMzgtLjIzOS0uNDI4VjUuODk5YzAtMi41NDUgMS45NS00LjQ3MiA0LjU5MS00LjQ3MiAxIDAgMS45MjcuMzMzIDIuNzEyLjkyOEw4LjIzIDUuMDY3Yy0uMjg1LjE2Ni0uNDI4LjQwNC0uNDI4LjczN3Y2Ljg5OHpNMTIgMTUuMTI4bC0yLjc5NS0xLjU3di0zLjMzTDEyIDguNjU4bDIuNzk1IDEuNTd2My4zM0wxMiAxNS4xMjh6bTEuNzk2IDcuMjNjLTEgMC0xLjkyNy0uMzMyLTIuNzEyLS45MjdsNC42ODYtMi43MTJjLjI4NS0uMTY2LjQyOC0uNDA0LjQyOC0uNzM3di02Ljg5OGwxLjk3NCAxLjE0MmMuMTY3LjA5NS4yMzguMjM4LjIzOC40Mjh2NS4yMzNjMCAyLjU0NS0xLjk3NCA0LjQ3Mi00LjYxNCA0LjQ3MnptLTUuNjM3LTUuMzAzbC00LjU0NC0yLjYxN2MtMS4zMDgtLjc2MS0yLjE4OC0yLjM3OC0yLjE4OC0zLjk0OEE0LjQ4MiA0LjQ4MiAwIDAxNC4yMSA2LjMyN3Y1LjQyM2MwIC4zMzMuMTQzLjU3MS40MjguNzM4bDUuOTQ3IDMuNDQ5LTEuOTUgMS4xMThhLjQzMi40MzIgMCAwMS0uNDc2IDB6bS0uMjYyIDMuOWMtMi42ODggMC00LjY2Mi0yLjAyMS00LjY2Mi00LjUxOSAwLS4xOS4wMjQtLjM4LjA0Ny0uNTdsNC42ODYgMi43MWMuMjg2LjE2Ny41NzEuMTY3Ljg1NiAwbDUuOTctMy40NDh2Mi4yNmMwIC4xOS0uMDcuMzMzLS4yMzcuNDI4bC00LjU0MyAyLjYxNmMtLjYxOS4zNTctMS4zNTYuNTIzLTIuMTE3LjUyM3ptNS44OTkgMi44M2E1Ljk0NyA1Ljk0NyAwIDAwNS44MjctNC43NTZDMjIuMjg3IDE4LjMzOSAyNCAxNS44NCAyNCAxMy4yOTZjMC0xLjY2NS0uNzEzLTMuMjgyLTEuOTk4LTQuNDQ4LjExOS0uNS4xOS0uOTk5LjE5LTEuNDk4IDAtMy40MDEtMi43NTktNS45NDctNS45NDYtNS45NDctLjY0MiAwLTEuMjYuMDk1LTEuODguMzFBNS45NjIgNS45NjIgMCAwMDEwLjIwNSAwYTUuOTQ3IDUuOTQ3IDAgMDAtNS44MjcgNC43NTdDMS43MTMgNS40NDcgMCA3Ljk0NSAwIDEwLjQ5YzAgMS42NjYuNzEzIDMuMjgzIDEuOTk4IDQuNDQ4LS4xMTkuNS0uMTkgMS0uMTkgMS40OTkgMCAzLjQwMSAyLjc1OSA1Ljk0NiA1Ljk0NiA1Ljk0Ni42NDIgMCAxLjI2LS4wOTUgMS44OC0uMzA5YTUuOTYgNS45NiAwIDAwNC4xNjIgMS43MTN6Ij48L3BhdGg+PC9zdmc+" alt="OpenAI API"> <img src="https://img.shields.io/badge/LangChain-F3F4F7?style=flat-square&logo=langchain&logoColor=1C3C3C" alt="LangChain"> <img src="https://img.shields.io/badge/Neo4j-F3F4F7?style=flat-square&logo=neo4j&logoColor=4581C3" alt="Neo4j"> <img src="https://img.shields.io/badge/pgvector-F3F4F7?style=flat-square&logo=postgresql&logoColor=4169E1" alt="pgvector"> <img src="https://img.shields.io/badge/Qdrant-F3F4F7?style=flat-square&logo=qdrant&logoColor=DC244C" alt="Qdrant"> <img src="https://img.shields.io/badge/Ollama-F3F4F7?style=flat-square&logo=ollama&logoColor=000000" alt="Ollama"> <img src="https://img.shields.io/badge/Hugging%20Face-F3F4F7?style=flat-square&logo=huggingface&logoColor=FFD21E" alt="Hugging Face"></td></tr>
<tr><td width="130"><b>Backend · Data</b></td><td><img src="https://img.shields.io/badge/Python-F3F4F7?style=flat-square&logo=python&logoColor=3776AB" alt="Python"> <img src="https://img.shields.io/badge/Django%20%C2%B7%20DRF-F3F4F7?style=flat-square&logo=django&logoColor=092E20" alt="Django · DRF"> <img src="https://img.shields.io/badge/Flask-F3F4F7?style=flat-square&logo=flask&logoColor=000000" alt="Flask"> <img src="https://img.shields.io/badge/Celery-F3F4F7?style=flat-square&logo=celery&logoColor=37814A" alt="Celery"> <img src="https://img.shields.io/badge/Redis-F3F4F7?style=flat-square&logo=redis&logoColor=FF4438" alt="Redis"> <img src="https://img.shields.io/badge/PostgreSQL-F3F4F7?style=flat-square&logo=postgresql&logoColor=4169E1" alt="PostgreSQL"> <img src="https://img.shields.io/badge/MySQL-F3F4F7?style=flat-square&logo=mysql&logoColor=4479A1" alt="MySQL"> <img src="https://img.shields.io/badge/Pandas-F3F4F7?style=flat-square&logo=pandas&logoColor=150458" alt="Pandas"> <img src="https://img.shields.io/badge/scikit--learn-F3F4F7?style=flat-square&logo=scikitlearn&logoColor=F7931E" alt="scikit-learn"> <img src="https://img.shields.io/badge/PyTorch-F3F4F7?style=flat-square&logo=pytorch&logoColor=EE4C2C" alt="PyTorch"></td></tr>
<tr><td width="130"><b>Frontend</b></td><td><img src="https://img.shields.io/badge/React-F3F4F7?style=flat-square&logo=react&logoColor=61DAFB" alt="React"> <img src="https://img.shields.io/badge/TypeScript-F3F4F7?style=flat-square&logo=typescript&logoColor=3178C6" alt="TypeScript"> <img src="https://img.shields.io/badge/JavaScript-F3F4F7?style=flat-square&logo=javascript&logoColor=F7DF1E" alt="JavaScript"> <img src="https://img.shields.io/badge/Vite-F3F4F7?style=flat-square&logo=vite&logoColor=646CFF" alt="Vite"> <img src="https://img.shields.io/badge/Next.js-F3F4F7?style=flat-square&logo=nextdotjs&logoColor=000000" alt="Next.js"> <img src="https://img.shields.io/badge/Tailwind%20CSS-F3F4F7?style=flat-square&logo=tailwindcss&logoColor=06B6D4" alt="Tailwind CSS"> <img src="https://img.shields.io/badge/Streamlit-F3F4F7?style=flat-square&logo=streamlit&logoColor=FF4B4B" alt="Streamlit"></td></tr>
<tr><td width="130"><b>Infra · Tools</b></td><td><img src="https://img.shields.io/badge/AWS%20EC2%20%C2%B7%20RDS%20%C2%B7%20S3-F3F4F7?style=flat-square&logo=data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjAgNzAgMTI4IDM0Ij48cGF0aCBmaWxsPSIjZjkwIiBkPSJNMTE4IDczLjM0OGMtNC40MzIuMDYzLTkuNjY0IDEuMDUyLTEzLjYyMSAzLjgzMi0xLjIyMy44ODMtMS4wMTIgMi4wNjIuMzM2IDEuODk0IDQuNTA4LS41NDcgMTQuNDQtMS43MjYgMTYuMjEuNTQ3IDEuNzcgMi4yMy0xLjk3NiAxMS42Mi0zLjY2MyAxNS43OS0uNTA0IDEuMjYuNTkgMS43NjkgMS43MjYuOCA3LjQxLTYuMjMxIDkuMzQ4LTE5LjI0MiA3LjgzMi0yMS4xMzctLjc1Ny0uOTI1LTQuMzg4LTEuNzktOC44Mi0xLjcyNnpNMS42MyA3NS44NTljLS45MjYuMTE2LTEuMzQ3IDEuMjM2LS4zNjggMi4xMjEgMTYuNTA4IDE0LjkwMiAzOC4zNTkgMjMuODcyIDYyLjYxMyAyMy44NzIgMTcuMzA1IDAgMzcuNDMtNS40MyA1MS4yODEtMTUuNjYgMi4yNzMtMS42ODkuMjk4LTQuMjU0LTIuMDItMy4yMDQtMTUuNTMzIDYuNTctMzIuNDIxIDkuNzctNDcuNzg4IDkuNzctMjIuNzc4IDAtNDQuOC02LjI3My02Mi42NTMtMTYuNjMzLS4zOS0uMjMxLS43NTUtLjMwNC0xLjA2NC0uMjY2eiIvPjwvc3ZnPg==" alt="AWS EC2 · RDS · S3"> <img src="https://img.shields.io/badge/Docker-F3F4F7?style=flat-square&logo=docker&logoColor=2496ED" alt="Docker"> <img src="https://img.shields.io/badge/nginx-F3F4F7?style=flat-square&logo=nginx&logoColor=009639" alt="nginx"> <img src="https://img.shields.io/badge/GitHub%20Actions-F3F4F7?style=flat-square&logo=githubactions&logoColor=2088FF" alt="GitHub Actions"> <img src="https://img.shields.io/badge/Vercel-F3F4F7?style=flat-square&logo=vercel&logoColor=000000" alt="Vercel"> <img src="https://img.shields.io/badge/Supabase-F3F4F7?style=flat-square&logo=supabase&logoColor=3FCF8E" alt="Supabase"> <img src="https://img.shields.io/badge/Claude%20Code-F3F4F7?style=flat-square&logo=claude&logoColor=D97757" alt="Claude Code"></td></tr>
</table>

## Highlights

- **원티드 AI 챔피언십 2026 해커톤** — FEEDiT 출품, 커머스/쇼핑 부문 인기 2위
- **제8회 K-디지털 트레이닝 해커톤 (2026)** — BrainSlap 출품
- **SK네트웍스 Family AI 캠프 31기** 수료 — 960시간 · 팀 프로젝트 5개 · PM 3회
- **프로그래머스 PCCE Lv.3** · 정보처리기사 필기 합격
- [니차내차](https://github.com/SKNETWORKS-FAMILY-AICAMP/SKN31-1st-4Team) — 중고차 시세 조회 서비스, 첫 팀 프로젝트 PM (팀 커밋 72건 중 50건)
- [AI-STUDY](https://github.com/Jinxxxok/AI-STUDY) — 파이썬 → 데이터 분석 → ML/DL → LLM 학습 기록, 커밋 100건+

<br>

<p align="right"><sub>안혁진 · <a href="mailto:hyeokjiny01@gmail.com">hyeokjiny01@gmail.com</a></sub></p>
