# **Порождающие паттерны проектирования**

Эти паттерны отвечают за удобное и безопасное создание новых объектов или даже целых семейств объектов.

## Абстрактная фабрика _(Abstract Factory)_

![Абстрактная фабрика!](/images/abstract-factory-mini.png)
**Абстрактная фабрика** — это порождающий паттерн проектирования, который решает проблему создания целых семейств связанных продуктов, без указания конкретных классов продуктов.

Абстрактная фабрика задаёт интерфейс создания всех доступных типов продуктов, а каждая конкретная реализация фабрики порождает продукты одной из вариаций. Клиентский код вызывает методы фабрики для получения продуктов, вместо самостоятельного создания с помощью оператора new. При этом фабрика сама следит за тем, чтобы создать продукт нужной вариации.

**Пример кода:** [Python](Python/abstract_factory.py)

## Строитель _(Builder)_

![Строитель!](/images/builder-mini.png)
**Строитель** — это порождающий паттерн проектирования, который позволяет создавать объекты пошагово.

В отличие от других порождающих паттернов, Строитель позволяет производить различные продукты, используя один и тот же процесс строительства.

**Пример кода:** [Python](Python/builder.py)

## Фабричный метод _(Factory Method)_

![Фабричный метод!](/images/factory-method-mini.png)
**Фабричный метод** — это порождающий паттерн проектирования, который решает проблему создания различных продуктов, без указания конкретных классов продуктов.

Фабричный метод задаёт метод, который следует использовать вместо вызова оператора new для создания объектов-продуктов. Подклассы могут переопределить этот метод, чтобы изменять тип создаваемых продуктов.

**Пример кода:** [Python](Python/factory_method.py)

## Прототип _(Prototype)_

![Прототип!](/images/prototype-mini.png)
**Прототип** — это порождающий паттерн, который позволяет копировать объекты любой сложности без привязки к их конкретным классам.

Все классы — Прототипы имеют общий интерфейс. Поэтому вы можете копировать объекты, не обращая внимания на их конкретные типы и всегда быть уверены, что получите точную копию. Клонирование совершается самим объектом-прототипам, что позволяет ему скопировать значения всех полей, даже приватных.

**Пример кода:** [Python](Python/prototype.py)

## Одиночка _(Singleton)_

![Одиночка!](/images/singleton-mini.png)
**Одиночка** — это порождающий паттерн, который гарантирует существование только одного объекта определённого класса, а также позволяет достучаться до этого объекта из любого места программы.

Одиночка имеет такие же преимущества и недостатки, что и глобальные переменные. Его невероятно удобно использовать, но он нарушает модульность вашего кода.

Вы не сможете просто взять и использовать класс, зависящий от одиночки в другой программе. Для этого придётся эмулировать присутствие одиночки и там. Чаще всего эта проблема проявляется при написании юнит-тестов.

**Пример кода:** [Python](Python/singleton.py), [JavaScript](JavaScript/singleton.js)