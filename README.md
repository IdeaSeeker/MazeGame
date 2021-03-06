# MazeGame
  Небольшая игра-визуализатор создания и прохождения лабиринта различными алгоритмами на графах

# Что мы умеем
  <li> Рисовать случайные лабиринты, используя разные вариатны генерации 
      (<a href = "https://ru.wikipedia.org/wiki/Поиск_в_глубину">DFS</a>,
       <a href = "https://ru.wikipedia.org/wiki/Алгоритм_Прима">Prim</a>,
       <a href = "https://ru.wikipedia.org/wiki/Алгоритм_Краскала">Kruskal</a>)
  </li>
  <li> Проходить их, опять же, разными способами 
      (<a href = "https://ru.wikipedia.org/wiki/Поиск_в_глубину">DFS</a>,
       <a href = "https://ru.wikipedia.org/wiki/Поиск_в_ширину">BFS</a>,
       <a href = "https://ru.wikipedia.org/wiki/A*">A*</a>)
  </li>
  <li> Визуализировать каждый наш шаг из предыдущих двух пунктов </li>
  <li> Сохранять понравившиеся вам лабиринты в формате .png </li>

# Как этим пользоваться
  <li> Для работы программы на компьютере должен быть установлен <b> Python 3 </b> с библиотеками 
       <a href = "https://www.pygame.org/">pygame</a>, 
       <a href = "http://www.pythonware.com/products/pil/">PIL</a>
  </li>
  <li> Запуск игры происходит из файла <b> main.py </b> </li>
  <li> У каждого лабиринта есть оранжевая клеточка, добраться до которой сложнее всего (может совпадать с выходом) </li>
  <li> Управление персонажем клавишами WASD или стрелочками </li>
  <li> В режиме двух игроков стрелочки отвечают за перемещение первого игрока, клавиши WASD - второго </li>

  <br> В файле <b> settings.txt </b> можно поменять 
    <li> Высоту и ширину поля (единица измерения - клеточка)
    <li> Количество игроков (1/2)
    <li> Нужно ли показывать процесс создания или прохождения лабиринта (0/1 - нет/да соответственно)
    <li> Задержу между кадрами при отрисовке (в секундах)
  </br>
