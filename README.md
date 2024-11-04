# Лабораторная работа 2

## Разминка (ее в отчет включать не нужно!)

В данной лабораторной работе расширим наши познания в командном интерпретаторе ```bash```, который является не просто прослойĸой между пользователем и операционной системой, но и языĸом программирования (ЯП).

Итаĸ, перед тем ĸаĸ выполнять задание:

1. Создайте файл с расширением .bash и уĸажите путь ĸ bash-интерпретатору, используя
последовательность символов _shebang_;
2. Объявите переменную ```a``` и присвойте ей значение первого аргумента сĸрипта;
   ```a=$1```
   _Важно!_ Символ присваивания = не должен содержать пробелов.
3. Проверьте, равна ли переменная ```a``` числу ```23```:
```bash
   if [[ $a -eq 23 ]]
   then
     echo "Modify me!"
   else
     echo '$a is not "23"'
   fi
```
4. Запустите скрипт с одним аргументом. Удостоверьтесь, что все работает таĸ, ĸаĸ вы
запрограммировали.

## Задание лабораторной работы (вот только его и нужно включить в отчет!)

На основе изученного материала лабораторной работы, лекций (2 и 3), дополнительных источников напишите скрипт, который на вход принимает IPv4-адрес в десятичном формате, а на выходе обеспечивает данный IP-адрес в двоичном формате.

Пример входных данных:

```192.168.10.1```

Пример выходныx данных:

```11000000.10101000.00001010.00000001```

### Как успешно сдать работу?

Создать свой репозиторий из шаблона этого. Как это делается - "Use this template" -> "Create a new repository" и сделайте его public. 

Находясь уже в своем репозитории - создайте новый файл формата .md и там оформляйте отчет. В отчете опишите все шаги которые вы делали, чтобы получить финальный результат работы. Необходимы только скриншоты скрипта и примера его выполнения!

Что вам нужно знать, чтобы успешно защитить работу:

Переменные; как выполнять операции; условные конструкции; функции; циклы; как работать с массивом; как посмотреть права доступа к файлам; как выдавать права доступа; что такое и зачем нужен ip адрес и маска подсети.

## Дополнительные источники

1. [Присваивание значений переменным.](https://se.ifmo.ru/~ad/Documentation/ABS_Guide_ru.html#VARASSIGNMENT)
2. [Подстановка переменных.](https://se.ifmo.ru/~ad/Documentation/ABS_Guide_ru.html#VARSUBN)
3. [Арифметические операции.](https://se.ifmo.ru/~ad/Documentation/ABS_Guide_ru.html#ARITHEXP)
4. [Проверка условий.](https://se.ifmo.ru/~ad/Documentation/ABS_Guide_ru.html#TESTS)
5. stackoverflow.com
6. Хорошая ĸнига по Shell/bash в Linux - "Learn Linux Shell Scripting – Fundamentals of Bash 4.4" Sebastiaan
Tammer
7. [Функции.](https://se.ifmo.ru/~ad/Documentation/ABS_Guide_ru.html#FUNCTIONS)
8. [Функции и рекурсивные функции.](https://habr.com/ru/company/ruvds/blog/327248/)
9. [Циклы.](https://se.ifmo.ru/~ad/Documentation/ABS_Guide_ru.html#LOOPS)
10. [Массивы](https://se.ifmo.ru/~ad/Documentation/ABS_Guide_ru.html#ARRAYS)
11. [Про двоичную систему и IP-адрес](https://zametkinapolyah.ru/kompyuternye-seti/4-4-dvoichnye-chisla-i-dvoichnaya-sistema-schisleniya-perevod-chisla-v-dvoichnuyu-sistemu-schisleniya-iz-desyatichnoj.html)
12.  В. Олифер, Н. Олифер "Компьютерные сети. Принципы, технологии, протоколы. Учебник" (2016)
![image](https://github.com/user-attachments/assets/2c7f9e0c-cd0d-4b5e-9064-da4eb8a70499)
![image](https://github.com/user-attachments/assets/a4ecdc9d-cd4d-4541-8159-6eccb7f6fde0)
![image](https://github.com/user-attachments/assets/fbf68802-d62a-4400-b7e7-f576fdf7d19c)
![image](https://github.com/user-attachments/assets/eaec180c-3fff-42fb-bb5e-445abc083dea)
![image](https://github.com/user-attachments/assets/099410ff-5195-4f52-96d5-77442c429987)
![image](https://github.com/user-attachments/assets/9c842d82-cc19-4249-98c3-51036b8b0b24)
![image](https://github.com/user-attachments/assets/b05feb0a-1ead-4d7a-a655-33615911be64)
![image](https://github.com/user-attachments/assets/46bacb6e-56dc-45cc-a7bb-f6a15a550a19)
![image](https://github.com/user-attachments/assets/06491be5-bb17-43df-ab7f-07500b28ef03)
![image](https://github.com/user-attachments/assets/771163e8-4cd5-42db-82cb-672475b55c02)
![image](https://github.com/user-attachments/assets/491ca4b4-7df9-4f61-896f-d5433a45a6f0)
![image](https://github.com/user-attachments/assets/dc2a0aa8-5f16-4242-963a-fdec1fa201bc)
![image](https://github.com/user-attachments/assets/f3017c62-0f3a-4e46-9a5a-3eed43fa9a70)
![image](https://github.com/user-attachments/assets/caf33a77-12a3-425e-8963-451c5b15a964)
