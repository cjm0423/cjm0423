# 차지만 (Cha Jiman)

인프라 위에서 **데이터와 AI 시스템이 안정적으로 동작하는 구조**에 관심이 많은 백엔드·인프라 지향 개발자입니다.
"잘 만든 시스템"보다 "왜 느린지 설명할 수 있는 시스템"을 만드는 데 시간을 씁니다.

- 🎓 삼육대학교 컴퓨터공학부 4학년
- 📄 KSCI 학술지 게재 — *대규모 실시간 데이터 파이프라인의 End-to-End 지연시간 최적화* (2026)
- 🔧 관심 분야: Infra / DevOps · OpenStack · 데이터 파이프라인 · Cloud

---

## 📌 대표 프로젝트

> 프로젝트 코드는 팀·조직 저장소에 있습니다. 각 제목에서 원본으로 이동할 수 있습니다.

### 1. 실시간 데이터 파이프라인 — End-to-End ([↗ 저장소](https://github.com/kakaocloud-edu/tutorial/tree/main/DataAnalyzeCourse))
**KakaoCloud 공식 교육 콘텐츠**(★25)에 포함된 실시간 데이터 파이프라인 실습 코스를 설계·구현.
- **수집 → CDC 처리 → ML 학습·서빙**까지 전 구간 아키텍처 설계
- Kafka·Kafka Connect·Debezium(CDC)로 이종 소스를 단일 스트림으로 통합
- PySpark(Structured Streaming)+Delta Lake로 스트리밍·배치 통합 처리
- Kubeflow 파이프라인 학습 → KServe 서빙까지 자동화
- `KakaoCloud` `Kafka` `Spark` `Hadoop` `Kubeflow` `KServe` `Python` `Go`

### 2. 정부 정책 개인화 추천 AI 챗봇 (캡스톤·팀장) ([↗ 저장소](https://github.com/26-1capstone-design2))
LangChain·RAG 기반으로 사용자 질의에 맞는 정책 문서를 검색해 LLM이 답변을 생성하는 서비스.
- 정책 데이터 수집(scrapper) → AI 서비스(aiservice) → 백엔드(Java)·프론트(TS)로 이어지는 풀스택 구성
- 검색 정확도와 응답 품질을 함께 끌어올리는 것이 핵심 과제
- `LangChain` `RAG` `Python` `Java` `TypeScript`

### 3. ONE WAVE — 취업 준비 청년을 위한 면접 회고·정서 지원 웹 (2026 GDGoC 해커톤) ([↗ 저장소](https://github.com/2026-GDGoC-Hackathon-ONE-WAVE))
취업난 속 청년들에게 **면접 회고**를 제공하고 결과에 따른 **감정 위로**를 건네는 웹 서비스. **백엔드 담당.**
- Spring Boot(Java 17) 기반 REST API 설계, JPA·MySQL로 데이터 관리
- Google Gemini(Vertex AI)를 연동해 회고·정서 지원 응답을 생성
- Swagger로 API 문서화, Docker·GitHub Actions로 빌드·배포 자동화
- `Spring Boot` `Java` `JPA` `MySQL` `Vertex AI` `Docker` `GitHub Actions`

---

## 📄 연구

**대규모 실시간 데이터 파이프라인의 End-to-End 지연시간 최적화** — KSCI, 2026.05
파이프라인의 어떤 설정이 전체 지연시간에 영향을 주는지 정량 측정·분석.
[DOI: 10.9708/jksci.2026.31.05.011](https://doi.org/10.9708/jksci.2026.31.05.011)

---

## 🛠 Tech Stack

- **Infra / DevOps** · `OpenStack` `Docker` `Linux` `Kubernetes` `Nginx` `Bash`
- **Cloud** · `KakaoCloud` `AWS` `GCP`
- **Data Engineering** · `Kafka` `Kafka Connect` `Debezium` `Spark` `Hadoop` `Hive` `Logstash`
- **ML / Serving** · `Kubeflow` `KServe` `LangChain` `RAG`
- **Backend** · `Spring Boot` `JPA` `MySQL`
- **Language** · `Python` `Go` `Java`
