Многопользовательская игра «Paper.io» создана для игры в нее двух
игроков с разных компьютеров. Цель этой игры – захватить всю территорию, сделать это можно двумя способами, в зависимости от стратегии,
избранной игроком.
– заполучив все свободные клетки
– убив своего соперника
Программа имеет графический интерфейс, который однозначно отображает игровую ситуацию у обоих игроков.

Руководство пользователя.


Игрок заходит на сервер, запускается графический интерфейс, когда
игрок будет готов начать игру, он нажмет кнопку «Играть». После этого
необходимо дождаться готовности другого игрока. Как только оба игрока
будут готовы, игра будет запущена со стартовых позиций.
– Параметры игрового поля:
Поле имеет размеры 20х20 клеток, игрок (1х1) перемещается по ним при
помощи клавиш (4 направления). Стартовые позиции игроков располагаются в диагонально противоположных углах игрового поля. 
Стартовая территория каждого игрока представляет собой квадрат (2х2) оттенка, соответствующего цвету самого игрока. 
При запуске игры, каждый игрок автоматически начнёт движение по горизонтали, в направлении к сопернику.


Архитектура программы.

Программа состоит из основных частей: TCP-server – сервер, на который будут отсылаться изменения, созданные игроками.
Game – основная логика игры, которая принимает команды от игроков, отправляет изменения на сервер и принимает их, а 
так же отправляет их на отрисовку в графический интерфейс.
