<div align="center">

<!-- Header Banner -->
<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=0:0f172a,50:1e3a5f,100:0ea5e9&height=200&section=header&text=이선로%20·%20Sunro%20Lee&fontSize=42&fontColor=ffffff&fontAlignY=38&desc=Backend%20Engineer%20|%20MSA%20·%20Kafka%20·%20Performance&descAlignY=58&descColor=94d3f7" />

</div>

<br/>

<div align="center">

[![Gmail](https://img.shields.io/badge/gwangjulsr@gmail.com-EA4335?style=flat-square&logo=gmail&logoColor=white)](mailto:gwangjulsr@gmail.com)
[![GitHub](https://img.shields.io/badge/GitHub-sunro1994-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/sunro1994)
[![Blog](https://img.shields.io/badge/Blog-Tistory-FF6B35?style=flat-square&logo=tistory&logoColor=white)](https://sunro1994.tistory.com)

</div>

---

## 🧠 Who Am I

```
간호학과 출신 → 백엔드 엔지니어
"왜 이 기술인가"를 끝까지 파고드는 습관
증상 → 원인 → 해결의 데이터 기반 트러블슈팅
```

> 비전공자였기에 오히려 기술의 본질을 끝까지 파고드는 습관이 생겼습니다.  
> **MSA 전환 · Kafka 기반 분산 처리 · 성능 개선**을 핵심 역량으로 삼고 있습니다.

---

## ⚡ Performance Highlights

<div align="center">

| 문제 | 해결 | 개선율 |
|------|------|--------|
| 분산 락 경합 (Redisson → Lua Script) | 최대 응답 지연 **10s → 3s** | 🚀 **66.7%↓** |
| 외부 API 지연 (Redis 이중 캐시 전략) | 응답 속도 **2,318ms → 14ms** | 🚀 **99.4%↓** |
| N+1 쿼리 (벌크 조회 + HashMap 캐시) | **5,000ms → 30ms** | 🚀 **99.4%↓** |
| Kafka Outbox 패턴 도입 | 6,500명 동시 요청 **메시지 무손실** 처리 | ✅ **원자성 보장** |
| DB 결제 테이블 정규화 (2개 → 12개) | 관리자 조회 **1,320ms → 700ms** | 🚀 **47%↓** |
| Token Diet 오픈소스 개발 | 프롬프트 토큰 **25,000개 → 5,000개** | 🚀 **80%↓** |

</div>

---

## 🛠 Tech Stack

### Backend
![Java](https://img.shields.io/badge/Java-FF0000?style=for-the-badge&logo=openjdk&logoColor=white)
![Spring Boot](https://img.shields.io/badge/SpringBoot-6DB33F?style=for-the-badge&logo=springboot&logoColor=white)
![Spring Security](https://img.shields.io/badge/Spring_Security-6DB33F?style=for-the-badge&logo=springsecurity&logoColor=white)
![Spring Batch](https://img.shields.io/badge/Spring_Batch-6DB33F?style=for-the-badge&logo=spring&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white)
![NestJS](https://img.shields.io/badge/NestJS-E0234E?style=for-the-badge&logo=nestjs&logoColor=white)
![Kotlin](https://img.shields.io/badge/Kotlin-7F52FF?style=for-the-badge&logo=kotlin&logoColor=white)

### Messaging & MSA
![Kafka](https://img.shields.io/badge/Apache_Kafka-231F20?style=for-the-badge&logo=apachekafka&logoColor=white)
![Spring Cloud](https://img.shields.io/badge/Spring_Cloud-6DB33F?style=for-the-badge&logo=spring&logoColor=white)
![OpenFeign](https://img.shields.io/badge/OpenFeign-6DB33F?style=for-the-badge&logo=spring&logoColor=white)

### Database & Cache
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-FF4438?style=for-the-badge&logo=redis&logoColor=white)
![Elasticsearch](https://img.shields.io/badge/Elasticsearch-005571?style=for-the-badge&logo=elasticsearch&logoColor=white)

### DevOps & Infra
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![AWS](https://img.shields.io/badge/AWS_ECS/ECR-232F3E?style=for-the-badge&logo=amazonaws&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=for-the-badge&logo=githubactions&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)

### Monitoring
![Prometheus](https://img.shields.io/badge/Prometheus-E6522C?style=for-the-badge&logo=prometheus&logoColor=white)
![Grafana](https://img.shields.io/badge/Grafana-F46800?style=for-the-badge&logo=grafana&logoColor=white)
![ELK Stack](https://img.shields.io/badge/ELK_Stack-005571?style=for-the-badge&logo=elasticstack&logoColor=white)

---

## 🚀 Featured Projects

### 🎫 [Earlybird-Ticket](https://github.com/earlybird-ticket/backend) — 실시간 예매 시스템
> **BE 4명 | 테크리더** · Java · SpringBoot · Kafka · Redis · MSA

- **Outbox 패턴** 도입으로 Kafka 이중 쓰기 문제 해결 → 6,500명 동시 요청 메시지 무손실
- **Lua Script** 기반 분산 락 재설계 → 응답 지연 10s → 3s (66.7% 개선)
- **Prometheus + Grafana** 모니터링 대시보드 구축 및 병목 탐색

<details>
<summary>📌 해결한 기술 문제 보기</summary>

| 문제 | 원인 | 해결 |
|------|------|------|
| Kafka 원자성 깨짐 | 이중 쓰기 문제 | Outbox 패턴 + DLQ |
| Consumer Lag 지연 | 폴링 주기 / 파티션 부족 | 폴링 500ms + 파티션 30개 |
| 직렬화 타입 불일치 | 단일 타입 처리 구조 | Event Dispatcher 전략 패턴 |
| 분산 락 경합 | Redisson 오버헤드 | Lua Script 원자적 명령 |

</details>

---

### 📦 [Owl-Express](https://github.com/over-time-worker/backend) — B2B 물류 배송 시스템
> **BE 4명 | 테크리더** · Java · SpringBoot · Spring Cloud · Redis · ELK

- **다익스트라 알고리즘** 직접 구현 → 허브-스포크 최단 경로 계산
- **Redis 이중 캐시** (Write Through + Cache Aside) → 2,318ms → 14ms (99.4% 개선)
- **N+1 해결** → HashMap 인메모리 캐시로 5,000ms → 30ms (99.4% 개선)

---

### 🔧 [save-your-token](https://github.com/Sunro1994/save-your-token) — Claude Code 토큰 절약 오픈소스
> **1인 개발** · Python · Bash · JSONL

- Claude Code 세션 JSONL 파싱 → 명령어별 토큰 사용량 집계 및 분류
- 4가지 훅 자동화: **ReadOnce**(중복 읽기 차단) · **prompt-lint**(고비용 패턴 감지) · **context-watch**(임계값 경고) · **report-save**(일별 스냅샷)
- 토큰 소모 **25,000개 → 5,000개 (80% 절감)**

---

## 💼 Work Experience

```
Loword          2025.11 ~ 2026.03  │  Node.js · NestJS · PostgreSQL · ECS/ECR
                결제 시스템 설계 · 8만건 데이터 마이그레이션 · 테이블 정규화 (2→12개)

The PAP (바로인턴 13기)  2025.06 ~ 2025.07  │  Kotlin · Spring Boot · ElasticSearch
                네이버 자회사 · MSA 장애 전파 방지 · 서킷브레이커 도입
```

---

## 📜 Certifications

![SQLD](https://img.shields.io/badge/SQLD-2024.10-003366?style=flat-square&logo=oracle&logoColor=white)
![정보처리기사](https://img.shields.io/badge/정보처리기사-2023.09-0078D4?style=flat-square&logo=windows&logoColor=white)
![리눅스마스터2급](https://img.shields.io/badge/리눅스마스터_2급-2023.03-FCC624?style=flat-square&logo=linux&logoColor=black)

---

## 📊 GitHub Stats

<div align="center">

<img height="165" src="https://github-readme-stats.vercel.app/api?username=sunro1994&show_icons=true&theme=tokyonight&hide_border=true&count_private=true" />
<img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=sunro1994&layout=compact&theme=tokyonight&hide_border=true" />

</div>

<div align="center">

[![GitHub Streak](https://streak-stats.demolab.com?user=sunro1994&theme=tokyonight&hide_border=true)](https://github.com/sunro1994)

</div>

---

## 📝 Tech Blog & Presentations

| 주제 | 링크 |
|------|------|
| 데이터 실시간 동기화 & Feature Flag | [🔗 보기](https://canva.link/jfgdp2r5rluaet8) |
| 올리브영 신규 재고 시스템 개발 | [🔗 보기](https://www.canva.com/design/DAGh3GObOZc/view) |
| Kafka의 한계와 Flink 활용 | [🔗 보기](https://www.canva.com/design/DAGiUd5-rgo/view) |
| Kafka 파티션 할당 전략 & MSK | [🔗 보기](https://www.canva.com/design/DAGi8svwbuE/view) |
| Toss 증권 Kafka 데이터센터 이중화 | [🔗 보기](https://www.canva.com/design/DAGkJNcmzgk/view) |

---

<div align="center">

<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=0:0ea5e9,50:1e3a5f,100:0f172a&height=120&section=footer" />

</div>
