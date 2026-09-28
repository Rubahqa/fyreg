---
name: qa-responsive
description: Проверяет сайт на разных экранах и сценариях: навигация, формы, адаптив, состояния, ошибки и регрессии.
---

# QA & Responsive Testing

Используй этот навык после реализации изменений.

## Viewports

Проверь минимум:
- 360×800
- 390×844
- 768×1024
- 1024×768
- 1366×768
- 1440×900

## Проверки

### Layout
- горизонтальный scroll;
- переполнение текста;
- обрезанные элементы;
- сломанные grid/flex layouts;
- некорректные sticky/fixed элементы.

### Navigation
- desktop menu;
- mobile menu;
- anchors;
- breadcrumbs;
- back/forward browser behavior.

### Forms
- required;
- validation;
- error states;
- success states;
- disabled/loading;
- вставка длинного текста;
- email/phone formats.

### Interaction
- hover;
- focus;
- keyboard;
- touch targets;
- modals;
- dropdown;
- accordion;
- tabs.

### Content
- длинные заголовки;
- отсутствие изображения;
- длинные URL;
- пустые состояния;
- ошибки загрузки.

## Формат bug report

Для каждой ошибки:
- Severity;
- Страница;
- Шаги воспроизведения;
- Ожидаемый результат;
- Фактический результат;
- Предлагаемое исправление.

## Финальный статус

Не пиши просто «все работает».
Сформируй checklist с PASS / FAIL / NOT TESTED.
