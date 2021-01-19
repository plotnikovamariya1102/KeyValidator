# **Отчёт о тестировании KeyValidator**

## **Краткое описание**

Дата начала 19.01.20121 - Дата окончания 19.01.2021.

Было проведено функциональное тестирование приложения KeyValidator с использование валидных и невалидных данных (данные: 5 валидных ключей, 5 невалидных ключей), .

На тестирование затрачено: 1 час.

В результате тестирования выявлены следующие дефекты:

* [Результат FAIL в приложении KeyValidator при проверке Валидных ключей](https://github.com/plotnikovamariya1102/Java-keyvalidator/issues/2)
* [Результат ОК в приложении KeyValidator при проверке Невалидных ключей](https://github.com/plotnikovamariya1102/Java-keyvalidator/issues/2)

## **Описание процесса тестирования**
В процессе тестирования использовались следующие артефакты:

* [Руководство использования KeyValidator](https://github.com/netology-code/javaqa-homeworks/blob/master/intro/user-manual.md)

* Баг-репорт: [Результат FAIL в приложении KeyValidator при проверке Валидных ключей](https://github.com/plotnikovamariya1102/Java-keyvalidator/issues/2)
* Баг-репорт: [Результат ОК в приложении KeyValidator при проверке Невалидных ключей](https://github.com/plotnikovamariya1102/Java-keyvalidator/issues/2)

В качестве тестовых данных использовались данные из [Руководство использования KeyValidator](https://github.com/netology-code/javaqa-homeworks/blob/master/intro/user-manual.md):

Валидные ключи, ожидаемый результат ОК:
* 8f05e6a7-70e9-33d7-bfe7-b19eae0d8998
* 80b427f8-92cd-3aae-ba04-3927fbe17c6
* b295bc63-9f03-3b4b-af80-969b39f8c262
* 387eedc6-12e9-3b32-9881-63b6b5e85317
* c19a8cf9-5c3a-37c5-b7f3-d16d38a0c180

Невалидные ключи, ожидаемый результат FAIL:
* 18252235-78e0-44a5-8720-556f0c7da17a
* e66075b6-ddad-445e-baf6-161b3289522b
* b6d53250-f07e-4352-a293-6102ddf7f1ca
* c2bc778a-1cb9-46c6-b435-0489649d2a42
* 2fb98b44-93e7-3bdd-a2ad-79347bfe4ad1

Тестирование производилось в следующем окружении:

* Windows 10, 64-разрядная.
* java -version версия openjdk "11.0.9.1" 2020-11-04
* Среда выполнения OpenJDK AdoptOpenJDK (сборка 11.0.9.1 + 1)
* 64-разрядная серверная виртуальная машина OpenJDK AdoptOpenJDK (сборка 11.0.9.1 + 1, смешанный режим)
* Приложение KeyValidator.class