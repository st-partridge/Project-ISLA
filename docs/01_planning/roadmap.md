# 🗺️ ISLA Renewal Roadmap (Python Worker Integration)

> **프로젝트 목표:** Python Worker가 적용된 ISLA Renewal 버전의 부분 시연  
> **총 기간:** 5 Sprints + Demo Day

## 🏃 Current Sprint (Sprint 2)
**주제: Technical Design & Architecture**
- **기간:** 2025.12.29 ~ 2026.01.09
- **상태:** 진행 중 (In Progress)
- **목표:** 개발 착수 전, 기술적 명세(API, DB) 확정 및 개발 환경(CI/CD) 구축

### 📝 To-Do (Action Items)
- **Architecture**
  - [ ] FE 아키텍처 설계 및 기술 스택 확정 (#이슈번호)
  - [ ] BE 아키텍처 설계 (Python Worker 구조 포함) `docs/02_design/architecture.md`
  - [ ] `docs/assets`에 Context Diagram 등록 (#이슈번호)

- **Documentation & Rules**
  - [ ] API 명세서 초안 작성 (Swagger/Docs) `docs/02_design/api_spec.md`
  - [ ] 코드 컨벤션 및 브랜치 전략 수립 `docs/03_development/convention.md`

- **DevOps**
  - [ ] GitHub Actions 기반 CI/CD 파이프라인 구축
  - [ ] 배포 환경(Dev/Stage) 구성

## 🔮 Upcoming Sprints

### Sprint 3: 구현 (Implementation)
**주제: Core Features & Worker Logic**
- 핵심 기능 개발 (FE/BE)
- Python Worker 연동 및 비동기 처리 로직 구현
- DB 마이그레이션 및 데이터 연동

### Sprint 4: 검증 및 보완 (QA & Refinement)
**주제: Stabilization**
- 통합 테스트 (Integration Test)
- 버그 수정 및 성능 최적화 (Worker 처리 속도 개선 등)
- UI/UX 폴리싱 (디테일 수정)

### Sprint 5: 데모 준비 (Demo Prep)
**주제: Packaging & Rehearsal**
- 배포 패키징 및 최종 환경 점검
- 시연 시나리오 작성 및 리허설
- 데모 데이터(Mock Data) 세팅

## 🚩 Milestone

### 📅 Demo Day
- **일정:** 2025.02.23 (Sprint 5 종료 후)
- **내용:** ISLA Renewal 버전 부분 시연 (Stakeholders 대상)

## ✅ History (Completed)

### Sprint 1: 기획 (Planning & Design)
**주제: Requirements & UI/UX**
- [x] 프로젝트 요구사항 정의 (ISLA Renewal 범위 설정)
- [x] 주요 기능 기획 및 정책 수립
- [x] UI/UX 와이어프레임 및 디자인 시안 도출