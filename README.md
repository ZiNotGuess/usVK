Автостатус и другое для ВКонтакте
=====================
***
### Что входит в этот скрипт:
* **Автостатус**
* **Автоонлайн**
* Автоматическое удаление **входящих** заявок в друзья
***
### Что тебе надо сделать, чтобы запустить этот скрипт?
* Получить `access_token`(если не знаешь, выбери на [этом](https://vkhost.github.io) сайте VK API)
* Зайти в `settings.ini` и вставить туда необходимые параметры(ты можешь изменять их во время работы скрипта)
* Запустить `main.py`
### Настройки `settings.ini`:
##### Настройки `[Script]`:
* **access_token**: access_token аккаунта ***(str)***
* **apiVersion**: версия API VK ***(str)***
* **status**: автостатус ***(boolean)***
* **eternalOnline**: вечный онлайн ***(boolean)***
* **deleteAllFriendsRequests**: автоматическое удаление входящих заявок в друзья ***(boolean)***
* **timeToSleep**: время, на которое остановливается скрипт ***(int)***
##### Настройки `[Status]`:
* **time**: текущее время в статус ***(boolean)***
* **photoProfile**: у страницы есть фотография профиля ***(boolean)***
* **photoLikeCount**: количество лайков фотографии профиля в статус ***(boolean)***
* **followersCount**: количество подписчиков в статус ***(boolean)***
* **unreadMessagesCount**: количество непрочитанных сообщений в статус ***(boolean)***
* **blackListMemberCount**: количество людей в ЧС в статус ***(boolean)***
* **giftsCount**: количество подарков в статус ***(boolean)***
* **decor**: красивые цифры вместо обычных в статусе ***(boolean)***

[Разработчик](https://vk.com/id470182086)(на вопросы не отвечает); [по вопросам](https://vk.me/club194412819)