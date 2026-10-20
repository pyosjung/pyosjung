# 안녕하세요, 시스템을 연결하고 데이터 흐름을 설계하는 개발자 표성중입니다.

정보통신공학을 전공하며 **디바이스에서 발생한 데이터를 수집하고, 서버와 데이터베이스를 거쳐 사용자에게 의미 있는 정보로 전달하는 시스템**에 관심을 가지고 개발 경험을 쌓아왔습니다.

웹 개발, IoT, AI Vision, Smart Factory, Digital Twin 프로젝트를 수행하며  
단순 기능 구현을 넘어 **여러 시스템을 연결하고 전체 데이터 흐름을 설계하는 역량**을 키워왔습니다.

현재는 **Smart Factory / Digital Twin / 제조 DX·AX 분야의 개발자**를 목표로 하고 있습니다.

---

## Featured Projects

### Automotive Body Shop Digital Twin

**Unreal Engine 5 기반 자동차 차체공정 디지털트윈 시스템**

자동차 차체 생산라인을 가상 환경에 구현하고, 컨베이어·AGV·조립로봇·용접로봇·비전검사 설비의 상태와 생산 이벤트를 연계한 프로젝트입니다.

단순 3D 시뮬레이션이 아니라  
**설비 제어 → 이벤트 수집 → DB 저장 → 생산성/OEE 분석**까지 연결하는 구조를 구현했습니다.

#### 주요 구현

- Unreal Engine 5 기반 자동차 차체공정 시뮬레이션
- MQTT 기반 Command / Event 통신 구조 설계
- Node-RED 기반 생산 공정 Orchestrator 구현
- AGV 기반 부품 공급 및 설비 상태 관리
- Assembly / Welding Robot 공정 구현
- 이벤트 기반 Conveyor 제어
- MySQL 기반 생산 및 설비 데이터 관리
- Station Cycle Time / OEE 계산
- Vision Inspection 결과 연동
- FastAPI / WebSocket 기반 Backend 연계

#### Architecture

```text
Production Command
        ↓
Node-RED
        ↓
MQTT
        ↓
Unreal Engine 5
        ↓
Equipment Operation
        ↓
MQTT Event
        ↓
Node-RED
        ↓
MySQL / FastAPI / OEE
```

#### Tech Stack

`Unreal Engine 5` `Blueprint` `C++` `MQTT` `Node-RED` `MySQL` `Python` `FastAPI` `WebSocket`

---

### Interactive Alarm Vision System

**Computer Vision 기반 미션형 알람 서비스**

사용자가 웹캠을 통해 특정 동작을 수행해야 알람을 종료할 수 있도록 구현한 AI Vision 프로젝트입니다.

#### 주요 구현

- MediaPipe Hands 기반 Landmark 추출
- EfficientNetB2 기반 가위바위보 이미지 분류
- Pose Landmark 기반 자세 분류
- Face Landmark 기반 얼굴 방향 판단
- Majority Voting 기반 예측 안정화
- FastAPI 기반 Vision API
- Next.js 기반 Web UI 및 Webcam 연동

#### Architecture

```text
Webcam
  ↓
Next.js
  ↓
FastAPI
  ↓
MediaPipe / AI Model
  ↓
Mission Validation
  ↓
Alarm Stop
```

#### Tech Stack

`Next.js` `TypeScript` `Python` `FastAPI` `TensorFlow` `Keras` `MediaPipe` `EfficientNetB2`

Repository  
https://github.com/pyosjung/hdae-cv-project1

---

### Parking Hit-and-Run Detection System

**Raspberry Pi 기반 주차 차량 충돌 감지 및 알림 시스템**

주차 중 차량에 충격이 발생했을 때 사용자가 사고 정보를 빠르게 확인할 수 있도록 구현한 IoT 프로젝트입니다.

#### 주요 구현

- Raspberry Pi 기반 충격 감지 시스템
- SW-18010P 충격 센서 연동
- HC-SR04 초음파 센서 활용
- Socket 통신 기반 데이터 전달
- 충돌 발생 시 Email Notification
- 웹을 통한 사고 영상 확인

#### Tech Stack

`Raspberry Pi` `Python` `Socket` `Sensor` `Web`

---

## Tech Stack

### Languages

`Python` `Java` `C++` `JavaScript` `TypeScript` `SQL`

### Backend

`FastAPI` `REST API` `WebSocket`

### Frontend

`Next.js` `React`

### Data & Messaging

`MySQL` `MQTT` `Node-RED`

### AI / Computer Vision

`TensorFlow` `Keras` `MediaPipe` `EfficientNet`

### Digital Twin / Manufacturing

`Unreal Engine 5` `Blueprint` `Smart Factory` `Digital Twin`

---

## What I Focus On

제가 프로젝트에서 중요하게 생각하는 것은 개별 기능보다 **전체 시스템의 연결 구조**입니다.

```text
Device
  ↓
Network / Protocol
  ↓
Backend
  ↓
Database
  ↓
Application
```

각 계층이 어떻게 데이터를 주고받고,  
어떻게 안정적으로 상태를 관리하며,  
어떻게 사용자에게 의미 있는 결과를 제공하는지를 고민합니다.

---

## Interests

- Smart Factory
- Digital Twin
- Manufacturing IT / OT
- IoT Data Pipeline
- Backend Platform
- Event-driven Architecture
- AI + Manufacturing
- DX / AX

---

## Contact

GitHub  
https://github.com/pyosjung
