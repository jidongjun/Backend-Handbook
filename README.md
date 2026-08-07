# Backend Interview Bible

> Java 백엔드 개발자를 위한 실무·운영·면접 중심의 Obsidian 기술 핸드북

## 프로젝트 소개

Backend Interview Bible은 단순한 기술 노트가 아니라 Java 백엔드 개발자가 실무 역량과 기술 면접을 함께 준비하기 위한 장기 지식 베이스다.

각 문서는 개념 정의에 그치지 않고 다음을 연결해서 설명한다.

- 기술이 등장한 배경과 해결하려는 문제
- 내부 동작 원리와 구현상의 경계
- 장단점과 설계 트레이드오프
- 성능, 메모리, 동시성 영향
- 운영 장애와 문제 해결 절차
- 실무 활용 사례와 모범 사례
- 면접 질문, 후속 질문, 시니어 수준의 답변

## 대상 독자

- Java 및 Spring 백엔드 개발자
- 약 8~10년 수준의 운영 경험을 체계화하려는 개발자
- 대기업·금융 IT·플랫폼 기업의 기술 면접 준비자
- JVM, Database, Network, System Design을 깊이 학습하려는 개발자
- Obsidian과 GitHub로 장기 기술 문서를 관리하려는 개발자

## 기술 기준

| 항목 | 기본 기준 |
|---|---|
| Java | 17 LTS |
| Spring Framework | 6.x |
| Spring Boot | 3.x |
| JPA 구현 | Hibernate 6.x |
| Build Tool | Gradle Kotlin DSL 권장 |
| 저장 형식 | UTF-8 Markdown |

Java 21 이상의 기능은 해당 주제에서 버전을 명시해 별도로 설명할 수 있다. 세부 버전과 구현 동작은 로컬에서 검증할 수 없는 경우 단정하지 않는다.

## 프로젝트 구조

```text
Backend Handbook/
├── AGENTS.md
├── README.md
├── PROBLEM-INDEX.md
├── HANDBOOK-INDEX.md
├── ROADMAP.md
├── CODEX-PROMPT-GUIDE.md
├── 01-Java-Core/
├── 02-Spring/
├── 03-Database/
├── 04-Data-Structure/
├── 05-Algorithm/
├── 06-JVM/
├── 07-Network/
├── 08-Operating-System/
├── 09-System-Design/
├── 10-Project-Experience/
├── 11-Behavioral/
└── assets/
    ├── images/
    └── diagrams/
```

Git은 빈 디렉터리를 추적하지 않는다. 아직 장이 없는 볼륨의 `KEEP.txt`와 `.gitkeep`은 GitHub에서 폴더 구조를 유지하기 위한 관리 파일이며 핸드북 장이 아니다.

## 볼륨 안내

| 볼륨 | 내용 |
|---|---|
| `01-Java-Core` | Java 언어, 표준 라이브러리, 컬렉션, 동시성 |
| `02-Spring` | Spring Framework, Spring Boot, JPA, Hibernate |
| `03-Database` | 관계형 데이터베이스, SQL, 트랜잭션, 잠금, 성능 |
| `04-Data-Structure` | 자료구조 이론과 구현 트레이드오프 |
| `05-Algorithm` | 알고리즘, 복잡도, 문제 해결 기법 |
| `06-JVM` | JVM 구조, 메모리, GC, JIT, 튜닝 |
| `07-Network` | TCP/IP, HTTP, TLS, DNS, 서버 통신 |
| `08-Operating-System` | 프로세스, 스레드, 메모리, 스케줄링, I/O |
| `09-System-Design` | 분산 시스템, 확장성, 신뢰성, 관측 가능성 |
| `10-Project-Experience` | 운영 장애, 마이그레이션, 최적화, 프로젝트 경험 |
| `11-Behavioral` | 리더십, 협업, 커뮤니케이션, Ownership |

## 핵심 운영 문서

| 문서 | 역할 |
|---|---|
| [[AGENTS]] | Codex와 AI가 반드시 따라야 하는 영구 프로젝트 규칙 |
| [[PROBLEM-INDEX]] | 001~350번 주제, 난이도와 작성 상태 관리 |
| [[HANDBOOK-INDEX]] | 실제로 생성된 장을 볼륨별로 탐색하는 목차 |
| [[ROADMAP]] | 볼륨별 장기 계획과 구조 관리 |
| [[CODEX-PROMPT-GUIDE]] | 최초 설정, 번호 생성, 검토 및 완료 처리용 프롬프트 |

