<div align="center">

# 김강민 | Kangmin Kim

### Backend Engineer · AI Application

**LLM을 API로 호출하는 데서 끝내지 않고, 검색 · 데이터 · 문서 생성 · 테스트 · 배포까지 연결해 실제 서비스로 만드는 개발자입니다.**

`Python` · `FastAPI` · `PostgreSQL` · `pgvector` · `RAG` · `Next.js` · `AWS`

</div>

---

## 👋 About Me

한림대학교에서 소프트웨어·빅데이터 분야를 공부하고 있는 4학년 개발자입니다.

현재는 **Backend Engineering과 AI Application Engineering**에 집중하고 있으며, 특히 다음과 같은 문제를 다루는 데 관심이 있습니다.

- LLM 기능을 실제 서비스의 API / Database와 연결하기
- RAG와 Hybrid Retrieval로 검색 품질과 근거성을 높이기
- 템플릿 기반 문서 생성처럼 **형식과 정확성이 중요한 AI 기능** 만들기
- 테스트, fallback, 예외 처리로 AI 기능을 안정적인 서비스로 만들기
- 트래픽과 병목을 측정하고 Backend Architecture를 개선하기

> **Current Focus:** RAG · Document Generation · Backend Reliability · System Architecture

---

## 🧩 What I Build

| AI Backend | Retrieval & Data | Production Engineering |
| :--- | :--- | :--- |
| FastAPI, LLM Integration, Document Generation | PostgreSQL, pgvector, Hybrid Retrieval | Docker, AWS, CI/CD, Testing |
| AI 기능을 서비스 로직으로 연결 | 검색 결과의 근거성과 품질 개선 | 실패 가능성을 고려한 안정적인 서비스 구현 |

---

## 🛠 Tech Stack

### Core

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)

### AI / Data

`RAG` `Hybrid Retrieval` `pgvector` `LLM Application` `PyTorch`

### Infra / DevOps

![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat-square&logo=amazonwebservices&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Nginx](https://img.shields.io/badge/Nginx-009639?style=flat-square&logo=nginx&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white)

---

# 🚀 Featured Projects

## 01. UniDocs AI

> **대학 행정 문서를 검색하고, 근거 기반 답변과 행정문서 자동생성을 제공하는 RAG 플랫폼**

**Project**

대학의 규정·학칙·지침 문서를 자연어로 검색하고, 출처가 포함된 답변과 행정문서 생성 기능을 제공하는 프로젝트입니다.

**My Role — DocsGen / Backend**

- 대학 행정문서 자동생성 기능 **DocsGen** 개발
- 문서 생성 과정을 `Draft → Review/Edit → Finalize` 흐름으로 구조화
- 템플릿 기반 행정양식 생성 및 출력 구조 개선
- 표·셀 병합·필드 위치 등 **레이아웃 보존이 중요한 문서 생성 문제** 대응
- 생성 실패 및 출력 오류를 고려한 validation / fallback 흐름 개선
- 자동 테스트와 acceptance validation을 활용한 생성 기능 안정화

**Project Context**

`FastAPI` · `PostgreSQL / pgvector` · `Hybrid Retrieval` · `Next.js` · `AWS` · `LLM`

```text
University Documents
        ↓
Parsing / Chunking
        ↓
Embedding + Hybrid Retrieval
        ↓
LLM / Grounded Answer
        ↓
DocsGen
        ↓
Draft → Review → Finalize → Document Output
