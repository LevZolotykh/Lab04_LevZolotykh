# Отчёт по лабораторной работе №4

В данной лабораторной работе необходимо было создать докер файл и запустить в нём приложение "aafire"(Рисунки 1, 2 и 3). Также была установлена утилита ping для проверки наличия связи между контейнерами.

Команда `ENTRYPOINT [ "aafire" ]` автоматически запускает приложение aafire при запуске контейнера
Команда `ENV TERM=xterm` устанавливает вывод в стандартный терминал

![Screen1](Screen1.png)
Рисунок 1

![Screen2](Screen2.png)
Рисунок 2

![Screen3](Screen3.png)
Рисунок 3

После была создана сеть, к которой были покдлючены оба контейнера (Рисунок 4):

![Screen4](Screen4.png)
Рисунок 4

На последних двух скринах представлены результаты проверки связи между файлами(Рисунки 5 и 6)

![Screen5](Screen5.png)
Рисунок 5

![Screen6](Screen6.png)
Рисунок 6