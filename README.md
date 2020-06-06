# Проект по теории конечных графов
Проектное задание основано на задачах об оптимальном размещении объектов инфраструктуры города, задаче о прокладке пассивных оптических сетей (passive optical network).
# 1 «Оценка удобства размещения объектов инфраструктуры города»
На карте заданы местоположения M объектов инфраструктуры города (например,
больниц) и случайным образом выбирается N узлов (домов).
1. Для каждого узла (дома)
  a. определить ближайший от узла объект (путь “туда”), ближайший к объекту узел (путь “обратно”), объект расстояние (время подъезда) до которого и обратно минимально (“туда и обратно”).
  b. определить объекты, расположенные не далее, чем в X км (или достижимые не более, чем за Y минут) для каждого из трех вариантов “туда”, “обратно”, “туда и обратно”.
2. Определить, какой из объектов расположен так, что время/расстояние между ним и самым дальним домом минимально (“туда”, “обратно”, “туда и обратно”).
3. Для какого объекта инфраструктуры сумма кратчайших расстояний от него до всех домов минимальна.
4. Для какого объекта инфраструктуры построенное дерево кратчайших путей имеет минимальный вес.
# 2 «Планирование новых объектов»
На карте случайным образом выбраны N узлов (домов) и один из объектов инфраструктуры.
1. Построить дерево кратчайших путей от объекта до выбранных узлов. Вычислить общую длину дерева, а также сумму кратчайших расстояний от объекта до всех заданных узлов.
2. Разбить выбранные узлы на кластеры, используя метод полной связи (сomplete-linkage clustering). Построить дендрограмму разбиения узлов.
3. Пусть узлы разбиты на k кластеров.
  a. Найти расположение центра масс (центроида) для каждого кластера;
  b. Построить дерево кратчайших путей от объекта до центроидов.
  c. Для каждого кластера построить дерево кратчайших путей от центроида до
  всех вершин кластера.
  d. Найти длину построенного дерева и сумму кратчайших расстояний от
  объекта до всех заданных узлов.
4. Сравнить найденные в п.1 и 3 величины для k=2, 3, 5
