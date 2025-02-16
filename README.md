# "Тестирование мобильных приложений"
## shopping-list apk
Создаю чек-лист для тестирования основных функциональностей мобильного приложения shopping-list:
#### [Чек-лист мобильного приложения (XLSX)](https://docs.google.com/spreadsheets/d/1qJjcV8EDXkOrjy7fVTewQbMhhMDQHBct1yjL7d-6VxA/edit?usp=sharing)
Создаю 15 тест-кейсов функциональностей мобильного приложения shopping-list в QASE:
#### [Тест-кейсы мобильного приложения из QASE (PDF)](https://github.com/StanTokarev/mobile/blob/main/Stan%20Tokarev%20%D0%A2%D0%B5%D1%81%D1%82-%D0%BA%D0%B5%D0%B9%D1%81%D1%8B%20%D0%BC%D0%BE%D0%B1%D0%B8%D0%BB%D1%8C%D0%BD%D0%BE%D0%B3%D0%BE%20%D0%BF%D1%80%D0%B8%D0%BB%D0%BE%D0%B6%D0%B5%D0%BD%D0%B8%D1%8F%20%D0%B8%D0%B7%20QASE.pdf)
Тестовый прогон 15 тест-кейсов функциональностей мобильного приложения shopping-list в QASE:
#### [Тестовый прогон мобильного приложения из QASE (PDF)](https://github.com/StanTokarev/mobile/blob/main/Stan%20Tokarev%20%D0%A2%D0%B5%D1%81%D1%82%D0%BE%D0%B2%D1%8B%D0%B9%20%D0%BF%D1%80%D0%BE%D0%B3%D0%BE%D0%BD%20%D0%BC%D0%BE%D0%B1%D0%B8%D0%BB%D1%8C%D0%BD%D0%BE%D0%B3%D0%BE%20%D0%BF%D1%80%D0%B8%D0%BB%D0%BE%D0%B6%D0%B5%D0%BD%D0%B8%D1%8F%20%D0%B8%D0%B7%20QASE.pdf)
Провожу тестирование по чек-листу/тест-кейсам и создаю отчеты о дефекте в YouTrack:
#### [Отчеты о дефекте мобильного приложения из YouTrack (XLSX)](https://github.com/StanTokarev/mobile/blob/main/Stan%20Tokarev%20%D0%9E%D1%82%D1%87%D0%B5%D1%82%D1%8B%20%D0%BE%20%D0%B4%D0%B5%D1%84%D0%B5%D0%BA%D1%82%D0%B5%20%D0%BC%D0%BE%D0%B1%D0%B8%D0%BB%D1%8C%D0%BD%D0%BE%D0%B3%D0%BE%20%D0%BF%D1%80%D0%B8%D0%BB%D0%BE%D0%B6%D0%B5%D0%BD%D0%B8%D1%8F%20%D0%B8%D0%B7%20YouTrack%20-%202.xlsx)
По результатам тестирования мобильного приложения shopping-list создаю отчет Test Summary Report:
#### [Отчет по результатам тестирования Test Summary Report (PDF)](https://github.com/StanTokarev/mobile/blob/main/Stan%20Tokarev%20Test%20Summary%20Report.pdf)
Добавляю несколько разных товаров в корзину, потом отправляю запрос на удаление товара 1892, перехватываю запрос, меняю на удаление товара 1895, использую мобильную версию <a href="https://demoshopping.ru/">demoshopping.ru</a>:
#### [Charles Proxy, 1. Смартфон. Запрос на удаление товара 1892 меняю на удаление товара 1895 (MP4)](https://github.com/StanTokarev/mobile/blob/main/1.%20%D0%A1%D0%BC%D0%B0%D1%80%D1%82%D1%84%D0%BE%D0%BD.%20%D0%97%D0%B0%D0%BF%D1%80%D0%BE%D1%81%20%D0%BD%D0%B0%20%D1%83%D0%B4%D0%B0%D0%BB%D0%B5%D0%BD%D0%B8%D0%B5%20%D1%82%D0%BE%D0%B2%D0%B0%D1%80%D0%B0%201892%20%D0%BC%D0%B5%D0%BD%D1%8F%D1%8E%20%D0%BD%D0%B0%20%D1%83%D0%B4%D0%B0%D0%BB%D0%B5%D0%BD%D0%B8%D0%B5%20%D1%82%D0%BE%D0%B2%D0%B0%D1%80%D0%B0%201895.mp4)
При обращении к <a href="https://demoshopping.ru/">demoshopping.ru</a> пользователь увидит в браузере фото Stan Tokarev:
#### [Charles Proxy, 2. Смартфон. При обращении к demoshopping пользователь увидит в браузере картинку (MP4)](https://github.com/StanTokarev/mobile/blob/main/%202.%20%D0%A1%D0%BC%D0%B0%D1%80%D1%82%D1%84%D0%BE%D0%BD.%20%D0%9F%D1%80%D0%B8%20%D0%BE%D0%B1%D1%80%D0%B0%D1%89%D0%B5%D0%BD%D0%B8%D0%B8%20%D0%BA%20demoshopping%20%D0%BF%D0%BE%D0%BB%D1%8C%D0%B7%D0%BE%D0%B2%D0%B0%D1%82%D0%B5%D0%BB%D1%8C%20%D1%83%D0%B2%D0%B8%D0%B4%D0%B8%D1%82%20%D0%B2%20%D0%B1%D1%80%D0%B0%D1%83%D0%B7%D0%B5%D1%80%D0%B5%20%D0%BA%D0%B0%D1%80%D1%82%D0%B8%D0%BD%D0%BA%D1%83.mp4)
Видео перехваченного HTTPs-запроса с мобильного устройства. В header user-agent информация о мобильном устройстве:
#### [Charles Proxy, 3. Смартфон. HTTPs-запрос с моб устройства в header user-agent информация о моб устройстве, MP4](https://github.com/StanTokarev/mobile/blob/main/3.%20%D0%A1%D0%BC%D0%B0%D1%80%D1%82%D1%84%D0%BE%D0%BD.%20HTTPs-%D0%B7%D0%B0%D0%BF%D1%80%D0%BE%D1%81%20%D1%81%20%D0%BC%D0%BE%D0%B1%D0%B8%D0%BB%D1%8C%D0%BD%D0%BE%D0%B3%D0%BE%20%D1%83%D1%81%D1%82%D1%80%D0%BE%D0%B9%D1%81%D1%82%D0%B2%D0%B0%20%D0%B2%20header%20user-agent%20%D0%B8%D0%BD%D1%84%D0%BE%D1%80%D0%BC%D0%B0%D1%86%D0%B8%D1%8F%20%D0%BE%20%D0%BC%D0%BE%D0%B1%20%D1%83%D1%81%D1%82%D1%80%D0%BE%D0%B9%D1%81%D1%82%D0%B2%D0%B5.mp4)
Скриншот перехваченного HTTPs-запроса с мобильного устройства. В header user-agent информация о мобильном устройстве:
#### [Charles Proxy, 3. Смартфон. HTTPs-запрос с моб устройства в header user-agent информация о моб устройстве, PNG](https://github.com/StanTokarev/mobile/blob/main/3.%20%D0%A1%D0%BC%D0%B0%D1%80%D1%82%D1%84%D0%BE%D0%BD.%20HTTPs-%D0%B7%D0%B0%D0%BF%D1%80%D0%BE%D1%81%20%D1%81%20%D0%BC%D0%BE%D0%B1%D0%B8%D0%BB%D1%8C%D0%BD%D0%BE%D0%B3%D0%BE%20%D1%83%D1%81%D1%82%D1%80%D0%BE%D0%B9%D1%81%D1%82%D0%B2%D0%B0%20%D0%B2%20header%20user-agent%20%D0%B8%D0%BD%D1%84%D0%BE%D1%80%D0%BC%D0%B0%D1%86%D0%B8%D1%8F%20%D0%BE%20%D0%BC%D0%BE%D0%B1%20%D1%83%D1%81%D1%82%D1%80%D0%BE%D0%B9%D1%81%D1%82%D0%B2%D0%B5.png)
