## Реализуйте структуру телефонной книги с помощью HashMap.

### Программа также должна учитывать, что во входной структуре будут повторяющиеся имена с разными телефонами, их необходимо считать, как одного человека с разными телефонами. Вывод должен быть отсортирован по убыванию числа телефонов.


*Краткая документация к заданию*

* ### *Метод add* добавляет человека и его номер телефона в телефонную книгу, а если имя уже есть в книге, то номер добавляется в список номеров для этого имени, в другом случае, если имя не существует, то создается новый список с этим именем именем и списком его номеров.

* ### *Метод getPhoneNum* выполняет поиск всех имён у которых есть этот номер.

* ### *Метод getByName* выполняет поиск контакта, вместе с его телефоном(нами), по имени.

* ### *Метод getAll* возвращает строку со всеми записями, а сами записи сортируются по уменьшению колличевста телефонов, которые есть у того или иного имени.