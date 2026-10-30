# 제조 현장의 데이터를 소프트웨어로 연결하는 개발자

**Manufacturing DX Software Engineer**  
`Backend` · `Manufacturing IT / MES` · `IIoT` · `Digital Twin` · `AI`

안녕하세요. 제조 현장에서 발생하는 **설비·생산·자재 데이터를 수집하고, 업무 시스템과 연결해 활용 가능한 정보로 만드는 개발자**를 지향합니다.

정보통신공학을 전공하고 스마트팩토리 교육 및 팀 프로젝트를 통해 **제조 업무 흐름, Backend/DB 개발, 데이터 연계, 디지털트윈 시뮬레이션**을 경험했습니다. 단순히 기능을 구현하는 데 그치지 않고, **데이터가 생성되는 현장부터 사용자가 확인하는 서비스까지 전체 흐름을 이해하고 설계하는 것**에 관심이 있습니다.

---

## 핵심 역량

| 영역 | 경험 및 기술 |
| --- | --- |
| **Manufacturing IT** | BOM·재고·자재 관리, 설비 상태·알람, 공정 흐름 모델링 |
| **Backend & Database** | Java, Spring Boot, REST API, MyBatis, MySQL, SQL |
| **Data Integration** | MQTT, Node-RED, 데이터 시뮬레이션, 설비 이벤트 연계 |
| **Frontend** | Vue.js, 제조 관리·모니터링 웹 UI |
| **Digital Twin & AI** | Unreal Engine 5 Blueprint, Python, RAG 기반 알람 분석 시스템 |

## 대표 프로젝트

### 01. FactoryEye — 제조 설비 관제 및 AI 기반 알람 분석

> **설비 상태와 알람 이력을 모니터링하고, 알람 대응에 필요한 정보를 분석·전달하는 교육용 제조 관제 PoC**

- **프로젝트 기술:** Spring Boot, MySQL, MQTT, Node-RED, RAG
- **문제 정의:** 설비 이벤트와 알람 정보가 분산되면 이상 상황을 확인하고 대응 맥락을 파악하기 어렵습니다.
- **시스템 접근:** 가상 설비 데이터 생성, 관제 시스템의 알람 조회·관리, 과거 정보 기반 분석 및 메일 알림 기능을 연계했습니다.
- **직접 담당:**
  - Node-RED 기반 설비 데이터 시뮬레이션
  - 알람 조회·관리 API 구현
  - RAG 기반 알람 분석 결과를 전달하는 메일링 기능 개발
- **보여주는 역량:** 제조 설비 데이터의 흐름 이해, Backend API 구현, AI 기능과 업무 시스템의 연계

**Repository:** [FactoryEye / BS-SCADA](https://github.com/sleeping-6eauty/BS-SCADA)

### 02. Auto BOM Inventory — 제조 자재·재고 관리 시스템

> **주문·BOM·자재·재고 정보를 연결하여 제조 현장의 자재 관리 업무를 지원하는 웹 프로젝트**

- **프로젝트 기술:** Java, Spring Boot, MyBatis, MySQL, Vue.js
- **문제 정의:** 자재, 가격, 재고 정보가 분리되어 있으면 자재 현황 확인과 생산 준비가 복잡해집니다.
- **시스템 접근:** 제조 업무에 필요한 데이터를 관계형 DB로 관리하고 Backend API와 웹 화면을 연결했습니다.
- **직접 담당:**
  - 자재 관리 화면 구현
  - 가격·재고 관련 테이블 설계 및 개발
- **보여주는 역량:** 제조 업무 요구사항 해석, 관계형 데이터 모델링, Backend–Frontend 연계

**Repository:** [auto-bom-inventory](https://github.com/sleeping-6eauty/auto-bom-inventory)

### 03. Automotive Digital Twin — 자동차 차체공정 디지털트윈

> **자동차 차체공정의 Station·AGV·Conveyor·Robot 상태를 모델링하고, 생산 이벤트와 3D 시뮬레이션을 연결한 교육용 PoC**

- **프로젝트 기술:** Unreal Engine 5 (Blueprint), Node-RED, MySQL, MQTT
- **문제 정의:** 설비별 상태와 공정 진행 흐름을 한눈에 파악하기 어렵고, 생산 시나리오를 일관되게 재현할 환경이 필요합니다.
- **시스템 접근:** Node-RED에서 생산 이벤트를 시뮬레이션하고 MySQL에 상태·이력을 관리하며, 팀에서 구축한 MQTT 연계를 통해 UE5의 설비 모델과 상태를 동기화했습니다.
- **역할:** **팀장** — 전체 시스템 설계 방향·기능 통합을 총괄
- **직접 담당:**
  - Node-RED 기반 생산 공정 이벤트 및 설비 상태 시뮬레이션 구현
  - MySQL 데이터베이스 스키마 설계
  - Unreal Engine 5에서 **로봇팔 동작 Blueprint** 구현
- **협업 범위:** UE5–MQTT 메시지 연동 기능은 다른 팀원이 담당했으며, 해당 기능과 시뮬레이션·DB의 통합을 팀 차원에서 진행했습니다.
- **보여주는 역량:** 제조 공정 상태 모델링, 시뮬레이션 설계, DB 구조화, 팀 리딩과 시스템 통합

**Repository:** [Digital-Twin-Project](https://github.com/sleeping-6eauty/Digital-Twin-Project)

---

## 개발할 때 중요하게 생각하는 것

1. **업무 이해부터 시작하기:** 사용자가 어떤 생산·자재·설비 정보를 필요로 하는지 먼저 정리합니다.
2. **데이터 흐름을 명확하게 설계하기:** 수집 → 저장 → 처리 → 화면/알림까지 데이터의 경로와 책임을 구분합니다.
3. **구현 범위와 근거를 투명하게 남기기:** 팀의 결과와 직접 담당한 부분을 구분하고, 실제 검증한 내용만 성과로 제시합니다.

## Education & Certifications

- **전공:** 정보통신공학
- **교육:** 현대오토에버 모빌리티 SW스쿨 — 스마트팩토리 트랙
- **자격증:** 정보처리기사 · SQLD

---

**관심 직무:** 제조 IT / MES 개발·운영 · 스마트팩토리 SW · 생산·물류 IT · 제조 DX/AX · Digital Twin

<!-- 각 프로젝트 상세 README에 실제 시연 영상, 발표자료, 아키텍처, 본인 담당 코드 및 기술 문제 해결 기록을 연결하면 더욱 설득력 있는 포트폴리오가 됩니다. -->
