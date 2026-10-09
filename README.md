# schema-rules

Плагин Claude Code: правила отрисовки схем Битрикс24 в draw.io — карты воронок, схемы на доработку, связи воронок, бизнес-процессы, согласования.

## Установка

В Claude Code:

```
/plugin marketplace add MargaretRaven/schema-rules
/plugin install schema-rules@schema-rules
```

Репозиторий приватный — нужен доступ к GitHub (`gh auth login` или git с вашими учётными данными).

## Использование

- Команда: `/schema-rules:schema-rules доработка карты продаж`
- Или просто: «нарисуй схему на доработку», «проверь схему БП» — скилл подхватится по описанию.

## Обновление

После правок здесь: увеличить `version` в `.claude-plugin/plugin.json`, закоммитить, запушить. На компьютере:

```
/plugin marketplace update schema-rules
```

## Структура

```
skills/schema-rules/
  SKILL.md        выбор типа схемы, чек-лист, red flags
  funnel-map.md   карта воронки, доработка, связи воронок, роботы стадий
  bp.md           БП линейный и со статусами
  approval.md     БП согласования документов
  arrows.md       стрелки
  styles.md       готовые стили draw.io
```

Правило: этот репозиторий — единственный источник правил схем. Новое правило или эталон — сюда, не в проекты.
