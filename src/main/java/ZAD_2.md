
*Задание 2. *Ниже список тестовых сценариев. Ваша задача - определить тип каждого теста (юнит-тест,
интеграционный тест, сквозной тест) и объяснить, почему вы так решили.

1Проверка того, что функция addContact корректно добавляет новый контакт в список контактов.

2Проверка того, что при добавлении контакта через пользовательский интерфейс, контакт корректно отображается 
в списке контактов.
3Проверка полного цикла работы с контактом: создание контакта, его редактирование и последующее удаление.


Ответ:

1Проверка того, что функция addContact корректно добавляет новый контакт в список контактов.
ответ:
Данный функционал логично организовать в рамках одного модуля, поэтому в данном случае это юнит-тест.

2Проверка того, что при добавлении контакта через пользовательский интерфейс контакт корректно отображается
списке контактов.
ответ:
Так как используется пользовательский интерфейс и используется в том же результате добавление контакта, 
 можно сказать, что это сквозной тест.

3Проверка полного цикла работы с контактом: создание контакта, его редактирование и последующее удаление.
ответ:
Цикл CRUD для всей системы без использования пользовательского интерфейса,
но взаимодействие всех модулей можно проверить с помощью интеграционных тестов.