# Отчёт о тестировании Руководство использования KeyValidator и Инструкцию по установке OpenJDK11

## Отчёт о тестировании Руководство использования KeyValidator

15.01.2021> - 15.01.2021 было проведено Функциональное тестирование приложения Руководство использования KeyValidator 

Проверка соответствия выполненных работ  в соответствии с [Техническим заданием](https://github.com/netology-code/javaqa-homeworks/blob/master/intro/user-manual.md) который был предназначен для работы на платформе Java +8.

Данные проверки были проведены на платформе Java 11.

На тестирование затрачено: 5 часов

## Описание процесса тестирования:
1. Открыть терминал в папке, где загружен файл KeyValidator.class
2. Ввести команду java KeyValidator и ключ

## В результате тестирования выявлены следующие дефекты:

* [Невалидные ключи проходят валидацию](https://github.com/Sininerebane/Validator/issues/2) 

* [Валидные ключи не проходят валидацию](https://github.com/Sininerebane/Validator/issues/1)


* [В качестве тестовых данных использовались данные](https://github.com/netology-code/javaqa-homeworks/blob/master/intro/user-manual.md):

Ключи для проверки

Валидные ключи:

* 8f05e6a7-70e9-33d7-bfe7-b19eae0d8998
* 80b427f8-92cd-3aae-ba04-3927fbe17c6
* b295bc63-9f03-3b4b-af80-969b39f8c262
* 387eedc6-12e9-3b32-9881-63b6b5e85317
* c19a8cf9-5c3a-37c5-b7f3-d16d38a0c180

RESULT FOR: OK
где OK означает, что ключ валидный

Невалидные ключи:

* 18252235-78e0-44a5-8720-556f0c7da17a
* e66075b6-ddad-445e-baf6-161b3289522b
* b6d53250-f07e-4352-a293-6102ddf7f1ca
* c2bc778a-1cb9-46c6-b435-0489649d2a42
* 2fb98b44-93e7-3bdd-a2ad-79347bfe4ad1

RESULT FOR: FAIL
где FAIL означает, что ключ не валидный

## Результаты тестирования

Были проверенные ключи, которые дабавленны тут как валидные и невалидные ключи
Происходит ошибочная валидация невалидных ключей и валидные ключи не проходят валидацию

## Отчёт по установке  OpenJDK11 по инстукции работает под Windows 10 Enterprise

[Следующая инструкция была проверена](https://github.com/netology-code/javaqa-homeworks/blob/master/intro/openjdk11-manual.md)

Результаты тестирования:
Инструкция по установке OpenJDK11 работает под Windows 10 Enterprise
Приложение запускается и совместимо с Java 11
Приложение работает согласно руководству использования
Приложение KeyValidator написано на языке Java и работает из командной строки

## Тестирование производилось в следующем окружении:

* версия и разрядность ОС
Windows 10 Enterprise
4-bit operating system, x64-based processor

* версия Java
openjdk version "11.0.9.1" 2020-11-04
OpenJDK Runtime Environment AdoptOpenJDK (build 11.0.9.1+1)
OpenJDK 64-Bit Server VM AdoptOpenJDK (build 11.0.9.1+1, mixed mode)

