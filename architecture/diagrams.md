# Архитектура MES One — Future Art v4.91+

## Основной поток данных

```mermaid
flowchart TD
    A[CRM / 1C: Заказ] --> B[MasterOrderID]
    B --> C[imos iX - Инженерия]
    C --> D[PartID + EngineeringVersionID]
    D --> E[HOMAG + SCM/Morbidelli - Производство]
    E --> F[OperationFactID + MDE/MDC]
    F --> G[WMS / Логистика / Паллеты]
    G --> H[Монтаж + BI / OEE / Traceability]
    
    style A fill:#e1f5fe
    style H fill:#e8f5e9
