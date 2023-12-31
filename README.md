Сссылка на сайт: https://vladmir26.github.io/Technical-task/

Техническое задание для вакансии «Frontend-разработчика» 
в студию разработки кода «Космоскрипт»

Проект: Верстка сайта
Сроки выполнения: 1 неделя с момента получения данного технического задания.

Этап 1: Верстка макета из Figma
1.1. Задача:
•	Сверстать макет веб-страницы (2 блока: заголовок и описание игры. Слой CosmoScript), предоставленный в Figma.
•	Ссылка на макет: https://www.figma.com/file/kbM13nPXTZTSbCbxugQbvh/CosmoScript?type=design&node-id=15-139&mode=dev
1.2. Требования:
•	Верстка должна соответствовать дизайну и шрифтам из макета.
•	Интегрировать изображения и иконки согласно макету.
•	Обеспечить интерактивность элементов, указанных в макете.
•	Добавить минимальное количество анимации

Этап 2: Адаптация макета под мобильные устройства и планшеты
2.1. Задача:
•	Адаптировать верстку под различные устройства, включая мобильные устройства и планшеты.
2.2. Требования:
•	Проверить и улучшить адаптивность макета для разных разрешений экрана.
•	Убедиться, что вся информация и элементы макета отображаются корректно и читаемо на мобильных устройствах и планшетах.

Этап 3: Дополнение блока "Тарифы"
3.1. Задача:
•	Дополнить макет блоком "Тарифы" с информацией о доступных тарифных планах. (в  Figma этого блока нет, надо разработать самостоятельно)
3.2. Требования:
•	Создать блок "Тарифы" в соответствии с общим дизайном и стилистикой макета.
•	Заполнить блок информацией о доступных тарифных планах, их стоимости и характеристиках.
•	Обеспечить возможность выбора тарифа пользователем.
•	Учесть адаптацию блока "Тарифы" для разных устройств, если необходимо.

Этап 4: Интеграция данных с API
4.1. Задача:
•	Получить данные с внешнего API и отобразить их на странице.
4.2. Требования:
•	С помощью POST запросов получить данные по тарифам с указанных endpoint'ов:
o	https://munchkin.cosmoscript.ru/api/get_tariff - получение списка тарифов (название, описание, цена).
o	https://munchkin.cosmoscript.ru/api/get_cost – передача количества человек, получение стоимости тарифа.
•	Отправка и получение данных должны происходить без обновления страницы.
•	Визуализировать данные на странице в соответствии с общей стилистикой.

Общие требования:
•	Использовать современные стандарты и технологии во всех этапах разработки.
•	Обеспечить кросс-браузерную совместимость и оптимизацию для быстрой загрузки страницы.
•	Предоставить инструкции по развертыванию проекта (если требуется).

Дополнительная информация:
•	Блок 4 выполняется в случае понимания методик взаимодействия с API. Данные выводятся в блок "Тарифы".
•	Для успешного выполнения этапа 3, разработайте блок "Тарифы" в общей стилистике сайта, продумайте оформление блоков и обеспечьте удобство использования.

Примеры API
 Пример запроса	Пример ответа
api/get_tariff/	[
    {
        "name": "TestTariff",
        "description": "Тариф для теста",
        "price": 1000
    },
    {
        "name": "TestTariff2",
        "description": "Тариф для теста 2",
        "price": 2000
    },
    {
        "name": "TestTariff3",
        "description": "Тариф для теста 3",
        "price": 3
    }
]

api/get_cost/10/
	{
    "total_cost": 27.69
}

