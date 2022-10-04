# TRITPO_2
# Требования к проекту 
# Содержание 
[1 Введение](https://github.com/Karabas18/TRITPO_2/blob/main/README.md#1-введение)  
[2 Требования пользователя](https://github.com/Karabas18/TRITPO_2/blob/main/README.md#2-требования-пользователя)  
[2.1 Программные интерфейсы](https://github.com/Karabas18/TRITPO_2/blob/main/README.md#21-программные-интерфейсы)  
[2.2 Интерфейс пользователя](https://github.com/Karabas18/TRITPO_2/blob/main/README.md#22-интерфейс-пользователя)  
[2.3 Характеристики пользователя](https://github.com/Karabas18/TRITPO_2/blob/main/README.md#23-характеристики-пользователей)  
[2.4 Предположения и зависимости](https://github.com/Karabas18/TRITPO_2/blob/main/README.md#24-предположения-и-зависимости)  
[3 Системные требования](https://github.com/Karabas18/TRITPO_2/blob/main/README.md#3-системные-требования)  
[3.1 Функциональные требования](https://github.com/Karabas18/TRITPO_2/blob/main/README.md#31-функциональные-требования)  
[3.2 Нефункциональные требования](https://github.com/Karabas18/TRITPO_2/blob/main/README.md#32-нефункциональные-требования)  
[3.2.1 Атрибуты качества](https://github.com/Karabas18/TRITPO_2/blob/main/README.md#321-атрибуты-качества)  
[3.2.2 Требования к безопасности](https://github.com/Karabas18/TRITPO_2/blob/main/README.md#322-требования-к-безопасности)  
[3.2.3 Ограничения](https://github.com/Karabas18/TRITPO_2/blob/main/README.md#323-ограничения)
## 1 Введение  
Задумкой проекта является создание web приложения по настольной игре "Взрывные котята". Несколько пользователей одновременно пользуются web-приложением. Они имеют весь функционал взаимодействий, который есть в оригинальной настольной игре.([Правила](https://hobbyworld.ru/download/rules/Exploding%20Kittens_Rules.pdf)).
## 2 Требования пользователя  
## 2.1 Программные интерфейсы 
Все данные будут храниться в базе данных mysql. Приложение должно быть написано на языке программирования Java. 
## 2.2 Интерфейс пользователя  
## Окно пользователя  
Главное меню "Взрывные котята".  
![](https://github.com/Karabas18/TRITPO_2/blob/main/Main_3.png)  
Вкладка "Игра" в которой пользователи играют.  
![](https://github.com/Karabas18/TRITPO_2/blob/main/Game.png) 
## 2.3 Характеристики пользователей  
Пользователь web-приложения - любой человек с доступом в сеть Интернет. Это люди, которые хоть немного знакомы с настольной игрой.
## 2.4 Предположения и зависимости 
Для web-приложения требуется компьютер и немного свободного места.
## 3 Системные требования  
Приложение требует установленной базы данных MySQL, а также небольшого количества свободного места на диске.
## 3.1 Функциональные требования 
1.Возможность играть с 2-мя и более игроками.  
2.Возможность играть с ботом.  
3.Возможность добавлять прошлых игроков в "друзья".  
4.Возможность приглашать друзей в свою игру.   
5.Реализация рейтинговой системы.  
6.Коммуникация с игроками во время игры.
## 3.2 Нефункциональные требования  
## 3.2.1 Атрибуты качества
Атрибуты важные для пользователя:  
1.Удобство в использовании  
2.Понятный интерфейс     
## 3.2.2 Требования к безопасности  
Информация о пользователях хранится в базе данных. Личные данные должны кодироваться, чтобы при краже злоумышленники не могли пользоваться ими.  
## 3.2.3 Ограничения    
Язык программирования Java, дизайн должен соответствовать пункту интерфейс пользователя.
