# myhome 프로젝트 개요

ESP32 보드를 통해 에어컨을 원격 제어하고, 센서 데이터를 수집해 AI가 사용 패턴을 분석한 리포트를 제공하며, 이를 대시보드로 시각화하는 웹 서비스입니다.

## 문서 구성

| 문서 | 내용 |
| :--- | :--- |
| [01-device-esp32.md](./01-device-esp32.md) | ESP32 디바이스 연동, 에어컨 제어 |
| [02-auth-user.md](./02-auth-user.md) | 사용자/인증, 디바이스 소유 관리 |
| [03-dashboard.md](./03-dashboard.md) | 대시보드 화면 요구사항 |
| [04-ai-report.md](./04-ai-report.md) | AI 리포트 생성 |
| [05-notification.md](./05-notification.md) | 알림 |
| [06-automation-schedule.md](./06-automation-schedule.md) | 자동화/스케줄 |

## 결정 필요 사항 (전체 공통)

- ESP32 ↔ 서버 통신 프로토콜 (MQTT vs HTTP)
- AI 리포트에 사용할 데이터 범위 및 모델/방식
- 단일 사용자용인지 멀티 테넌트(여러 가구)를 지원할지

각 결정 사항의 세부 논의는 해당 기능 문서 하단의 "결정 필요 사항" 절에도 별도로 정리합니다.
