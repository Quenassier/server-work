# Отчет по работе для допуска Новичков Климентий


## Установка buntu через PowerShell

Первым делом устсновил Ubuntu через PowerShell. Все запускаю от имени администратора. Установка Ubuntu через WSL проще и более интегрирована с Windows, особенно для разработки.

Установка прошла нормально.

![Проблема с установкой](https://github.com/DenisShestakov1/en_to_rus/blob/main/%D0%A1%D0%BD%D0%B8%D0%BC%D0%BE%D0%BA%20%D1%8D%D0%BA%D1%80%D0%B0%D0%BD%D0%B0%202024-06-04%20192203.png?raw=true)





### Установка компонентов

Далее установил нужные компоненты, и все прошло отлично. Продолжаю работу. После почти каждой команды перезагружаю ПК.

![Включение SVM Mode](https://github.com/DenisShestakov1/en_to_rus/blob/main/%D0%A1%D0%BD%D0%B8%D0%BC%D0%BE%D0%BA%20%D1%8D%D0%BA%D1%80%D0%B0%D0%BD%D0%B0%202024-06-04%20192909.png?raw=true)

### Регистрация и установка дистрибутива

Зарегистрировался и чекаю список доступных дистрибутивов. Качаю 22.04.

![Список доступных дистрибутивов](https://github.com/DenisShestakov1/en_to_rus/blob/main/%D0%A1%D0%BD%D0%B8%D0%BC%D0%BE%D0%BA%20%D1%8D%D0%BA%D1%80%D0%B0%D0%BD%D0%B0%202024-06-04%20192923.png?raw=true)

Устанавливаю JDK-17.

![Установка JDK-17](https://github.com/DenisShestakov1/en_to_rus/blob/main/%D0%A1%D0%BD%D0%B8%D0%BC%D0%BE%D0%BA%20%D1%8D%D0%BA%D1%80%D0%B0%D0%BD%D0%B0%202024-06-04%20192928.png?raw=true)

## Переход в Visual Studio Code

Далее перехожу в VS Code по данной ТЗшке. Запустил VS Code. Мне нужно установить 3 компонента: JDK, Maven и PostgreSQL. Все это я буду делать в VS Code.

![Запуск VS Code](https://github.com/DenisShestakov1/en_to_rus/blob/main/%D0%A1%D0%BD%D0%B8%D0%BC%D0%BE%D0%BA%20%D1%8D%D0%BA%D1%80%D0%B0%D0%BD%D0%B0%202024-06-04%20192934.png?raw=true)

### Установка компонентов через WSL

Запустил обновление пакетов. Все нормально. Устанавливаю JDK 17.

![Установка JDK 17](https://github.com/DenisShestakov1/en_to_rus/blob/main/%D0%A1%D0%BD%D0%B8%D0%BC%D0%BE%D0%BA%20%D1%8D%D0%BA%D1%80%D0%B0%D0%BD%D0%B0%202024-06-04%20192939.png?raw=true)
![Установка Maven](https://github.com/DenisShestakov1/en_to_rus/blob/main/%D0%A1%D0%BD%D0%B8%D0%BC%D0%BE%D0%BA%20%D1%8D%D0%BA%D1%80%D0%B0%D0%BD%D0%B0%202024-06-04%20192944.png?raw=true)
Устанавливаю JDK-17.

![Установка JDK-17](https://github.com/DenisShestakov1/en_to_rus/blob/main/%D0%A1%D0%BD%D0%B8%D0%BC%D0%BE%D0%BA%20%D1%8D%D0%BA%D1%80%D0%B0%D0%BD%D0%B0%202024-06-04%20192928.png?raw=true)

Установка JDK прошла успешно. Далее устанавливаю Maven.

![Установка Maven](https://github.com/DenisShestakov1/en_to_rus/blob/main/%D0%A1%D0%BD%D0%B8%D0%BC%D0%BE%D0%BA%20%D1%8D%D0%BA%D1%80%D0%B0%D0%BD%D0%B0%202024-06-04%20192950.png?raw=true)

Maven установлен. Далее идет PostgreSQL. Установка прошла успешно.

![Установка PostgreSQL](https://github.com/DenisShestakov1/en_to_rus/blob/main/%D0%A1%D0%BD%D0%B8%D0%BC%D0%BE%D0%BA%20%D1%8D%D0%BA%D1%80%D0%B0%D0%BD%D0%B0%202024-06-04%20192955.png?raw=true)

### Настройка PostgreSQL

Далее нужно установить пароль для PostgreSQL. Задаю пароль 1234 с помощью команды:

```sql
ALTER USER postgres PASSWORD '1234';
```
![ewfww](https://github.com/DenisShestakov1/en_to_rus/blob/main/%D0%A1%D0%BD%D0%B8%D0%BC%D0%BE%D0%BA%20%D1%8D%D0%BA%D1%80%D0%B0%D0%BD%D0%B0%202024-06-04%20193002.png?raw=true)

Пишу psql для входа в консоль PostgreSQL
Задаю пароль 1234 и он сейвится
![ew](https://github.com/DenisShestakov1/en_to_rus/blob/main/%D0%A1%D0%BD%D0%B8%D0%BC%D0%BE%D0%BA%20%D1%8D%D0%BA%D1%80%D0%B0%D0%BD%D0%B0%202024-06-04%20193009.png?raw=true)
Я неправильно создал базу данных. Переделываю
![ewfww](https://github.com/DenisShestakov1/en_to_rus/blob/main/%D0%A1%D0%BD%D0%B8%D0%BC%D0%BE%D0%BA%20%D1%8D%D0%BA%D1%80%D0%B0%D0%BD%D0%B0%202024-06-04%20193015.png?raw=true)
база данных создана
![ewfww](https://github.com/DenisShestakov1/en_to_rus/blob/main/%D0%A1%D0%BD%D0%B8%D0%BC%D0%BE%D0%BA%20%D1%8D%D0%BA%D1%80%D0%B0%D0%BD%D0%B0%202024-06-04%20193019.png?raw=true)
Подключился 
![ewfww](https://github.com/DenisShestakov1/en_to_rus/blob/main/%D0%A1%D0%BD%D0%B8%D0%BC%D0%BE%D0%BA%20%D1%8D%D0%BA%D1%80%D0%B0%D0%BD%D0%B0%202024-06-04%20193024.png?raw=true)
Я создал таблицу юзеров. След таблица профиль
![ewfww](https://github.com/DenisShestakov1/en_to_rus/blob/main/%D0%A1%D0%BD%D0%B8%D0%BC%D0%BE%D0%BA%20%D1%8D%D0%BA%D1%80%D0%B0%D0%BD%D0%B0%202024-06-04%20193033.png?raw=true)
Профиль создал.
Все таблицы созданы
![ewfww](https://github.com/DenisShestakov1/en_to_rus/blob/main/%D0%A1%D0%BD%D0%B8%D0%BC%D0%BE%D0%BA%20%D1%8D%D0%BA%D1%80%D0%B0%D0%BD%D0%B0%202024-06-04%20193039.png?raw=true)
Заполнил таблицу пользователи
![ewfww](https://github.com/DenisShestakov1/en_to_rus/blob/main/%D0%A1%D0%BD%D0%B8%D0%BC%D0%BE%D0%BA%20%D1%8D%D0%BA%D1%80%D0%B0%D0%BD%D0%B0%202024-06-04%20193044.png?raw=true)
Заполнил таблицу профили
![ewfww](https://github.com/DenisShestakov1/en_to_rus/blob/main/%D0%A1%D0%BD%D0%B8%D0%BC%D0%BE%D0%BA%20%D1%8D%D0%BA%D1%80%D0%B0%D0%BD%D0%B0%202024-06-04%20193049.png?raw=true)
Почекал селект фромами и все нормально. Иду далее
След шагом по тз устанавливаю джаву и мейвен от майкрософт
![ewfww](https://github.com/DenisShestakov1/en_to_rus/blob/main/%D0%A1%D0%BD%D0%B8%D0%BC%D0%BE%D0%BA%20%D1%8D%D0%BA%D1%80%D0%B0%D0%BD%D0%B0%202024-06-04%20193101.png?raw=true)
Все нормально качаю мейвен
![ewfww](https://github.com/DenisShestakov1/en_to_rus/blob/main/%D0%A1%D0%BD%D0%B8%D0%BC%D0%BE%D0%BA%20%D1%8D%D0%BA%D1%80%D0%B0%D0%BD%D0%B0%202024-06-04%20193122.png?raw=true)
![ewfww](https://github.com/DenisShestakov1/en_to_rus/blob/main/%D0%A1%D0%BD%D0%B8%D0%BC%D0%BE%D0%BA%20%D1%8D%D0%BA%D1%80%D0%B0%D0%BD%D0%B0%202024-06-04%20193128.png?raw=true)
доступ есть
Заранил спринг бут командой mvn spring-boot:run
![ewfww](https://github.com/DenisShestakov1/en_to_rus/blob/main/%D0%A1%D0%BD%D0%B8%D0%BC%D0%BE%D0%BA%20%D1%8D%D0%BA%D1%80%D0%B0%D0%BD%D0%B0%202024-06-04%20193228.png?raw=true)
Качаю спринг бут
![ewfww](https://github.com/DenisShestakov1/en_to_rus/blob/main/%D0%A1%D0%BD%D0%B8%D0%BC%D0%BE%D0%BA%20%D1%8D%D0%BA%D1%80%D0%B0%D0%BD%D0%B0%202024-06-04%20193234.png?raw=true)
 Решил скачать PostgreSQL Extension 
![ewfww](https://github.com/DenisShestakov1/en_to_rus/blob/main/%D0%A1%D0%BD%D0%B8%D0%BC%D0%BE%D0%BA%20%D1%8D%D0%BA%D1%80%D0%B0%D0%BD%D0%B0%202024-06-04%20193239.png?raw=true)
Проверка порта
![ewfww](https://github.com/DenisShestakov1/en_to_rus/blob/main/%D0%A1%D0%BD%D0%B8%D0%BC%D0%BE%D0%BA%20%D1%8D%D0%BA%D1%80%D0%B0%D0%BD%D0%B0%202024-06-04%20193247.png?raw=true)
Порт верный

Джава установлена, мейвен установлен, PostgreSQL установлен и работает. Порт верный. Пароль 1234. База данных есть вообщем все есть.
Начинаю инициализацию и запуск проекта на Spring Boot
Нажал cntr + shift + p и вбил спринг инитиализр
![ewfww](https://github.com/DenisShestakov1/en_to_rus/blob/main/%D0%A1%D0%BD%D0%B8%D0%BC%D0%BE%D0%BA%20%D1%8D%D0%BA%D1%80%D0%B0%D0%BD%D0%B0%202024-06-04%20193258.png?raw=true)
 Идет открытие проекта
 ![ewfww](https://github.com/DenisShestakov1/en_to_rus/blob/main/%D0%A1%D0%BD%D0%B8%D0%BC%D0%BE%D0%BA%20%D1%8D%D0%BA%D1%80%D0%B0%D0%BD%D0%B0%202024-06-04%20193447.png?raw=true)
  У меня открылось окно c проектом
Далее по плану настройка demo (приложения)
![ewfww](https://github.com/DenisShestakov1/en_to_rus/blob/main/%D0%A1%D0%BD%D0%B8%D0%BC%D0%BE%D0%BA%20%D1%8D%D0%BA%D1%80%D0%B0%D0%BD%D0%B0%202024-06-04%20193452.png?raw=true)
![ewfww](https://github.com/DenisShestakov1/en_to_rus/blob/main/%D0%A1%D0%BD%D0%B8%D0%BC%D0%BE%D0%BA%20%D1%8D%D0%BA%D1%80%D0%B0%D0%BD%D0%B0%202024-06-04%20193457.png?raw=true)
Качаю эту либу тк само приложение перенаправило меня для ее скачки
![ewfww](https://github.com/DenisShestakov1/en_to_rus/blob/main/%D0%A1%D0%BD%D0%B8%D0%BC%D0%BE%D0%BA%20%D1%8D%D0%BA%D1%80%D0%B0%D0%BD%D0%B0%202024-06-04%20193506.png?raw=true)
запускаю проект через maven 
![ewfww](https://github.com/DenisShestakov1/en_to_rus/blob/main/%D0%A1%D0%BD%D0%B8%D0%BC%D0%BE%D0%BA%20%D1%8D%D0%BA%D1%80%D0%B0%D0%BD%D0%B0%202024-06-04%20193515.png?raw=true)
![ewfww](https://github.com/DenisShestakov1/en_to_rus/blob/main/%D0%A1%D0%BD%D0%B8%D0%BC%D0%BE%D0%BA%20%D1%8D%D0%BA%D1%80%D0%B0%D0%BD%D0%B0%202024-06-04%20193524.png?raw=true)
![wwe](https://github.com/DenisShestakov1/en_to_rus/blob/main/%D0%A1%D0%BD%D0%B8%D0%BC%D0%BE%D0%BA%20%D1%8D%D0%BA%D1%80%D0%B0%D0%BD%D0%B0%202024-06-04%20193532.png?raw=true)
Мои логи показывают что приложение Spring Boot заробило
в конце сообщение Started DemoApplication с указанием времени, за которое приложение запустилось. Это значит что все прошло успешно. 

создал запросы 
далее через cntr + shift + p пишу PostgreSQL connect database и идет настройка Имя хоста localhost
![ewfww](https://github.com/DenisShestakov1/en_to_rus/blob/main/%D0%A1%D0%BD%D0%B8%D0%BC%D0%BE%D0%BA%20%D1%8D%D0%BA%D1%80%D0%B0%D0%BD%D0%B0%202024-06-04%20193550.png?raw=true)
Пароль 1234 для постгреса
![ewfww](https://github.com/DenisShestakov1/en_to_rus/blob/main/%D0%A1%D0%BD%D0%B8%D0%BC%D0%BE%D0%BA%20%D1%8D%D0%BA%D1%80%D0%B0%D0%BD%D0%B0%202024-06-04%20193631.png?raw=true)
Порт 5432
![ewfww](https://github.com/DenisShestakov1/en_to_rus/blob/main/%D0%A1%D0%BD%D0%B8%D0%BC%D0%BE%D0%BA%20%D1%8D%D0%BA%D1%80%D0%B0%D0%BD%D0%B0%202024-06-04%20193635.png?raw=true)
Даю имя для нового профиля подключения
![ewfww](https://github.com/DenisShestakov1/en_to_rus/blob/main/%D0%A1%D0%BD%D0%B8%D0%BC%D0%BE%D0%BA%20%D1%8D%D0%BA%D1%80%D0%B0%D0%BD%D0%B0%202024-06-04%20193640.png?raw=true)
Все подключилось 
![ewfww](https://github.com/DenisShestakov1/en_to_rus/blob/main/%D0%A1%D0%BD%D0%B8%D0%BC%D0%BE%D0%BA%20%D1%8D%D0%BA%D1%80%D0%B0%D0%BD%D0%B0%202024-06-04%20193648.png?raw=true)
Я провел проверку и таблицы вывелись
![ewfww](https://github.com/DenisShestakov1/en_to_rus/blob/main/%D0%A1%D0%BD%D0%B8%D0%BC%D0%BE%D0%BA%20%D1%8D%D0%BA%D1%80%D0%B0%D0%BD%D0%B0%202024-06-04%20193657.png?raw=true)
 
