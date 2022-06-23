# Установкаn:

###### Склонировать репозиторий:
```bash
$ git clone https://github.com/L4zzur/reversi-cli.git
```

###### Перейти в папку reversi-cli:
```bash
$ cd reversi-cli
```

###### Запустить основной файл игры с набором аргументов:
```bash
$ python main.py --color --random
```

Один из трёх аргументов (```human, random, test```) является обязательным.
В противном случае запускается запускается игра с аргументом ```human```.

Аргумент  | Значение
--------- | -------------------
--color   | Запуск в цветном режиме
--sleep   | Устанавливает таймаут ожидания после ходов, может быть вещественным (по умолчанию 1)
--human   | Игра против другого человека
--random  | Игра против бота-рандома
--test    | Игра двух ботов-рандомов