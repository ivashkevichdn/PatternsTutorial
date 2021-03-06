# **ПАТТЕРНЫ ПРОЕКТИРОВАНИЯ**

Паттерны (или шаблоны) проектирования описывают
типичные способы решения часто встречающихся
проблем при проектировании программ.

## **Что такое Паттерн?**

**Паттерн проектирования** — это часто встречающееся решение определённой проблемы при проектировании архитектуры программ.

В отличие от готовых функций или библиотек, паттерн нельзя просто взять и скопировать в программу. Паттерн представляет собой не какой-то конкретный код, а общую концепцию решения той или иной проблемы, которую нужно будет ещё подстроить под нужды вашей программы.

Паттерны часто путают с алгоритмами, ведь оба понятия описывают типовые решения каких-то известных проблем. Но если алгоритм — это чёткий набор действий, то паттерн — это высокоуровневое описание решения, реализация которого может отличаться в двух разных программах.

Если привести аналогии, то алгоритм — это кулинарный рецепт с чёткими шагами, а паттерн — инженерный чертёж, на котором нарисовано решение, но не конкретные шаги его реализации.

## **Из чего состоит паттерн?**

Описания паттернов обычно очень формальны и чаще всего состоят из таких пунктов:

- проблема, которую решает паттерн;
- мотивации к решению проблемы способом, который предлагает паттерн;
- структуры классов, составляющих решение;
- примера на одном из языков программирования;
- особенностей реализации в различных контекстах;
- связей с другими паттернами.

Такой формализм в описании позволил создать обширный каталог паттернов, проверив каждый из них на состоятельность.

## **Классификация паттернов**

Паттерны отличаются по уровню сложности, детализации и охвата проектируемой системы. Проводя аналогию со строительством, вы можете повысить безопасность перекрёстка, поставив светофор, а можете заменить перекрёсток целой автомобильной развязкой с подземными переходами.

Самые низкоуровневые и простые паттерны — идиомы. Они не универсальны, поскольку применимы только в рамках одного языка программирования.

Самые универсальные — архитектурные паттерны, которые можно реализовать практически на любом языке. Они нужны для проектирования всей программы, а не отдельных её элементов.

Кроме того, паттерны отличаются и предназначением. В этой книге будут рассмотрены три основные группы паттернов:

- [**Порождающие паттерны**](Generating/README.md) беспокоятся о гибком создании объектов без внесения в программу лишних зависимостей.

- [**Структурные паттерны**](Structural/README.md) показывают различные способы построения связей между объектами.

- [**Поведенческие паттерны**](Behavioral/README.md) заботятся об эффективной коммуникации между объектами.

## **Источники**

Конспект был основан на данных из следующих источников:

- [Рефакторинг.Гуру](https://refactoring.guru/ru/design-patterns)
- [design_patterns (github)](https://github.com/pkolt/design_patterns)
