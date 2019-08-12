# ПАТТЕРНЫ ПРОЕКТИРОВАНИЯ

Паттерны (или шаблоны) проектирования описывают
типичные способы решения часто встречающихся
проблем при проектировании программ.

## Классификация паттернов

Паттерны отличаются по уровню сложности, детализации и охвата проектируемой системы. Проводя аналогию со строительством, вы можете повысить безопасность перекрёстка, поставив светофор, а можете заменить перекрёсток целой автомобильной развязкой с подземными переходами.

Самые низкоуровневые и простые паттерны — идиомы. Они не универсальны, поскольку применимы только в рамках одного языка программирования.

Самые универсальные — архитектурные паттерны, которые можно реализовать практически на любом языке. Они нужны для проектирования всей программы, а не отдельных её элементов.

Кроме того, паттерны отличаются и предназначением. В этой книге будут рассмотрены три основные группы паттернов:

- **Порождающие паттерны** беспокоятся о гибком создании объектов без внесения в программу лишних зависимостей.

- **Структурные паттерны** показывают различные способы построения связей между объектами.

- **Поведенческие паттерны** заботятся об эффективной коммуникации между объектами.

## **Порождающие паттерны**

### Абстрактная фабрика _(Abstract Factory)_

Позволяет создавать семейства связанных объектов, не привязываясь к конкретным классам создаваемых объектов.

**Пример кода:** [Python](Generating/Python/abstract_factory.py)

### Строитель _(Builder)_

Позволяет создавать сложные объекты пошагово. Строитель даёт возможность использовать один и тот же код строительства для получения разных представлений объектов.

**Пример кода:** [Python](Generating/Python/builder.py)
