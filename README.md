В этой задаче используется полносвязная нейронная сеть из шести слоев: один Flatten и пять Dense. В первых четырёх слоях Dense используется активация selu, в последнем linear. В слоях Dense 512, 256, 256, 128 и 10 нейронов соответсвенно.

В цикле обучения используется оптимизатор Adam, функция потерь SparceCategoricalCrossentropy и метрика accuracy. Всего производится 18 эпох обучения.

Для получения графиков использовал Tensorboard.

Графики функции потерь

![Image alt](https://github.com/Timoshic228/Lab_1_tochkar/blob/master/loss.png)
![Image alt](https://github.com/Timoshic228/Lab_1_tochkar/blob/master/val_loss.png)


Графики метрики точности


![Image alt](https://github.com/Timoshic228/Lab_1_tochkar/blob/master/acc.png)
![Image alt](https://github.com/Timoshic228/Lab_1_tochkar/blob/master/val_acc.png)

Итоговая точность на тестовых данных 0.4779
