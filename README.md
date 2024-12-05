
# Лабораторная работа 4.

## Задание:  

1. Для начала создаю образ "aafire" на базе образа ubuntu:latest, предустанавливаю libaa-bin (aafire), iputils (ping):

Содержимое Dockerfile:
![image](https://github.com/user-attachments/assets/8581265c-5acf-42c8-98fd-97a64c5d8803)

Сборка образа:
![image](https://github.com/user-attachments/assets/c2c91767-8e0e-4434-9b6c-014847f58ccd)

Образ действительно собрался:
![image](https://github.com/user-attachments/assets/e9e26545-4515-4176-8745-c7ed5b46ce8d)

2. Запускаю первый контейнер, называю его "aafire-1": 

![image](https://github.com/user-attachments/assets/170ac3bc-98da-4f4f-8845-2432f46fc1c9)

Процесс работы aafire:
![image](https://github.com/user-attachments/assets/d634868a-27e3-4ff6-8f73-ffb246ffab50)

3. Запускаю второй контейнер, называю его "aafire-2":
   
![image](https://github.com/user-attachments/assets/002ae15b-d589-453c-8da7-10f5846fd576)

Получившиеся контейнеры:
![image](https://github.com/user-attachments/assets/785c809c-5ed5-4bbe-a268-7f4c2a7fc51f)

4. Настраиваю сеть между двумя контейнерами:

    1. Создаю сеть:
       ![image](https://github.com/user-attachments/assets/823c95da-ba00-4048-a529-b294a1b191be)

    2. Подключаю контейнеры к сети:
       ![image](https://github.com/user-attachments/assets/e57b9cb9-2a65-49de-9b96-218e2a14d2f6)

    3. Вывожу настройки созданной ранее сети:
       ![image](https://github.com/user-attachments/assets/4f81f2c2-c5ea-4d4b-98a8-1b65bd088f77)

    4. Проверяю доступность одного контейнера изнутри другого при помощи `ping`:
       ![image](https://github.com/user-attachments/assets/34e1fa19-8c2f-4c55-b3c6-644c0af54806)
