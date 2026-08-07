# Backend Interview Bible

> Java 백엔드 개발자를 위한 실무 중심 기술 핸드북 프로젝트

---

# 프로젝트 소개

Backend Interview Bible은 단순한 기술 노트가 아닙니다.

Java 백엔드 개발자가 실무 역량과 기술 면접을 동시에 준비할 수 있도록 만드는 장기 프로젝트입니다.

이 저장소의 모든 문서는 다음 목표를 가지고 작성됩니다.

- 실무에서 사용하는 기술 이해
- 기술 면접 대비
- 운영 환경(Production) 관점 이해
- 백엔드 아키텍처 이해
- 지속적으로 성장 가능한 기술 문서 구축

---

# 프로젝트 목표

이 프로젝트의 최종 목표는 다음과 같습니다.

- Java 백엔드 핵심 기술 정리
- Spring 생태계 정리
- JVM 심화 학습
- 운영 경험(Production Experience) 정리
- 시스템 설계(System Design) 정리
- 기술 면접 대비

최종적으로 하나의 백엔드 기술 핸드북을 완성하는 것을 목표로 합니다.

---

# 프로젝트 특징

이 프로젝트는 일반적인 기술 블로그와 다릅니다.

모든 문서는 다음 기준을 만족해야 합니다.

- 왜(Why)를 설명한다.
- 어떻게(How)를 설명한다.
- 언제 사용하는지 설명한다.
- 언제 사용하면 안 되는지 설명한다.
- 실무 사례를 설명한다.
- 운영 중 발생하는 문제를 설명한다.
- 성능 관점을 설명한다.
- 기술 면접 질문을 포함한다.

---

# 대상 독자

다음과 같은 개발자를 대상으로 합니다.

- Java 백엔드 개발자
- Spring 개발자
- 취업 준비생
- 이직 준비 중인 개발자
- 기술 면접 준비생
- 백엔드 아키텍처를 공부하는 개발자

---

# 기술 스택

기본 기준은 다음과 같습니다.

| 항목 | 버전 |
|------|------|
| Java | 17 LTS |
| Spring Framework | 6.x |
| Spring Boot | 3.x |
| JPA | Hibernate 6+ |
| Build Tool | Gradle(Kotlin DSL 권장) |

필요한 경우 Java 21 이상의 기능은 별도 섹션에서 설명합니다.

---

# 문서 구성

예시

```text
01-Java-Core
02-JVM
03-Collections
04-Concurrency
05-Spring
06-Spring-Boot
07-JPA
08-Database
09-Redis
10-Kafka
11-System-Design
12-Architecture
...
```

---

# 문서 작성 원칙

모든 문서는 다음 원칙을 따릅니다.

- 정확성을 최우선으로 한다.
- 실무 중심으로 설명한다.
- 운영 환경 관점을 포함한다.
- 성능을 고려한다.
- 단순 정의보다 동작 원리를 설명한다.
- 코드 예제를 포함한다.
- 기술 면접 관점에서 설명한다.

---

# 프로젝트 구조

```text
Backend-Interview-Bible/

README.md
AGENTS.md
STYLE-GUIDE.md
PROMPT.md
CODEX-WORKFLOW.md
QUALITY-CHECKLIST.md
CODEX-PROMPT-GUIDE.md

PROBLEM-INDEX.md
HANDBOOK-INDEX.md

01-Java-Core/
02-JVM/
03-Collections/
04-Concurrency/
05-Spring/
06-Spring-Boot/
...
```

---

# 문서 관리

## PROBLEM-INDEX.md

작성해야 할 문서를 관리합니다.

상태는 다음과 같습니다.

| 상태 | 의미 |
|------|------|
| ⬜ | 미작성 |
| 🟨 | 문서 생성 완료 |
| 🟩 | ChatGPT 기술 검토 완료 |

---

## HANDBOOK-INDEX.md

생성된 문서를 관리합니다.

폴더별 문서 목록과 링크를 제공합니다.

---

# 문서 생성 프로세스

문서는 다음 순서로 작성됩니다.

1. 작성 대상 선정
2. 기존 문서 중복 확인
3. 문서 생성
4. 자가 검토(Self Review)
5. ChatGPT 기술 검토
6. 수정
7. Git Commit

---

# 품질 기준

모든 문서는 **001. Java Architecture** 문서를 기준(Baseline)으로 합니다.

새로운 문서는 최소한 다음 수준 이상의 품질을 유지해야 합니다.

- 기술적 깊이
- 실무 활용성
- 운영 경험
- 성능 분석
- 기술 면접 활용도

---

# 저장소 운영 문서

| 문서 | 설명 |
|------|------|
| AGENTS.md | 프로젝트 운영 규칙 |
| STYLE-GUIDE.md | 문서 작성 규칙 |
| PROMPT.md | Codex 작업 지침 |
| CODEX-WORKFLOW.md | 문서 생성 절차 |
| QUALITY-CHECKLIST.md | 품질 검증 기준 |
| CODEX-PROMPT-GUIDE.md | 프롬프트 예제 |

---

# 라이선스

본 프로젝트는 개인 학습 및 기술 문서 작성을 목적으로 합니다.

필요에 따라 라이선스를 추가하여 관리합니다.