# 김현주 (Hyeonju Kim) · Backend · Data Pipeline · MLOps Engineer

대량의 데이터를 **유실 없이** 흘려보내는 파이프라인과, 그 위에서 모델을 학습·배포하는 **인프라**를 만들어 온 3년 차 엔지니어입니다.
문제가 생기면 증설부터 하지 않고, **먼저 측정해서 병목을 찾고**, 해결한 과정은 블로그에 남깁니다.

[![Blog](https://img.shields.io/badge/Tech_Blog-thenicole.tistory.com-000000?style=flat&logo=tistory&logoColor=white)](https://thenicole.tistory.com)
[![Old Blog](https://img.shields.io/badge/Archive-yeees.tistory.com-555555?style=flat&logo=tistory&logoColor=white)](https://yeees.tistory.com)
[![Email](https://img.shields.io/badge/yocu1784@gmail.com-EA4335?style=flat&logo=gmail&logoColor=white)](mailto:yocu1784@gmail.com)

---

## 🚀 What I've built

| 프로젝트 | 역할 | 핵심 성과 |
|---|---|---|
| **DB 운영 점검 AI 자동화** (2026 ~ 현재) | 단독 설계·개발·운영 | 160여 대 DB 이상 탐지(룰 + PCA) 리포트·대시보드 자동화 · 점검 시간 **44%↓** · 알림 오탐률 **38.4% → 5.4%** |
| **사내 첫 MLOps 플랫폼** (2026) | 프로젝트 리더 (팀 4인) | GPU 서버 + Kubernetes 위 학습·배포·서빙 플랫폼 0 → 1 · Transactional Outbox로 이벤트 **558건 유실 0건** |
| **자율주행 관제 실시간 파이프라인** (2024 ~ 2025) | 서브 PM · 국가 R&D (7개 기관) | Kafka로 일 최대 **5억 건** 처리 · 병목 측정으로 **7,000 → 21,000 TPS** · 공인 시험 E2E **7,482 TPS** |

## 🔧 Problems I've solved

- **Kafka 처리량 3배**: 파티션을 늘려도 그대로 → 구간별 측정으로 정제 단계 병목 특정 → 건당 처리 비용 경량화 ([글](https://thenicole.tistory.com/42))
- **GPU 서버 2분 멈춤**: 커널 로그·cgroup 추적으로 유령 cgroup 수천 개가 원인임을 규명 ([글](https://thenicole.tistory.com/46))
- **서비스 간 이벤트 정합성**: DB 커밋과 Kafka 발행을 Transactional Outbox + 멱등 소비로 묶음 ([글](https://thenicole.tistory.com/40))
- **Redis Lost Update**: 분산 락·WATCH·Lua 비교 후 Lua 원자적 UPSERT로 상태 롤백 0건 ([글](https://thenicole.tistory.com/63))

## 💪 Tech Stack

**Backend** &nbsp;
![Java](https://img.shields.io/badge/Java-007396?style=flat&logo=openjdk&logoColor=white)
![Spring Boot](https://img.shields.io/badge/Spring_Boot-6DB33F?style=flat&logo=springboot&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat&logo=fastapi&logoColor=white)
![MyBatis](https://img.shields.io/badge/MyBatis-000000?style=flat)

**Data · Messaging** &nbsp;
![Kafka](https://img.shields.io/badge/Kafka_(Streams·Connect)-231F20?style=flat&logo=apachekafka&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat&logo=redis&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat&logo=postgresql&logoColor=white)
![TimescaleDB](https://img.shields.io/badge/TimescaleDB-FDB515?style=flat&logo=timescale&logoColor=black)
![MQTT](https://img.shields.io/badge/MQTT_(EMQX)-660066?style=flat&logo=mqtt&logoColor=white)

**Infra · MLOps** &nbsp;
![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=flat&logo=kubernetes&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat&logo=docker&logoColor=white)
![NVIDIA](https://img.shields.io/badge/NVIDIA_GPU·CUDA-76B900?style=flat&logo=nvidia&logoColor=white)
![Jenkins](https://img.shields.io/badge/Jenkins-D24939?style=flat&logo=jenkins&logoColor=white)
![Argo CD](https://img.shields.io/badge/Argo_CD-EF7B4D?style=flat&logo=argo&logoColor=white)
![MLflow](https://img.shields.io/badge/MLflow-0194E2?style=flat&logo=mlflow&logoColor=white)
![Airflow](https://img.shields.io/badge/Airflow-017CEE?style=flat&logo=apacheairflow&logoColor=white)
![Prometheus](https://img.shields.io/badge/Prometheus-E6522C?style=flat&logo=prometheus&logoColor=white)
![Grafana](https://img.shields.io/badge/Grafana-F46800?style=flat&logo=grafana&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat&logo=linux&logoColor=black)

## 📜 Certifications

AWS Certified Solutions Architect – Associate · 리눅스마스터 1급 · 정보처리기사 · SQLD · AICE Associate

## 🌱 About

간호사·보건소 공무원으로 일하다 1년간 공부해 개발자로 전직했습니다.
현장에서 몸에 밴 **"원인을 끝까지 확인하고 기록하는 습관"** 을 개발에서도 그대로 이어가고 있습니다.

> 실무 코드는 회사 보안 정책상 공개하지 않으며, 설계와 트러블슈팅 과정은 [기술 블로그](https://thenicole.tistory.com)에 정리하고 있습니다.
