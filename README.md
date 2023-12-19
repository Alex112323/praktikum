# **Игра лабиринт**
В качестве проекта для НИУ ВШЭ была создана игра Лабиринт
# **Правила игры**
*Играет один человек
*Нужно выбрать один из двух уровней сложности, который в процессе игры иожно поменять
*Есть возможность узнать решение из любой клетки лабиринта
*В любой момент игру можно завершить
# **Установка**
Необходимо установить репозиторий и соответствующие библиотеки.
*Установка репозитория через HTTPS: 
*Установка библиотек: pip install --upgrade -r requirements.txt
# **Запуск**
В командной строке необходимо ввести: python main.py
# **Особенности игры**
*Игроку нужно ввести один из уровней сложности(Medium или Hard), в соответствии с которым сгенерируется лабиринт
*Зеленым цветом выделен игрок
*Красным цветом выделена финальная точка, в которую нужно добраться
*Клавиши стрелок влево/вправо/наверх/вниз означают соответствующие перемещения игрока в соседние клетки
*Синим выделены стены, если на пути игрока есть стена, движение в эту сторону для него закрыто
*Если нажать enter, в случае правильного решения сгенерируется новый лабиринт, в противном случае сгенерируется решение
*Если нажать клавишу 1, сгенерируется новый лабиринт уровня "Medium"
*Если нажать клавишу 2, сгенерируется новый лабиринт уровня "Hard"
*Чтобы завершить игру, нужно нажать крестик в правом верхнем углу экрана

