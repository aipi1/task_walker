# Тестовое задание ml-agents #

Ссылка на используемый здесь репозиторий - https://github.com/Unity-Technologies/ml-agents

Путь *Project/Assets/ModelTraining* содержит: файл **environment.yml** для создания используемого окружения, конфиг обучения модели **Walker.yaml**, результаты обучения модели в папке *results*, а также итоговую модель **WalkerFinalModel.onnx**(Step: 3330000. Time Elapsed: 7887.630 s. Mean Reward: 318.950. Std of Reward: 329.859).

В самом тренажере Walker у первых пяти WalkerRagdoll(0-4) поставлена итоговая модель **WalkerFinalModel.onnx**, у остальных выставлена модель по умолчанию.(для сравнения работы моделей)

Результаты примерно двухчасового обучения приведены на скриншотах снизу:

![tensorboard plots](https://github.com/aipi1/task_walker/blob/main/Project/Assets/ModelTraining/results/1.png)

![tensorboard plots](https://github.com/aipi1/task_walker/blob/main/Project/Assets/ModelTraining/results/22.png)
