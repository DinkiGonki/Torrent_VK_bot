# Torrent_VK_bot
Сервис скачивания торрентов через браузер на основе vk_api

Как работает?
1. Написать группе https://vk.com/club182306529
2. Напишет, что создает папку. Она создается в папке users
3. Команда "загрузки" отобразит торренты через api
4. Постоянно требует отправить torrent - файл (отправьте ему этот файл для загрузки)
5. Этот файл скачается в torrent_user

Как настроить?
1. скачать qbittorrent
2. "Загрузки должны выглядеть так"  (копировать торрент файлы в torrent_user)

<p align="center">
  <img src="img/1.png"/>
</p>

3. Веб-интерфейс должен быть таким (в файле конфигурации config.py можно поменять настройки под свои пароль adminadmin)

<p align="center">
  <img src="img/2.png"/>
</p>

4. В файле конфига укажите полный путь до папки users в этом репозитории
5. Нужен пайтов и установленные зависимости
> Запускаем:

    $ pip install -r requirements.txt

6. Пишем команды боту
