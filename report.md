Отчёт о тестировании <Руководство использования KeyValidator>

<15.01.2021> - <15.01.2021> было проведено <Функциональное и не функциональное тестирование> приложения <Руководство использования KeyValidator>.
Проверка соответствия выполненных работ  в соответствии с ТЗ https://github.com/netology-code/javaqa-homeworks/blob/master/intro/user-manual.md который был предназначен для работы на платформе Java +8.
Данные проверки были проведены на платформе Java 11.

На тестирование затрачено: <5 часов>


В результате тестирования выявлены следующие дефекты:


Невалидный ключ "2fb98b44-93e7-3bdd-a2ad-79347bfe4ad1" воспринимаеться KeyValidator-ом как валидный
<https://github.com/Sininerebane/Third_one/issues/1>

Валидный ключ "387eedc6-12e9-3b32-9881-63b6b5e85317" воспринимаеться KeyValidator-ом как невалидный
<https://github.com/Sininerebane/Third_one/issues/2>

Валидный ключ "80b427f8-92cd-3aae-ba04-3927fbe17c6" воспринимаеться KeyValidator-ом как невалидный
<https://github.com/Sininerebane/Third_one/issues/3>

В процессе тестирования использовались следующие артефакты*:

<Чек лист>
<Тест кейсы>

Чек лист: 
KeyValidator определяет валидный ключ
KeyValidator определяет невалидный ключ
KeyValidator не выдаст валидный или невалидный ключ, если не будет введен какой либо ключ

В качестве тестовых данных использовались данные <https://github.com/netology-code/javaqa-homeworks/blob/master/intro/user-manual.md>:

Ключи для проверки

Валидные ключи:

8f05e6a7-70e9-33d7-bfe7-b19eae0d8998
80b427f8-92cd-3aae-ba04-3927fbe17c6
b295bc63-9f03-3b4b-af80-969b39f8c262
387eedc6-12e9-3b32-9881-63b6b5e85317
c19a8cf9-5c3a-37c5-b7f3-d16d38a0c180

RESULT FOR: OK
где OK означает, что ключ валидный

Невалидные ключи:

18252235-78e0-44a5-8720-556f0c7da17a
e66075b6-ddad-445e-baf6-161b3289522b
b6d53250-f07e-4352-a293-6102ddf7f1ca
c2bc778a-1cb9-46c6-b435-0489649d2a42
2fb98b44-93e7-3bdd-a2ad-79347bfe4ad1

RESULT FOR: FAIL
FAIL - невалидный

Тестирование производилось в следующем окружении:

<версия и разрядность ОС>
Windows 10 Enterprise
4-bit operating system, x64-based processor

<версия Java>
openjdk version "11.0.9.1" 2020-11-04
OpenJDK Runtime Environment AdoptOpenJDK (build 11.0.9.1+1)
OpenJDK 64-Bit Server VM AdoptOpenJDK (build 11.0.9.1+1, mixed mode)

