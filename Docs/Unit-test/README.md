# Методические рекомендации к разработке модульных тестов

Для автоматизации модульного тестирования выделен проект в папке UnitTestOfTimetableOfClasses
Эта папка содержит файлы соответсвующих шаблону UT_Method_Class, где Method - тестируемый метод, Class - класс в котором находится тестируемый метод.

## Требования к тестам

Имя теста должно соответсовать шаблону Test_111_1, где 111 это номер Story для которой пишутся тесты, 1 - порядковый номер теста.
Для методов класса Assert, проверяющие актуальные значения, необходимо использовать методы с перегрузкой в котороых нужно указывать комментарий.
В комментарии необходимо указать причину сбоя, если условие не выполнено. Все тесты относящиеся к задаче, должны выполнится удачно на сервере Azure.