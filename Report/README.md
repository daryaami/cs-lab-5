# Лабораторная работа №5

## Введение

Склонируем репозиторий локально
![Скриншот 1](/screenshots/Screenshot_1.png)  

Создадим файл **example.txt** и добавим в него текст. Создадим коммит и запушим в main ветку.
![Скриншот 2](/screenshots/Screenshot_2.png)  
![Скриншот 3](/screenshots/Screenshot_3.png)  

Создадим новую ветку ```feature-branch``` и переключимся на нее. 
![Скриншот 4](/screenshots/Screenshot_4.png)  

Отредактируем наш файл и снова создадим коммит
![Скриншот 5](/screenshots/Screenshot_5.png)  
![Скриншот 6](/screenshots/Screenshot_6.png)  

Вернемся в ветку main и сделаем мердж новой ветки в ветку main.
![Скриншот 7](/screenshots/Screenshot_7.png)  

Файл успешно обновлен и находится в основной ветке
![Скриншот 8](/screenshots/Screenshot_8.png)  


## Работа с ветками
Создадим новый файл **book.md** и добавим в него пример структуры книги. 
![Скриншот 9](/screenshots/Screenshot_9.png)  

Создадим новую ветку с названием **feature-login**
![Скриншот 10](/screenshots/Screenshot_10.png) 

Внесем изменения в наш файл (добавим новую главу)
![Скриншот 11](/screenshots/Screenshot_11.png) 

Закоммитим изменения и отправим ветку **feature-login** на git hib
![Скриншот 12](/screenshots/Screenshot_12.png) 


## Работа с удаленным репозиторием
Переключимся на ветку main. Добавим изменения в наш файл **book.md** (добавим описание возле названия книги)
![Скриншот 13](/screenshots/Screenshot_13.png) 

Запушим ветку с изменениями на git hub
![Скриншот 14](/screenshots/Screenshot_14.png) 

## Моделирование конфликта
Вернемся в ветку **feature-login** и изменим вторую главу в том же файле
![Скриншот 15](/screenshots/Screenshot_15.png) 
![Скриншот 16](/screenshots/Screenshot_16.png) 

Отправим изменения на гит хаб
![Скриншот 17](/screenshots/Screenshot_17.png) 

## Разрешение конфликта
Из ветки **feature-login** попробуем слить изменения с **main**. Это вызывает конфликт, так как в двух ветках этот файл изменен по-разному.
![Скриншот 18](/screenshots/Screenshot_18.png) 

Разрешим конфликт в файле выбрав нужные изменения.
![Скриншот 19](/screenshots/Screenshot_19.png) 
![Скриншот 20](/screenshots/Screenshot_20.png) 

Запушим изменения
![Скриншот 21](/screenshots/Screenshot_21.png) 


## Автоматизация проверки формата файлов при коммите
