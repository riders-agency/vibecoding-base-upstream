# Перенос сайтов и админок

Модуль `delivery/site-migration` описывает перенос контента, данных, сценариев и инфраструктуры. Начните с [пошаговой инструкции](rules/playbook.md), [разбора решений](../../../../docs/migration-lessons.md) и [шаблона](../../../../templates/site-migration.md).

Число правил: 11.

| ID | Правило | Уровень |
| --- | --- | --- |
| `migration.playbook` | [Пошаговый перенос сайта и админки](rules/playbook.md) | Обязательно |
| `migration.source-inventory` | [Инвентаризация исходного сайта](rules/source-inventory.md) | Обязательно |
| `migration.field-mapping` | [Карта полей и преобразований](rules/field-mapping.md) | Обязательно |
| `migration.repeatable-import` | [Повторяемый импорт и перенос изменений](rules/repeatable-import.md) | Обязательно |
| `migration.data-reconciliation` | [Сверка исходника и результата импорта](rules/data-reconciliation.md) | Обязательно |
| `migration.url-continuity` | [Сохранение адресов при переносе сайта](rules/url-continuity.md) | Обязательно |
| `migration.feature-parity` | [Функции сайта и замечания сохраняются при переносе](rules/feature-parity.md) | Обязательно |
| `migration.preview-isolation` | [Изолированный стенд для переноса](rules/preview-isolation.md) | Обязательно |
| `migration.cutover-recovery` | [Переключение сайта и восстановление записей](rules/cutover-recovery.md) | Обязательно |
| `migration.handoff` | [Передача перенесённого сайта владельцу](rules/handoff.md) | Обязательно |
| `migration.legacy-independence` | [Независимость перенесённого сайта от старого движка](rules/legacy-independence.md) | Обязательно |

[История изменений](CHANGELOG.md).
