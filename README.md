# ITDDP

# ТЕМА: Церковный православный портал

## Описание

Приложение с каталогом храмов и церквей, а так же церковными онлайн услугами: карта ближайших храмов и церквей, провославный календарь, поле для ввода суммы пожертвования, электронная запись на таинства крещения и венчания, а так же отпевание, заказать молебен или оформить подписку на молебны. 

## Функционал

- Авторизация
- Карта храмов и церквей
- Православный календарь
- Пожертвования
- Запись на крещение, венчание, отпевание
- Заказ молебена
- Оформление подписки на молебны

## Схема данных

1. Пользователь
    + ID
    + ФИО
    + контакты
    + bio

2. Церковь
    + ID
    + адрес
    + контакты
    + информация
    
3. Запись на требу
    + пользователь
    + церковь
    + треба
    + дата
    + сумма пожертвования
    + информация и комментарии 
    
4. Подписка на молебны
    + пользователь
    + церьковь
    + сумма пожертвования
    + повод
    + дата списания 