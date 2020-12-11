# dstar73

Append contacts from dstar.su to DMR ID database and generate Retevis RT73/Kydera CDR-300UV databases (c) 2020, EU1ADI

Программа генерации .csv базы контактов для радиостанций Retevis RT73/Kydera CDR-300UV

В базу контактов https://database.radioid.net/static/user.csv добавятся контакты из dstar.su. Все данные скачиваются автоматически. На выходе получатся файлы users.csv groups.csv, которые можно закачать в радиостанцию при помощи CPS утилиты.

## Использование

- Запустите `userdb.exe`

- Импортируйте users.csv groups.csv

Внимание: заливка файла users.csv может занять очень много времени.

## Параметры запуска 

`userdb.exe -exclude 310,311,312`

Исключить контакты начинающиеся на перечисленные префиксы 310,311,312. Может быть полезно для уменьшения выходого файла.

`userdb.zip` скомпилировная версия для Win10 x64

## Поддержка

Вопросы можно задать в чате https://t.me/qsyby
