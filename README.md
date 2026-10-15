## 📊 DORA 4대 지표 수집 결과 보고서

GitHub Actions를 통해 자동으로 수집된 DORA 4대 지표 측정 결과입니다.

| 지표 항목 (Metric) | 측정 결과 (Value) | 설명 (Description) |
| :--- | :--- | :--- |
| **배포 빈도** (Deployment Frequency) | Daily | 프로덕션 환경 배포 주기 |
| **변경 리드 타임** (Lead Time for Changes) | 1 hour | 커밋부터 프로덕션 배포까지 소요된 시간 |
| **평균 복구 시간** (MTTR) | 15 minutes | 장애 발생 후 서비스 복구까지 걸린 시간 |
| **변경 실패율** (Change Failure Rate) | 5% | 배포로 인해 장애가 발생한 비율 |

### 📈 대시보드 시안
- 수집된 `dora-metrics.json` 아티팩트 데이터를 기반으로 구성한 대시보드 시안입니다.
- 향후 Grafana 또는 Chart.js와 연동하여 실시간 트렌드 시각화를 지원합니다.
