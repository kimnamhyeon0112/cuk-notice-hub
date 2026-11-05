# 🤖 가톨릭대학교 공지 통합 알리미(The Catholic University of Korea Notice Hub)

## 📖 Overview
가톨릭대학교 공지 통합 알리미 서비스입니다.

가톨릭대학교에서 운영하는 각종 웹페이지에서 올라오는 공지글을 스크랩하여 하나의 웹에서 열람할 수 있는 웹서비스 입니다.

## ✨ Key Features


## 🛠 Tech Stack
- **Language**: TypeScript
- **AI Framework**: LangGraph / LangChain (에이전트 오케스트레이션)
- **Integration**: 
  - GitHub API / GitHub Actions (PR 생성 및 배포 파이프라인 연동)
  - GraphQL (필요 시 데이터 쿼리용)

## 🚀 Getting Started

### Prerequisites

**[공통]**
- Node.js (v18+) 또는 .NET SDK
- [Cursor IDE](https://cursor.sh/) (AI 바이브 코딩 권장 편집기)
- Git

**[Mac 환경]**
- [Homebrew](https://brew.sh/) (패키지 관리용)

**[Windows 환경]**
- Windows 10/11
- [winget](https://learn.microsoft.com/ko-kr/windows/package-manager/winget/) 또는 Chocolatey (패키지 관리용, 선택 사항)
- *Tip: 원활한 개발 및 스크립트 실행을 위해 [WSL2 (Windows Subsystem for Linux)](https://learn.microsoft.com/ko-kr/windows/wsl/install) 환경에서의 실행을 권장합니다.*

### Installation
```bash
# 1. Repository 클론 (Mac 터미널 / Windows PowerShell 또는 WSL 공통)
git clone [https://github.com/kimnamhyeon0112/ecommerce-issue-resolver-agent.git](https://github.com/kimnamhyeon0112/ecommerce-issue-resolver-agent.git)
cd ecommerce-issue-resolver-agent

# 2. 패키지 설치
npm install
```

## 🗺 Roadmap
[ ] Phase 1: Jira API 연동 및 RAG 기반 에러 티켓 분류 모델 구축

[ ] Phase 2: 시나리오 1 (가이드 댓글 작성 및 자동 Close) 파이프라인 완성

[ ] Phase 3: 시나리오 2 (GitHub API 연동, 코드 분석 및 PR 자동 생성) 구현

[ ] Phase 4: 시나리오 3 (쇼핑몰 문의 분기 및 Human-in-the-loop) 적용

[ ] Phase 5: GitHub Actions 연동 테스트 및 배포 자동화