## 문제 상태

| 상태 | 의미 |
|---|---|
| ⬜ | 미작성 |
| 🟨 | 문서 생성 및 자체 검증을 마친 초안 |
| 🟩 | 기술 검토와 최종 검증을 마친 완료 문서 |
| 🔁 | 수정 필요 |
| ⭐ | 즐겨찾기 |
| ❓ | 복습 필요 |

기본 상태 전이는 다음과 같다.

```text
⬜ → 문서 하나 생성 및 자체 검증 → 🟨
🟨 → 기술 리뷰와 수정 및 최종 검증 → 🟩
검토 중 문제 발견 → 🔁
```

## Codex 사용법

새 PC나 새 Codex 세션에서는 먼저 [[CODEX-PROMPT-GUIDE#1 최초 실행 프롬프트|최초 실행 프롬프트]]를 사용한다.

환경 확인이 끝난 뒤에는 다음처럼 요청할 수 있다.

```text
003번 생성
```

```text
next
```

```text
status
```

- `NNN번 생성`: `PROBLEM-INDEX.md`의 해당 번호 하나만 생성
- `next`: 상태가 `⬜`인 가장 빠른 번호 하나만 생성
- `status`: 전체 문제와 상태별 개수, 현재 초안, 다음 미작성 번호 확인

한 번의 생성 요청에서는 장 하나만 작성한다. 파일이 이미 존재하거나 인덱스 상태와 실제 파일이 충돌하면 덮어쓰지 않고 작업을 중단한다.

## 문서 생성 워크플로우

1. `AGENTS.md`, `README.md`, `PROBLEM-INDEX.md`를 확인한다.
2. 요청 번호의 주제와 상태를 확인한다.
3. 동일 번호, 동일 파일명과 유사 주제 문서를 검색한다.
4. 실제 폴더 구조에 맞는 저장 위치를 결정한다.
5. 한국어 UTF-8 Markdown 장 하나를 생성한다.
6. 기술 내용, 코드, Markdown, Mermaid와 Wiki Link를 자체 검증한다.
7. 성공한 경우 해당 번호 상태만 `⬜ → 🟨`로 변경한다.
8. `HANDBOOK-INDEX.md`의 올바른 볼륨과 `Recently Added`를 갱신한다.
9. 외부 기술 검토와 수정이 끝난 후에만 `🟨 → 🟩`로 변경한다.

자세한 실행 프롬프트는 [[CODEX-PROMPT-GUIDE]]를 참고한다.

## 품질 기준

모든 장은 [[01-Java-Core/001-Java-Architecture|Java 아키텍처]] 문서를 기본 품질 기준으로 삼는다.

- 정확성과 검증 가능성을 우선한다.
- Java 명세, JVM 구현, Framework 동작과 일반적인 구현 선택을 구분한다.
- 운영 사고나 벤치마크 수치, 특정 회사 질문을 만들어 내지 않는다.
- 실무 사례가 가상이면 예시임을 밝힌다.
- 존재하거나 명시적으로 계획된 문서에만 Obsidian Wiki Link를 추가한다.
- 주제와 관련 없는 Spring 예제나 빈 템플릿 섹션을 억지로 넣지 않는다.

## Obsidian과 GitHub 사용

이 디렉터리를 Obsidian에서 **Open folder as vault**로 연다. 문서 작성 전에 원격 변경을 Pull하고, 작업이 끝나면 Commit과 Push를 수행한다.

권장 흐름은 다음과 같다.

```text
GitHub Desktop에서 Pull
→ Obsidian 또는 Codex에서 문서 작업
→ 변경 내용 확인
→ Commit
→ Push origin
```

다른 PC에서는 GitHub 저장소를 Clone한 뒤 Clone된 폴더를 Obsidian Vault로 열면 된다. 여러 PC에서 같은 파일을 동시에 수정하면 충돌할 수 있으므로 작업 시작 전 Pull을 습관화한다.

## Navigation

- [[HANDBOOK-INDEX|완성된 문서 목차]]
- [[PROBLEM-INDEX|전체 문제 목록과 상태]]
- [[ROADMAP|전체 작성 로드맵]]
- [[CODEX-PROMPT-GUIDE|Codex 프롬프트 가이드]]
- [[AGENTS|문서 작성 및 관리 규칙]]

## 라이선스

이 프로젝트는 개인 학습 및 기술 문서 작성을 목적으로 한다. 외부 공개와 재사용 범위는 저장소에 별도 라이선스를 추가해 관리한다.
