# Зависимости в тестах
=========================================

## Задание 1. 
Ответьте письменно на вопросы:
1) Почему использование тестовых заглушек может быть полезным при написании модульных тестов?

       Ответ:
       Это позволяет упростить процесс тестирования, изолировать тестируемый компонент от 
       внешних зависимостей и контролировать поведение зависимых компонентов в ходе тестирования.

2) Какой тип тестовой заглушки следует использовать, если вам нужно проверить, что метод был вызван 
   с определенными аргументами?

       Ответ: 
       Mock - заглушки, которые позволяют контролировать вызов методов, передачу аргументов и 
       проверку ожидаемого поведения тестируемой системы.

3) Какой тип тестовой заглушки следует использовать, если вам просто нужно вернуть определенное значение 
   или исключение в ответ на вызов метода?

       Ответ: 
       Stub - простейшие заглушки, которые возвращают заранее определенные значения на 
       определенные входные данные.

4) Какой тип тестовой заглушки вы бы использовали для имитации  взаимодействия с внешним API или базой данных?

       Ответ: 
       Fake - заглушки, часто используемые для тестирования баз данных, файловых систем или внешних сервисов, 
       когда настройка реального компонента непрактична или требует много времени.

------------------------------------------
## Задание 2.
У вас есть класс BookService, который использует интерфейс BookRepository для получения информации 
о книгах из базы данных. Ваша задача написать unit-тесты для BookService, используя Mockito для создания 
мок-объекта BookRepository.

Формат сдачи: воспользуйтесь одним из вариантов: Ссылка на репозиторий Git или Прикрепленный архив
Письменное задание 1 можно также разместить в репозитории или разместить текстом в окне сдачи практического задания.