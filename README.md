# Архитектура ПО (семинары)
## Урок 6. Принципы построения приложений «чистая архитектура»

Реализовать любые 2 паттерна, прочитать про остальные.
Доделать дз с прошлых семинаров.
Прокси (Proxy): Прокси предоставляет заместитель для другого объекта и управляет доступом к нему. Это может быть полезно для ленивой инициализации объектов, контроля доступа, мониторинга и т. д.

Мост (Bridge): Мост разделяет абстракцию от ее реализации, позволяя им изменяться независимо друг от друга. Этот паттерн используется, когда есть несколько способов расширения классов и когда изменение одного класса не должно влиять на другой.

Фасад (Facade): Фасад предоставляет унифицированный интерфейс к группе интерфейсов подсистемы. Он упрощает работу с сложной системой, предоставляя более простой интерфейс.


Легковес (Flyweight): Этот паттерн используется для оптимизации работы с большим количеством мелких объектов, путем разделения общей части объектов и уменьшения затрат на память.

Заместитель (Proxy): Заместитель предоставляет объект, который выступает в качестве заместителя для другого объекта и контролирует доступ к нему. Это может быть полезно для ленивой инициализации, отложенной загрузки данных и т. д.

По желанию. Разработать полную ERD домена в https://www.dbdesigner.net/. по любому из старых проектов, цель вспомнить о БД.