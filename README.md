KICK START CHAPTER A

Необходимо написать приложение и тесты к нему согласно требованиям, приведенным ниже. В приложении должна быть реализована функциональность, определенная индивидуальным заданием.

Овал. Разработать классы Точка и Овал (задан двумя точками описанного прямоугольника). Создать методы и тесты: вычисления площади и периметра фигуры; составляют ли точки овал (не лежат ли три точки на одной прямой, параллельной осям координат); пересекает ли фигура оси координат; является ли фигура овалом, кругом.

KICK START CHAPTER B

Требования

 1. Площади, Объемы, Периметры фигур должны храниться в объекте класса-регистратора.
 2. Любое изменение параметра фигуры должно вызывать пересчет соответствующих значений в классе-регистраторе. Для решения данной задачи использовать паттерны Observer (можно использовать Flow API) и Singleton (потокобезопасные варианты использовать запрещено).
 
 3. Все созданные объекты геометрических фигур сохранить в объекте-репозитории.
 4. Используя шаблон Repository, разработать спецификации по добавлению, удалению и изменению объектов репозитория.
 5. Разработать спецификации по поиску объектов и групп объектов в репозитории. По ID, по имени, по координатам (например, найти все объекты точки которых находятся в первом квадранте, найти все объекты площади поверхности (объемы, периметры) которых заключены в заданный диапазон, найти объекты находящиеся на расстоянии в заданном диапазоне от начала координат).
 6. Разработать методы сортировки наборов объектов по ID, по имени, по координатам X первой точки, по координатам Y первой точки и т.д. Использовать интерфейс Comparator.