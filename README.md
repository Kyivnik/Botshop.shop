# Обновление 4.0 (18.10.2021)
✅ Обновления:
1. Был полностью оптимизирован код, теперь если пользователь введёт что-то не так, бот не будет крашиться, а напишет

![image](https://user-images.githubusercontent.com/94528892/142433868-40037a8b-5315-430e-b0ef-6409b71933aa.png)

2. Инлайновые кнопки были полностью изменены, вместо текста, эмодзи.

![image](https://user-images.githubusercontent.com/94528892/142434248-5501e81b-8bdb-488d-8b80-ae9e67bdc82d.png)

3. Обновлён профиль пользователя

![image](https://user-images.githubusercontent.com/94528892/142441734-2ae0cd85-8e00-45cd-915f-8b4c4bc07524.png)

4. Добавлена команда для просмотра всех пользователей `/users` (Синяя ссылка это кликабельно)

![image](https://user-images.githubusercontent.com/94528892/142456863-6b5f112a-c3f6-4e7b-9a02-c650ebb04faa.png)

# Обновление 3.0 (17.10.2021)
✅ Обновления:
1. Добавлена команда для просмотра купленных товаров `/mybuy`
2. При покупке товара, если у пользователя уже куплен товар пишет

![image](https://user-images.githubusercontent.com/94528892/142281705-32ca0121-258c-471e-8f93-d2b94d97de10.png)

3. Добавлена команда для связи с тех.поддержкой `/teh`
4. Для администратора добавлена команда `/ot` для ответа пользователю (отправки сообщения пользователю)

# Обновление 2.0 (17.10.2021)

✅ Обновления:
1. Добавлена команда для удаления товаров `/rembuy`
2. Добавлена команда для изменения данных о товаре (Название, Цена, Ссылка) `/editbuy`
3. Код стал более оптимизированым

# ShopBot Telegram

🤖 Бот Магазин для Телеграмма на Python 🤖


✅ Функционал бота:
1. Уровни доступа (Пользователь, Администратор, Разработчик)
2. База данных SQLite3
3. Добавление товаров
4. Продажа товаров
5. Пополнение счёта при помощи QIWI (Библиотека SimpleQIWI)
6. Просмотр профилей других пользователей
7. Выдача средств, выдача уровней доступа.
8. Изменение данных о товаре
9. Удаление товаров
10. Список купленных товаров
11. Система тех.поддержки

🎄 В будущем:
1. Ссылка для оплаты при попоплнении счёта

Список будет дополняться и изменятся.

📄 Список библиотек которые нужно установить:

`pip install pyTelegramBotAPI`
`pip install SimpleQIWI`
`pip install requests`

👾 Список команд:

`/start` - Зарегистрироваться в боте

`/profile` - Профиль

`/donate` - Пополнить счёт

`/buy` - Купить товар

`/help` - Помощь по командам

`/mybuy` - Список купленных товаров

`/teh` - Связаться с тех.поддержкой

🚨 Админские команды: 

`/getprofile` - Посмотреть чужой профиль

`/getid` - Узнать ID пользователя

`/getcid` - Узнать Conference ID

`/access` - Выдать уровень доступа

`/giverub` - Выдать средства пользователю

`/addbuy` - Добавить товар

`/getrazrab` - Выдать себе разработчика (читать установку)

`/editbuy` - Изменить данные о товаре

`/rembuy` - Удалить товар

`/ot` - Ответить пользователю (отправить сообщение)


# 🛠 Установка бота:
1. Скачать файлы, затем распоковать папку в любое удобное место.
2. Открыть папку затем открыть файл `configure.py`
3. Найти бота  `@BotFather` в телеграмм затем написать `/newbot`
4. Ввести имя бота, ник бота затем вылезет токен

![image](https://user-images.githubusercontent.com/94528892/142181389-673cf369-2fe2-4c73-ae62-6e10ea822d38.png)

5. Копируем токен, затем открываем файл `configure.py`

![image](https://user-images.githubusercontent.com/94528892/142181704-064533e2-7af9-421e-b08e-82be42200835.png)

У вас будет пустой файл в строку `'name'` нужно вписать имя бота пример: 

![image](https://user-images.githubusercontent.com/94528892/142181871-63a7cd9c-7428-44d3-b2d8-63b7952a10b2.png)

В строку `'token'` нужно вписать токен который мы получили ранее:

![image](https://user-images.githubusercontent.com/94528892/142182021-cd38d9e2-97ab-4eb6-a61e-41df4975f5a2.png)

Далее переходим на сайт `qiwi.com/api`
Затем нажимаем на кнопку Выпустить новый токен

![image](https://user-images.githubusercontent.com/94528892/142182251-166e666b-55c8-419c-b6ac-8b66d014f7c4.png)

Выбираем все галочки, нажимаем на кнопку выбрать всё, затем нажимаем продолжить

![image](https://user-images.githubusercontent.com/94528892/142182421-919cf712-94f9-4a31-8c86-e4b22465799d.png)

Далее копируем токен и вставляем его в строку `'tokenqiwi'`

![image](https://user-images.githubusercontent.com/94528892/142182632-4aba3460-54d9-45c0-a904-38ea00978d90.png)

Далее в строку `'phoneqiwi'` вставляем свой номер телефона от QIWI кошелька

![image](https://user-images.githubusercontent.com/94528892/142182904-01d53418-6e1a-4252-b288-f75dd17b5e55.png)

Обязательно с + и кодом страны

Отлично! Всё почти готово.

Переходим по ссылке которая в сообщении с токеном бота

![image](https://user-images.githubusercontent.com/94528892/142183064-5031e215-cc3d-4d41-8685-e92f4d3c87f2.png)

Запускаем бота открывая файл `start.bat`

Далее нажимаем кнопку `Начать` либо `/start`

![image](https://user-images.githubusercontent.com/94528892/142184773-1c887e02-b542-40e1-ac62-fbcf3d567ea9.png)

Изменить этот текст Вы сможете тут

![image](https://user-images.githubusercontent.com/94528892/142184832-fd03b4b4-84f6-497c-99bb-2eafcc0bdf42.png)

Весь исходный код находиться в файле `bot.py`

Открываем файл `bot.py` затем ищем строку

![image](https://user-images.githubusercontent.com/94528892/142184961-c7d2d0be-7815-4d35-bda2-351032b32e77.png)

В чате с ботом пишем `/profile`

![image](https://user-images.githubusercontent.com/94528892/142185194-f71a4acd-f48d-470f-aaaa-66c666a755b1.png)

Копируем ваш ID затем вставялем в строку `WHERE id = 596060542` и `if message.from_user.id == 596060542:` ваш ID

![image](https://user-images.githubusercontent.com/94528892/142185458-d0a034b3-0302-45d4-ba7d-11fe138025be.png)

Затем сохраняем и перезапускаем бота.
В чат с ботом пишем `/getrazrab` и всё! Вы получили админку разработчика

![image](https://user-images.githubusercontent.com/94528892/142185660-f9b67c5b-d8c7-4a21-97d9-ff4a95471398.png)

![image](https://user-images.githubusercontent.com/94528892/142185690-eff4296c-ede4-4322-837d-7d9827655d68.png)

Далее находим строку 223 'def donateyesoplacheno'

![image](https://user-images.githubusercontent.com/94528892/142187463-7a46f327-857c-42a5-abf3-8017f774af5d.png)

И вместо `596060542` вписываем свой ID

Всё, бот полностью настроен!
Советую поставить бота на хостинг по типу:

`eu.pythonanywhere.com`

Либо на ВДС или на Выделенный сервер

Бот делал лично Я с нуля, один. Просьба если будете его пересливать, дорабатывать и сливать то указывайте автора исходного кода. ❤

# 📞 Связь со мной:

1. ВК: https://vk.com/nosemka
2. Дискорд: semmy#0068
# Kyivnik.shop
# Kyivnik.shop
# Kyivnik.shop
