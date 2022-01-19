# simple-pygame-game

Перед запуском игры:

    pip install -r requirements.txt
    
Для запуска:
    python main.py

Мой проект, который я делал в школе в 2020 году.

Игра, в которой есть разные виды юнитов, которые обладают разным поведением и потребностями и пытаются выжить. Человек не может повлиять на игровой процесс после запуска игры и не имеет в игровом процессе никакую роль. Все параметры меняются до запуска игры в коде.

Суть игры в том, чтобы наблюдать за способностью юнитов к выживанию при изменении различных факторов, например, при изменении поведения юнитов (например, их отношения к другим юнитам) или их характеритик (например, здоровья, скорости или количества энергии, которое затрачивается на размножение). Изменяться может также окружающая среда, например можно увеличивать или уменьшать скорость роста травы.

Планировалось также добавить в игру предметы (для чего уже была подготовлена основа в виде абстрактного класса Item), добавить возможность создания предметов юнитами, но это так и не было реализовано. 

Одна из проблем, которую я в своё время не смог решить - добавление коллизии между сущностями (юнит - юнит, или юнит - предмет). Возможно, стоило искать не способ создания коллизии между сущностями, а лишь способ поиска обходного пути, чтобы эта коллизия даже не возникала. 
