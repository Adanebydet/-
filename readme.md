# Итоговая проверочная работа
Условия задачи
-

Задача алгоритмически не встречается, однако для выполнения проверочной работы необходимо:

- Создать репозиторий на GitHub
- Нарисовать блок-схему алгоритма *(можно использовать блок-схему основной содержательной части, если выделить ее в отдельный метод)*
- Снабдить репозиторий оформленным текстовым описанием решений *(файл README.md)*
- Написать программу, определяющую установленную шкалу
- Использовать контрольную работу в этой работе над рассмотрением проекта


Задача:
-
Написать программу, которая из массива массива строк формирует новый массив из строк, длина которого меньше, либо равна 3 символам. Первоначальный массив можно ввести с помощью комбинации, либо нажать на начало выполнения алгоритма. Не рекомендуется использовать коллекции, лучше всего собирать уникальные массивы.

Примеры:
-
 [“Hello”, “2”, “world”, “:-)”] → [“2”, “:-)”]

 [“1234”, “1567”, “-2”, “computer science”] → [“-2”]

 [“Russia”, “Denmark”, “Kazan”] → []


## Алгоритм работы программы.
![Алгоритм работы программы.](%D0%98%D1%82%D0%BE%D0%B3%D0%BE%D0%B2%D0%B0%D1%8F.drawio.png)


# Решение

Необходимые действия:
-
1. Запросить ввод текста от пользователя.
2. Перевести введённый текст в массив.
3. Вывести массив на экран.
4. Вывести на экран элементы массива, подходящие по условиям задачи.