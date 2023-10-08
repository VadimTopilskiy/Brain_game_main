
## Проект содержит пят математических мини-игр:

* **Even number** - Чётное / Нечётное.
* **Missing number** - Пропущнное число.
* **Calculation** - Посчитай-ка!.
* **GSD** - Найди наибольший общий делитель.
* **Prime Number** - Простое ли это число?


### Необходимые требования

[Python 3.8.1+](https://www.python.org/downloads/)

[Poetry](https://python-poetry.org/docs/)

### Установка
   

    git clone https://github.com/VadimTopilskiy/Brain_game_main.git

>>

    cd python-project-49/
    poetry build
    python -m pip install --user dist/*.whl

### Команды для вызова игр

    brain-even # Чётное / Нечётное
    brain-calc # Вычисления 
    brain-gcd # Нахождение наибольшего общего делителя
    brain-progression # Заполнение прогрессии
    brain-prime # Простое число или нет

### Правила игры
Для **успешного** прохождения любой из игр необходимо дать **три правильных** ответа.

В случае предоставления **неверного** ответа, игра **завершается**.