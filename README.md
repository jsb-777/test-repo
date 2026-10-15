### 📈 DORA 지표 시각화 대시보드 시안 (Mermaid)

```mermaid
gantt
    title DORA Metrics - Delivery Performance
    dateFormat  HH:mm
    axisFormat %H:%m
    section Lead Time for Changes
    Commit & Build       :a1, 00:00, 30m
    Automated Testing    :a2, after a1, 15m
    Production Deploy    :a3, after a2, 15m
```

```mermaid
pie title DORA Metrics - Deployment Stability
    "Success Deployments (95%)" : 95
    "Change Failures (5%)" : 5
```
