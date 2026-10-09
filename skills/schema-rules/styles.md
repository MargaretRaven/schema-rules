# Готовые стили draw.io

Копируй строку стиля целиком в атрибут `style` у `mxCell`. Цвета не подбирать на глаз.

## Карта воронки (1.1, 1.1a, 1.1b, 1.3)

| Элемент | style |
|---------|-------|
| Шапка воронки (родитель) | `swimlane;childLayout=stackLayout;resizeParent=1;resizeParentMax=0;horizontal=1;startSize=20;fontSize=15;fontStyle=1;fillColor=#ffe6cc;strokeColor=#d79b00;strokeWidth=3;html=1;` |
| Колонка стадии | `swimlane;startSize=30;fontSize=11;html=1;whiteSpace=wrap;` |
| Стадия «успех» | колонка + `fillColor=#d5e8d4;strokeColor=#82b366;` |
| Стадия «провал» | колонка + `fillColor=#f8cecc;strokeColor=#b85450;` |
| Новая стадия (доработка) | колонка + `fillColor=#f8cecc;strokeColor=#b85450;strokeWidth=3;` |
| Задание / задача человеку | `rounded=0;whiteSpace=wrap;html=1;fontSize=10;align=left;verticalAlign=top;fillColor=#d5e8d4;strokeColor=#82b366;` |
| Действие системы | `rounded=0;whiteSpace=wrap;html=1;fontSize=11;fillColor=#ffffff;strokeColor=#666666;align=left;verticalAlign=top;` |
| Смена стадии | `rounded=0;whiteSpace=wrap;html=1;fontSize=11;fillColor=#fff2cc;strokeColor=#d6b656;align=left;verticalAlign=top;` |
| Запуск БП / вебхук / приложение | `rounded=0;whiteSpace=wrap;html=1;fontSize=11;fillColor=#e1d5e7;strokeColor=#9673a6;align=left;verticalAlign=top;` |
| Событие / уведомление | `rounded=0;whiteSpace=wrap;html=1;fontSize=10;fillColor=#e1d5e7;strokeColor=#9673a6;align=left;verticalAlign=top;` |
| Условие | `rhombus;whiteSpace=wrap;html=1;fontSize=10;` |
| Заметка | `ellipse;shape=cloud;whiteSpace=wrap;html=1;fillColor=#f5f5f5;strokeColor=#666666;fontSize=10;` |
| Конец логики стадии | `ellipse;whiteSpace=wrap;html=1;shapeInside=1;fillColor=#ffffff;strokeColor=#666666;fontSize=12;` |
| Отключено | `rounded=0;whiteSpace=wrap;html=1;fontSize=11;fillColor=#e0e0e0;strokeColor=#999999;fontColor=#666666;align=left;verticalAlign=top;` |
| Отключённое условие | `rhombus;whiteSpace=wrap;html=1;fontSize=10;fillColor=#e0e0e0;strokeColor=#999999;fontColor=#666666;` |
| **Доработка:** добавить / изменить | `rounded=0;whiteSpace=wrap;html=1;fontSize=11;fillColor=#f8cecc;strokeColor=#b85450;align=left;verticalAlign=top;` |
| **Доработка:** условие | `rhombus;whiteSpace=wrap;html=1;fontSize=10;fillColor=#f8cecc;strokeColor=#b85450;` |
| **Доработка:** вопрос ⚠ | `ellipse;shape=cloud;whiteSpace=wrap;html=1;fillColor=#f8cecc;strokeColor=#b85450;fontSize=10;` |
| **Доработка:** удалить | `rounded=0;whiteSpace=wrap;html=1;fontSize=11;fillColor=#ffffff;strokeColor=#b85450;dashed=1;strokeWidth=2;fontStyle=8;fontColor=#b85450;align=left;verticalAlign=top;` |

## Схема БП (1.2a, 1.2b)

