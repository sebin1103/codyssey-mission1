# 컴퓨터 사고 원인 분석 보고서


## 1. 사고 발생 타임라인 
로그 분석 결과 미션 완료 직후 아래와 같은 문제가 발생하였습니다

| 시간 | 상태 | 주요 내용 |
| :--- | :---: | :--- |
| **11:28:00** | **INFO** | Touchdown confirmed. Rocket safely landed.                   |
| **11:30:00** | **INFO** | Mission completed successfully. Recovery team dispatched.    |
| **11:35:00** | **INFO** | **Oxygen tank unstable.** (산소 탱크 불안정 감지)                 |
| **11:40:00** | **INFO** | **Oxygen tank explosion.** (산소 탱크 폭발 발생)                 |
| **12:00:00** | **INFO** | Center and mission control systems powered down.             |

## 2. 사고 원인 분석
* **직접적 원인**: 산소 탱크의 결함에 의한 폭발입니다.
* **사고 전개**: 로켓이 안전하게 착륙하여 미션이 성공적으로 종료된 지 5분 만에 산소 탱크에서 불안정 수치가 감지되었습니다. 이후 5분이 지난 후 탱크가 완전히 폭발하였습니다. 

## 3. 결론
* **결론**:  **산소 탱크의 결함**으로 인해 발생한 사고입니다
