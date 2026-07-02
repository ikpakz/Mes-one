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
## 📁 Документация (v4.91)

- [00_Full_Documentation_Set](./00_Full_Documentation_Set...) — Полный комплект
- [01_Architecture_Diagram_v4](./01_Architecture_Diagram_v4...) — Архитектура
- [02_Expanded_Technical_Spec](./02_Expanded_Technical_Spe...) — Расширенное ТЗ
- [03_Integration_Matrix](./03_Integration_Matrix...) — Матрица интеграций
- [04_Data_Exchange_Logic](./04_Data_Exchange_Logic...) — Логика обмена данными
- [05_Glossary_ID_Dictionary](./05_Glossary_ID_Dictionary...) — Словарь ID-моделей
- [06_Master_Data_Governance](./06_Master_Data_Governanc...) — Управление мастер-данными

См. также:
- [docs/risks-register.md](./docs/risks-register.md)
- [architecture/diagrams.md](./architecture/diagrams.md)