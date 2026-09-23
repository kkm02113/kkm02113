<div align="center">

# Kim Kangmin

### Backend / AI Application Engineer

**AI 기능을 실제 서비스의 API, 데이터베이스, 검색, 문서 생성 및 운영 흐름으로 연결합니다.**

Python · FastAPI · PostgreSQL · pgvector · RAG · Next.js · AWS

<br/>

<a href="https://github.com/kkm02113">
  <img src="https://img.shields.io/badge/GitHub-kkm02113-181717?style=flat-square&logo=github&logoColor=white" />
</a>

</div>

---

## About Me

한림대학교에서 소프트웨어·빅데이터 분야를 전공하고 있으며,  
**Backend Engineering과 AI Application Engineering**을 중심으로 개발하고 있습니다.

단순히 LLM API를 호출하는 기능 구현보다,

- AI 기능을 실제 서비스의 Backend / Database와 연결하고
- RAG 기반 검색 및 문서 처리 파이프라인을 설계하고
- 테스트와 예외 처리를 통해 서비스 안정성을 높이고
- 실제 사용 가능한 형태로 배포하는 과정

에 관심을 두고 있습니다.

현재는 대학 행정업무를 위한 **RAG 기반 지식검색 및 문서 자동생성 시스템** 개발에 참여하고 있습니다.

---

## Tech Stack

### Languages

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![Java](https://img.shields.io/badge/Java-007396?style=flat-square&logo=openjdk&logoColor=white)

### Backend & Database

![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![Supabase](https://img.shields.io/badge/Supabase-3FCF8E?style=flat-square&logo=supabase&logoColor=white)

### AI & Data

![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white)
![OpenAI](https://img.shields.io/badge/OpenAI_API-412991?style=flat-square&logo=openai&logoColor=white)

`RAG` · `Hybrid Retrieval` · `pgvector` · `LLM Application`

### Cloud & DevOps

![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat-square&logo=amazonwebservices&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Nginx](https://img.shields.io/badge/Nginx-009639?style=flat-square&logo=nginx&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white)

---

# Selected Projects

## 01. UniDocs AI

> **RAG 기반 대학 행정 지식검색 및 문서 자동생성 플랫폼**

한림대학교 대학 행정업무를 대상으로  
행정문서 검색, 근거 기반 질의응답, 문서 자동생성을 제공하는 프로젝트입니다.

**Role**  
Backend / DocsGen

**Project Stack**

`Python` `FastAPI` `PostgreSQL` `pgvector` `Next.js` `LLM` `AWS`

### What I Worked On

- 대학 행정문서 자동생성 기능 **DocsGen** 개발
- 행정양식 기반 문서 생성 및 출력 구조 구현
- Draft → Review/Edit → Finalize 형태의 문서 생성 흐름 설계
- HWPX 기반 문서의 표 / 셀 병합 / 필드 배치 등 양식 보존 개선
- 생성 결과의 품질 검증 및 예외 처리
- 자동화 테스트를 활용한 생성 기능 안정화

### Project Architecture

```text
University Documents
        ↓
Parsing / Chunking
        ↓
Embedding
        ↓
Dense + Sparse Retrieval
        ↓
RRF / Hybrid Search
        ↓
LLM
        ↓
Grounded Answer / Document Generation