| Элемент | style |
|---------|-------|
| Старт (овал) | `ellipse;whiteSpace=wrap;html=1;fillColor=#d5e8d4;strokeColor=#82b366;fontStyle=1` |
| Конец / ошибка (овал) | `ellipse;whiteSpace=wrap;html=1;fillColor=#f8cecc;strokeColor=#b85450;fontStyle=1` |
| Действие | `rounded=1;whiteSpace=wrap;html=1;fillColor=#ffffff;strokeColor=#666666;` |
| Задание человеку | `rounded=1;whiteSpace=wrap;html=1;fillColor=#d5e8d4;strokeColor=#82b366;` |
| Цикл / запуск БП | `rounded=1;whiteSpace=wrap;html=1;fillColor=#e1d5e7;strokeColor=#9673a6;` |
| Смена статуса | `rounded=0;whiteSpace=wrap;html=1;fontSize=11;fillColor=#fff2cc;strokeColor=#d6b656;align=left;verticalAlign=top;` |
| Условие | `rhombus;whiteSpace=wrap;html=1;fillColor=#ffffff;strokeColor=#666666;` |
| Статус (1.2b) | `swimlane;horizontal=1;startSize=40;whiteSpace=wrap;html=1;fillColor=#fafafa;strokeColor=#666666;rounded=1;fontStyle=1;container=1;collapsible=0;` |
| Статус «Старт» / «Финиш» | как статус, но `fillColor=#d5e8d4;strokeColor=#82b366;` |
| Контейнер-обёртка (1.2b) | `swimlane;horizontal=1;startSize=36;whiteSpace=wrap;html=1;fillColor=#fff8e1;strokeColor=#d79b00;rounded=1;fontStyle=1;container=1;collapsible=0;` |
| Заголовок схемы | `text;html=1;strokeColor=none;fillColor=none;align=left;verticalAlign=middle;fontStyle=1;fontSize=16;` |
| Панель «Логика процесса» | `rounded=1;whiteSpace=wrap;html=1;fillColor=#fffef7;strokeColor=#d0d0d0;align=left;verticalAlign=top;spacingLeft=14;spacingTop=12;spacingRight=12;fontSize=11;fontColor=#333333;` |

## Согласование (1.7)

| Смысл | fill / stroke |
|-------|---------------|
| Сохранить поля / системное | `#fff2cc` / `#d6b656` |
| Служебное / информационное | `#dae8fc` / `#6c8ebf` |
| Согласовано / задание / рецензия | `#d5e8d4` / `#82b366` |
| Отклонено / на доработку | `#f8cecc` / `#b85450` |

## Стрелки

| Вид | style |
|-----|-------|
| Обычная | `edgeStyle=orthogonalEdgeStyle;rounded=1;orthogonalLoop=1;jettySize=auto;html=1;strokeColor=#000000;strokeWidth=1.5;` |
| Между статусами / связь воронок | `edgeStyle=orthogonalEdgeStyle;rounded=1;orthogonalLoop=1;jettySize=auto;html=1;strokeWidth=2;strokeColor=#000000;` |
| Новая связь (доработка) | обычная + `strokeColor=#b85450;` |
| Предложение / вопрос | + `dashed=1;` |

Точки выхода / входа задаются в стиле: `exitX=0.5;exitY=1;entryX=0.5;entryY=0;` (вниз центр к центру), `exitX=0;exitY=0.5;` / `exitX=1;exitY=0.5;` — боковые вершины ромба.

## Каркас файла

```xml
<mxfile host="app.diagrams.net">
  <diagram name="Схема" id="page-1">
    <mxGraphModel dx="1400" dy="900" grid="1" gridSize="10" guides="1" tooltips="1" connect="1" arrows="1" fold="1" page="0" pageScale="1" math="0" shadow="0">
      <root>
        <mxCell id="0" />
        <mxCell id="1" parent="0" />
        <!-- блоки: <mxCell id="..." value="текст (HTML можно)" style="..." vertex="1" parent="1"><mxGeometry x="" y="" width="" height="" as="geometry" /></mxCell> -->
        <!-- стрелки: <mxCell id="..." value="подпись" style="..." edge="1" parent="1" source="id" target="id"><mxGeometry relative="1" as="geometry" /></mxCell> -->
      </root>
    </mxGraphModel>
  </diagram>
</mxfile>
```

Блоки внутри колонки / статуса — `parent` = id колонки, координаты относительно неё. В `value` с HTML экранируй `<` `>` `&` `"`.
