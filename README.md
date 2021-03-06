# ShopOOPJava
Задания, для провеки уровня понимания ООП, на тематику приложения агрегатора товаров в магазинах

Шаблон для этого задания на kotlin https://github.com/JunoHunt/JunoShopOOPTaskKotlin

---
Ход выполнения:
1. Создать свой репозиторий из этого шаблона
2. Реализовать поведение описанное в классе MainActivity
3. Закоммитить решение и запушить в свой репозиторий на своем аккаунте
4. Скинуть ссылку на репозиторий на почту hello@junohunt.ru

## Задача
### TaskOne
---
Будем считать, что в приложении будет всего 2 типа магазинов:
1. Обычный магазин (Напирмер М.Видео или NDS)
2. Интернет магазин (Например AliExpress и Юла)

С этими магазинами можно сделать общие действия:
1. Посмотреть спиок продуктов List<Sting>
2. Вернуть непонравившийся продук

Так же будет существовать база чеков, в которую все магазины будут записывать все свои действия и в ответ получать номера чеков

В обычных магазинах в отличие от интерент конкурентов можно:
1. Попробовать товар

Только в интренет магазинах можно:
1. Получить купон на скидку

Еще в приложении есть пользователи, они могут:
1. Делать покупки в магазинах
2. Возвращать товары
4. Попробовать товар в обчных магазинах
5. Получить купон на скидку в интернет магазинах
6. Получить запись из базы чеков, о действии в магазине, по номеру чека

В что бы выполнить любое действие пользователь должен представиться и в ответ он получит номер чека.

Любой магазин при выполнении любого действия записывает его в базу чеков в формате: "Покупатель $имя $действие в магазине $название и получил чек номер $номер_чека"

Вам необходимо:
1. Создать 1 обычный( DNS) и 1 интерент( AliExpress) магазины
2. Создать 1 пользователя Диму
3. Воссоздать последоватльность действий для Димы:
     а. Попробовать телефон Samsung Galaxy 10 в DNS
     б. Получить купон на скидку в AliExpress
     в. Купить телефон Samsung Galaxy 10 в AliExpress
     
Вывести все действия в act_mail_log в столбце

![task1](https://github.com/JunoHunt/JunoShopOOPTaskKotlin/blob/master/examples/OOPTask.jpg)
