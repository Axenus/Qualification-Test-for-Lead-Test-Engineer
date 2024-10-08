# Квалификационный тест на Ведущего инженера по тестированию

Реализовать автоматизированное тестирование приложения исходя из следующих требований к его работе:
- ОС запуска приложения: Debian 12 и выше.
- Приложение работает с СУБД PostgreSQL 14 и выше.
- Запущенное приложение должно принимать соединения по протоколу TCP/IP на порт, указанный в настройках до его запуска.
- Приложение должно при получении бинарной кодограммы "Получить список активных пользователей":

## Установка

1. Клонируйте репозиторий:

   ```bash
   git clone git@github.com:Axenus/Qualification-Test-for-Lead-Test-Engineer.git
   ```

2. Перейдите в директорию проекта:

   ```bash
   cd Qualification-Test-for-Lead-Test-Engineer
   ```

3. Установите зависимости:

   ```bash
   pip install -r requirements.txt
   ```

## Использование

Инструкции по запуску проекта:

1. Авторизация в Debian:
   - Логин: `axenus`
   - Пароль: `123123`

2. Перейдите в корень проекта:

   ```
   cd ~/PycharmProjects/QAA
   ```

3. Откройте две командные строки и выполните следующие действия:
   - Войдите под root-пользователем:
     
     ```bash
     su root
     # Введите пароль: 123123
     ```
   - Активируйте виртуальное окружение для обеих консолей:

     ```bash
     python -m venv venv
     source venv/bin/activate  # Для Linux/Debian12
     ```

4. В первой консоли запустите `main.py` (это наш сервер, поэтому запускаем его первым):

   ```bash
   python main.py
   ```

5. Во второй консоли запустите `client.py`:

   ```bash
   python client.py
   ```

Запуск клиента можно повторять, и каждый раз клиент будет получать ожидаемый результат.

## Примечание

Я постараюсь приложить отдельно файл с базой данных и копию рабочей БД, чтобы вы всё могли воспроизвести. Однако я раньше так не делал, если будут проблемы — пишите.

## Контакты

Над задачей трудился: Васильченко Евгений Владимирович
- [Telegram](https://t.me/VasilchenkoEugene)
