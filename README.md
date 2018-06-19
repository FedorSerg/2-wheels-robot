# 2-wheels-robot

Robot with 2 whells and 1 helpfull wheel-like part added to make it stand + rqt camera.

Для запуска робота в Gazebo необходимо в разных терминалах написать следующие команды:

  * **roslaunch mobot_gazebo mobot.launch** — для запуска Gazebo с моделью и настройками

  * **rosrun turtlesim turtle_teleop_key /turtle1/cmd_vel:=/mobot/cmd_vel** — для запуска утилиты, добавляющей возможность управлять роботом с клавиатуры клавишами стрелок. Для управления роботом терминал, в котором запущена эта команда, должен быть активным окном.

Также можно в дополнительном терминале ввести команду rqt, которая запустит работу камеры, находящейся в сцене
