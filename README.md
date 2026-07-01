# MES One — Future Art Digital Factory

**Собственная MES/MOM система** для мебельной фабрики Ильдара (КАЗПРОМ АВТОМАТИКА).

## Цель проекта
Создать единую платформу с полным **traceability** (прослеживаемостью) от заказа в CRM/1C → инженерия (imos iX) → производство (HOMAG + SCM/Morbidelli) → логистика/монтаж → BI/KPI/OEE.

## Ключевые элементы
- **Unified ID Model**: MasterOrderID, PartID, OperationFactID, EngineeringVersionID
- **Интеграции**: imos iX Integration Server, 1C, Homag OPC UA, Maestro Connect, woodWOP, UNS/MQTT
- **Архитектура**: v4.91+
- **Критические риски**: R01 (imos), R06 (1C-sync), R09 (governance)

## Структура репозитория
- `docs/` — Технические задания, спецификации
- `architecture/` — Диаграммы (Mermaid)
- `integrations/` — Скрипты и логика интеграций
- `Issues + Projects` — Управление внедрением

**Статус**: Активная разработка и внедрение на собственной фабрике.
