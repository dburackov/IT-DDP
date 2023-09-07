# ITDDP

# ТЕМА: Церковный православный портал

## Описание

Приложение с каталогом храмов и церквей, а так же церковными онлайн услугами: карта ближайших храмов и церквей, провославный календарь, поле для ввода суммы пожертвования, электронная запись на таинства крещения и венчания, а так же отпевание, заказать молебен или оформить подписку на молебны. 

## Deploy Link

https://dburackov.github.io/IT-DDP/

## Функционал

- Авторизация
- Карта церквей
- Поиск церквей по названию
- Пожертвования 
- Заказ треб 
- подписка на требы
- оценки о отзывы
- личный кабинет:
    - список активных подписок 
    - актуальные требы 
    - история заказов

## Макет

![1](mockup/1.png)

![2](mockup/2.png)

![3](mockup/3.png)

![4](mockup/4.png)

![5](mockup/5.png)

![6](mockup/6.png)

## Схема данных

1. User
    + id
    + login
    + email

2. Church
    + id
    + name
    
3. Adress
    + id
    + church_id
    + city
    + street
    + unit

4. Contact
    + id
    + church_id
    + name
    + contact 

5. Schedule    
    + id
    + church_id
    + schedule

6. Review
    + id
    + user_id
    + church_id
    + content
    + date

7. Mark
    + id
    + review_id
    + value

8. treba
    + id
    + user_id
    + kind
    + purpose
