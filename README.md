# TRITPO_2
# Требования к проекту 
# Содержание 
# Введение 
[1.1 Название продукта](https://github.com/Karabas18/TRITPO_2/blob/main/README.md#1.1й-название-продукта)
[1.2 Назначение документа](https://github.com/Karabas18/TRITPO_2/blob/main/README.md#1.2-назначение-документа)  
[1.3 Бизнес требования](https://github.com/Karabas18/TRITPO_2/blob/main/README.md#1.3-бизнес-требования)  
[1.3.1 Исходные данные](https://github.com/Karabas18/TRITPO_2/blob/main/README.md#1.3.1-исходные-данные)
[1.3.2 Возможности бизнеса](https://github.com/Karabas18/TRITPO_2/blob/main/README.md#1.3.2-возможности-бизнеса)
[1.3.3 Границы проекта](https://github.com/Karabas18/TRITPO_2/blob/main/README.md#1.3.3-границы-проекта)  
[1.4 Аналоги](https://github.com/Karabas18/TRITPO_2/blob/main/README.md#1.4-аналоги)  
[1.4.1 Отличие от аналогов](https://github.com/Karabas18/TRITPO_2/blob/main/README.md#1.4.1-отличие-от-аналогов)  
[2 Требования пользователя](https://github.com/Karabas18/TRITPO_2/blob/main/README.md#2-требования-пользователя)  
[2.1 Программные интерфейсы](https://github.com/Karabas18/TRITPO_2/blob/main/README.md#21-программные-интерфейсы)  
[2.2 Интерфейс пользователя](https://github.com/Karabas18/TRITPO_2/blob/main/README.md#22-интерфейс-пользователя)  
[2.3 Характеристики пользователя](https://github.com/Karabas18/TRITPO_2/blob/main/README.md#23-характеристики-пользователей)  
[2.3.1 Аудитория приложения](https://github.com/Karabas18/TRITPO_2/blob/main/README.md#231-аудитория-приложения) 
[2.4 Предположения и зависимости](https://github.com/Karabas18/TRITPO_2/blob/main/README.md#24-предположения-и-зависимости)  
[3 Системные требования](https://github.com/Karabas18/TRITPO_2/blob/main/README.md#3-системные-требования)  
[3.1 Функциональные требования](https://github.com/Karabas18/TRITPO_2/blob/main/README.md#31-функциональные-требования) 
[3.1.1 Основные функции](https://github.com/Karabas18/TRITPO_2/blob/main/README.md#311-основные-функции) 
[3.1.1.1 Вход пользователя в приложение](https://github.com/Karabas18/TRITPO_2/blob/main/README.md#3111-вход-пользователя-в-приложение) 
[3.1.1.2 Настройка профиля пользователя](https://github.com/Karabas18/TRITPO_2/blob/main/README.md#3112-настройка-профиля-пользователя) 
[3.1.1.3 Игровой процесс (поле)](https://github.com/Karabas18/TRITPO_2/blob/main/README.md#3113-игровой-процесс-поле) 
[3.1.1.4 Игровой процесс (игроки)](https://github.com/Karabas18/TRITPO_2/blob/main/README.md#3114-игровой-процесс-игроки) 
[3.1.1.5 Финал игры](https://github.com/Karabas18/TRITPO_2/blob/main/README.md#3115-финал-игры) 
[3.2 Нефункциональные требования](https://github.com/Karabas18/TRITPO_2/blob/main/README.md#32-нефункциональные-требования)  
[3.2.1 Атрибуты качества](https://github.com/Karabas18/TRITPO_2/blob/main/README.md#321-атрибуты-качества)  
[3.2.2 Требования к безопасности](https://github.com/Karabas18/TRITPO_2/blob/main/README.md#322-требования-к-безопасности)  
[3.2.3 Ограничения](https://github.com/Karabas18/TRITPO_2/blob/main/README.md#323-ограничения)
## 1.1 Название продукта
Explosive kittens
## 1.2 Назначение документа
В этом документе описаны функциональные и нефункциональные требования к веб-сайту «Explosive kittens» для ОС Windows 10. Этот документ предназначен для команды, которая будет реализовывать и проверять корректность работы веб-сервиса.
## 1.3 Бизнес требования
## 1.3.1 Исходные данные
Взрывные котята - карточная игра, создателями которой являются главный дизайнер Xbox Илан Ли, создатель комикса The Oatmeal Мэттью Инман и художник MARVEL и Xbox Шейн Смолл.([Правила](https://hobbyworld.ru/download/rules/Exploding%20Kittens_Rules.pdf)) Она представляет собой высоко стратегическую версию русской рулетки, наполненную котятами вместо патронов. Однако, не всегда у людей есть возможность собраться компанией для игры, поэтому игры стали все чаще переносить на новые платформы. Данная игра исключением не стала.
## 1.3.2 Возможности бизнеса
Исходя из предпочтений любителей настольных игр, у них есть желание иметь данную игру на других платформах и ресурсах, в том числе в виде веб-сайта. Интерфейс спроектирован так, чтобы весь функционал оригинальной игры был доступен пользователю. Игра может автоматически подбирать вам игроков или вы сами сможете добавлять их. 
## 1.3.3 Границы проекта
Веб-сайт позволяет всем пользователям играть в данную игру, поэтому регистрация не требуется. Также у пользователей есть возможность либо играть с незнакомцами, либо играть с друзьями, которых можно добавить к себе в список. Также есть функция изменения вашего аватара. Если же вы не знаете как играть, то вы всегда можете ознакомится с правилами, которые доступны в главном меню.
## 1.4 Аналоги
Монополия - экономическая и стратегическая настольная игра для двух и более человек. Получила большую популярность в XX веке во многих странах мира, включая СССР; в последнем была также известна под названиями «Менеджер», «Империя», «Бизнесмен». Цель игры — рационально используя стартовый капитал остаться единственным игроком, который не достиг банкротства. Фактически «Монополия» представляет собой игровое поле, состоящее из квадратов, которые проходят по кругу все игроки по очереди. Квадраты разделяются на активы (предприятие, ценная вещь) и события. Когда игроку выпадает очередь ходить, то броском кубика он определяет, какое количество шагов он должен совершить на игровом поле за этот ход (каждый шаг соответствует одному очку на кубике и одному квадрату на игровом поле).
Шахматы -  настольная логическая игра с шахматными фигурами на 64-клеточной доске, сочетающая в себе элементы искусства (в том числе в части шахматной композиции), науки и спорта. В шахматы обычно играют два игрока (именуемые шахматистами) друг против друга. Также возможна игра одной группы шахматистов против другой или против одного игрока, такие партии зачастую именуются консультационными. Кроме того, существует практика сеансов одновременной игры, когда против одного сильного игрока играет несколько противников, каждый на отдельной доске. Правила игры в основном сложились к XV веку; в современных официальных турнирах применяются правила Международной шахматной федерации, которыми регламентируются не только передвижение фигур, но и права судьи, правила поведения игроков и контроль времени. Игра, осуществляемая дистанционно, например по переписке, по телефону или через Интернет, имеет особые правила. 
## 1.4.1 Отличие от аналогов
Главное отличие - это красочный интерфейс, а также качественная система общения.
## 2 Требования пользователя  
## 2.1 Программные интерфейсы 
Все данные будут храниться в базе данных mysql. Приложение должно быть написано на языке программирования Java. 
## 2.2 Интерфейс пользователя  
## Окно пользователя  
Главное меню "Взрывные котята".  
![](https://github.com/Karabas18/TRITPO_2/blob/main/Cat_1.png)  
Окно ожидания.  
![](https://github.com/Karabas18/TRITPO_2/blob/main/Cat_2.png) 
Игровое окно
![](https://github.com/Karabas18/TRITPO_2/blob/main/Cat_3.png) 
Финальное окно
![](https://github.com/Karabas18/TRITPO_2/blob/main/Cat_4.png) 
## 2.3 Характеристики пользователей  
## 2.3.1 Аудитория приложения
Целевая аудитория - люди младшей и средней возрастной группы, увлекающиеся настольными играми. Побочная аудитория - люди старшей аудитории,  увлекающиеся настольными играми.
## 2.4 Предположения и зависимости 
1. Требуется хранить информацию о пользователях. 2.На сайте ожидается большое количество пользователей. 3. Веб-сайт должен иметь возможность обрабатывать значительное количество запросов в секунду.
## 3 Системные требования  
## 3.1 Функциональные требования 
## 3.1.1 Основные функции
## 3.1.1.1 Вход пользователя в приложение
| Функция | Требования | 
|:---|:---|
| Игра с друзьями | Приложение должно предоставить пользователю возможность играть с друзьями из списка друзей пользователя |
| Игра с незнакомцами | Приложение должно предоставить пользователю возможность играть с другими игроками |
| Правила | Приложение должно предоставить пользователю правила игры |
## 3.1.1.2 Настройка профиля пользователя
| Функция | Требования | 
|:---|:---|
| Редактирование аватара | Приложение должно предоставить пользователю возможность выбирать себе аватар из числа доступных аватаров в списке |
| Изменение имени | Приложение должно предоставить пользователю возможность менять свое имя в любой момент |
| Пользователь с таким именем существует | Приложение должно известить пользователя об ошибке изменения и запросить ввод псевдонима. Пользователь должен либо ввести псевдоним, либо отменить действие |
## 3.1.1.3 Игровой процесс (поле)
**Описание.** 1. Пользователь видит количество карт в колоде и шанс вытянуть "взрывного котенка".

**Требование.** Приложение должно предоставить пользователю видеть текущее количество карт в колоде и процентный шанс вытянуть карту "взрывного котенка".
## 3.1.1.4 Игровой процесс (игроки)
**Описание.** 1. Пользователь видит количество карт на руках у своих оппонентов.

**Требование.** Приложение должно предоставить пользователю видеть текущее количество карт на руках у оппонентов.

**Описание.** 2. Пользователь видит свои карты в руке, а также имеет возможность разыгрывать карты в соответствии с правилами игры.

**Требование.** Приложение должно предоставить пользователю видеть текущее количество карт у себя на руках, а также показывать, чей сейчас ход и какие карты можно разыгрывать.
## 3.1.1.5 Финал игры
**Описание.** 1. Пользователь видит результат партии.

**Требование.** Приложение должно предоставить пользователю видеть победителя партии с другими игроками, а также показывать статистику с наиболее частыми действиями.
## 3.2 Нефункциональные требования  
## 3.2.1 Атрибуты качества
1. Все функциональные элементы пользовательского интерфейса имеют названия, описывающие действие, которое произойдет при выборе элемента; 2. Пошаговая инструкция использования основных функций приложения отображена в справке; 3. Понятный графический интерфейс.
## 3.2.2 Требования к безопасности  
Информация о пользователях хранится в базе данных. Личные данные должны кодироваться, чтобы при краже злоумышленники не могли пользоваться ими.  
## 3.2.3 Ограничения    
Язык программирования Java, дизайн должен соответствовать пункту интерфейс пользователя. Веб-приложение не работает при отсутствии подключения к Интернету.
