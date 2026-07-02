# MES One — Future Art Digital Factory

**Собственная MES/MOM-система** для мебельной фабрики Ильдара (КАЗПРОМ АВТОМАТИКА).

## 🎯 Цель проекта
Создать единую платформу с **полной прослеживаемостью (traceability)** от заказа в CRM/1C → инженерия (imos iX) → производство (HOMAG + SCM/Morbidelli) → логистика/монтаж → BI/KPI/OEE.

## 📋 Основная документация v4.91

| Файл | Описание |
|------|----------|
| **[02_Expanded_Technical_Specification_v4_91_FULL_43_points_CORRECTED.pdf](./02_Expanded_Technical_Specification_v4_91_FULL_43_points_CORRECTED.pdf)** | **Основное Техническое Задание** (рабочая версия) |
| **[00_Full_Documentation_Set](./00_Full_Documentation_Set...)** | Полный комплект документов |
| **[03_Integration_Matrix_v4_91](./03_Integration_Matrix...)** | Матрица интеграций |
| **[04_Data_Exchange_Logic](./04_Data_Exchange_Logic...)** | Логика обмена данными |
| **[05_Glossary_ID_Dictionary](./05_Glossary_ID_Dictionary...)** | Словарь ID-моделей |
| **[06_Master_Data_Governance](./06_Master_Data_Governance...)** | Управление мастер-данными |
| **[01_Architecture_Diagram](./01_Architecture_Diagram...)** | Архитектурные диаграммы |

## 🏗️ Архитектура
- [Диаграммы и основной поток](./architecture/diagrams.md)
- Unified ID Model: `MasterOrderID`, `PartID`, `OperationFactID`, `EngineeringVersionID`

## ⚠️ Критические риски
- [Реестр рисков](./docs/risks-register.md) (R01, R06, R09 и др.)

## 🔧 Ключевые интеграции
- imos iX (Integration Server + CAD/CAM)
- 1C: Комплексная автоматизация
- HOMAG (OPC UA, STORETEQ, CENTATEQ, EDGETEQ и др.)
- SCM/Morbidelli (Maestro Connect)
- woodWOP, Cut Rite, woodStore

## 📍 Текущий статус
- Активное внедрение на собственной мебельной фабрике
- Ведётся пилотный этап (traceability skeleton)
- Архитектура v4.91+

---

**Репозиторий** предназначен для хранения всей документации, архитектуры, рисков и кода по проекту MES One.

---

*Последнее обновление: Июль 2026*