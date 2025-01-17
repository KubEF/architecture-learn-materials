# Паттерны проектирования: Краткое описание

## Структурные паттерны

### Компоновщик (Composite)

Используется для представления древовидной структуры объектов. Позволяет работать с группой объектов так же, как с единичным объектом.

![Компоновщик](../out/patterns/composite/composite.svg)

### Декоратор (Decorator)

Динамически добавляет объекту новые функциональности, не изменяя его структуры. Полезен для гибкого расширения поведения.

![Декоратор](../out/patterns/decorator/decorator.svg)

### Адаптер (Adapter)

Позволяет объектам с несовместимыми интерфейсами работать вместе, преобразуя интерфейс одного объекта в интерфейс, ожидаемый другим.

![Адаптер](../out/patterns/adapter/adapter.svg)

### Заместитель (Proxy)

Предоставляет объект-заместитель, который контролирует доступ к реальному объекту, например, для добавления кэширования или защиты.

![Proxy](../out/patterns/proxy/proxy.svg)

### Фасад (Facade)

Предоставляет упрощённый интерфейс к сложной системе классов, скрывая её детали.

![Facade](../out/patterns/facade/facade.svg)

### Приспособленец (Flyweight)

Оптимизирует использование памяти за счёт повторного использования объектов. Применяется для управления большим количеством мелких объектов.

![Flyweight](../out/patterns/flyweight/flyweight.svg)

### Мост (Bridge)

Позволяет разделить абстракцию от её реализации таким образом, чтобы они могли меняться независимо друг от друга.

![Bridge](../out/patterns/bridge/bridge.svg)

## Порождающие паттерны

### Фабричный метод (Factory Method)

Определяет интерфейс для создания объектов, позволяя подклассам решать, какой класс создавать.

![Factory method](../out/patterns/factory_method/factory_method.svg)

### Абстрактная фабрика (Abstract Factory)

Позволяет создавать семейства взаимосвязанных объектов без указания их конкретных классов.

![Abstract factory](../out/patterns/abstract_factory/abstract_factory.svg)

### Одиночка (Singleton)

Обеспечивает существование только одного экземпляра класса и предоставляет глобальную точку доступа к нему.

![Singleton](../out/patterns/singleton/singleton.svg)

### Ленивая инициализация (Lazy initialization)

Используется для откладывания создания объекта или выполнения ресурсоёмкой операции до момента их непосредственного использования.

![Lazy initialization](../out/patterns/lazy_initialization/lazy_initialization.svg)

### Пулл объектов (Object pull)

Предоставляет способ повторного использования объектов, которые слишком дорого создавать и уничтожать.

![Object pull](../out/patterns/object_pull/object_pull.svg)

### Прототип (Prototype)

Позволяет создавать объекты на основе копирования существующих экземпляров.

![Prototype](../out/patterns/prototype/prototype.svg)

### Строитель (Builder)

Используется для пошагового создания сложных объектов. Он отделяет процесс построения объекта от его представления, позволяя создавать разные представления одного и того же типа объекта.

![Builder](../out/patterns/builder/builder.svg)

## Поведенческие паттерны

### Стратегия (Strategy)

Определяет семейство алгоритмов, инкапсулирует их и позволяет подменять алгоритмы на лету.

![Strategy](../out/patterns/strategy/strategy.svg)

### Шаблонный метод (Template Method)

Определяет скелет алгоритма в базовом классе, позволяя подклассам переопределять отдельные шаги.

![Template method](../out/patterns/template_method/template_method.svg)

### Посредник (Mediator)

Обеспечивает взаимодействие между объектами, уменьшая их взаимозависимость.

![Mediator](../out/patterns/mediator/mediator.svg)

### Команда (Command)

Инкапсулирует запрос в виде объекта, позволяя откладывать его выполнение или поддерживать историю запросов.

![Command](../out/patterns/comand/command.svg)

### Цепочка ответственности (Chain of Responsibility)

Передаёт запрос по цепочке обработчиков до тех пор, пока он не будет обработан.

![Chain](../out/patterns/chain/chain.svg)

### Наблюдатель (Observer)

Позволяет одному объекту уведомлять другие о своих изменениях.

![Observer](../out/patterns/observer/observer.svg)

### Состояние (State)

Позволяет объекту изменять своё поведение в зависимости от внутреннего состояния.

![State](../out/patterns/state/state.svg)

### Посетитель (Visitor)

Позволяет добавлять новые операции для классов без изменения их структуры, перемещая реализацию в отдельный класс.

![Visitor](../out/patterns/visitor/visitor.svg)

### Хранитель (Memento)

Сохраняет внутреннее состояние объекта для последующего восстановления, не нарушая его инкапсуляции.

![Memento](../out/patterns/memento/memento.svg)

### Интерпретатор (Interpreter)

Реализует интерпретацию заданного языка или выражения.

![Interpreter](../out/patterns/interpreter/interpreter.svg)

### Итератор (Iterator)

Предоставляет доступ к элементам коллекции без раскрытия её внутреннего представления.

![Iterator](../out/patterns/iterator/iterator.svg)
