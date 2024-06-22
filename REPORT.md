Для начала представим все замеры для девайса: NVIDIA GeForce RTX 4050 Laptop GPU
Замеры при перемножении матриц 2048x2048
| Tile | Time (Realization 2) | Time (Realization 3) |
| --- | --- | --- |
| 4 | 90.216384 | 242.083840 |
| 8 | 27.869184 | 49.976320 |
| 16 | 20.271104 | 13.777920 |
| 32 | 20.150272 | 7.666688 |
| 64 | - | 6.447008 |
| 128 | - | - |

![image](https://github.com/Ence1adus/Digital-image-processing/assets/144054132/8f36f36e-98fc-4f56-abf7-e11d2cb0fc6f)

Также выберем лучшие замеры для каждой релизации и представим их в сравнении
| Host | Time (Realization 1) | Time (Realization 2) | Time (Realization 3) |
| --- | --- | --- | --- |
| 5195.21 | 31.924224 | 20.150272 |6.447008|

![image](https://github.com/Ence1adus/Digital-image-processing/assets/144054132/41219132-117c-495d-b700-49c0bf22e5f3)

Также на данном девайсе были проведены замеры для маленьний матрицы 13x11 * 11x13
| Host | Time (Realization 1) | Time (Realization 2) | Time (Realization 3) |
| --- | --- | --- | --- |
| 0.9058 | 0.010240 | 0.026784 |0.025234|

![image](https://github.com/Ence1adus/Digital-image-processing/assets/144054132/3dcadc66-ad19-4901-95d7-1788fcbd0986)


Аналогичным образом сделаем замеры на девайсе: Intel(R) Iris(R) Xe Graphics
Замеры при перемножении матриц 2048x2048
| Tile | Time (Realization 2) | Time (Realization 3) |
| --- | --- | --- |
| 4 | 1319.277968 | 4567.594635 |
| 8 | 500.560312 | 827.23410 |
| 16 | 480.985416 | 186.02931 |
| 32 |- | 199.634322 |
| 64 | - | 198.010937 |
| 128 | - | - |

![image](https://github.com/Ence1adus/Digital-image-processing/assets/144054132/29df6c11-0e6e-410f-a593-321e706998b6)

| Host | Time (Realization 1) | Time (Realization 2) | Time (Realization 3) |
| --- | --- | --- | --- |
| 5195.21 | 1197.112187 | 480.985416 |186.02931|

![image](https://github.com/Ence1adus/Digital-image-processing/assets/144054132/afdb4681-35c2-4b63-bc77-0f3023364bf0)

И для девайса: 12th Gen Intel(R) Core(TM) i5-12500H
Замеры при перемножении матриц 2048x2048
| Tile | Time (Realization 2) | Time (Realization 3) |
| --- | --- | --- |
| 4 | 1417.110300 | 654.563300 |
| 8 | 281.428800 | 236.765200 |
| 16 | 134.784000 | 134.878100 |
| 32 |97.283500 | 41.387000 |
| 64 | 89.880200 | 198.010937 |
| 128 | - | - |

![image](https://github.com/Ence1adus/Digital-image-processing/assets/144054132/b7f609e8-5378-4511-a279-a11ba777f605)

| Host | Time (Realization 1) | Time (Realization 2) | Time (Realization 3) |
| --- | --- | --- | --- |
| 5195.21 | 1095.038900 | 89.880200 |41.387000|

![image](https://github.com/Ence1adus/Digital-image-processing/assets/144054132/8f33226f-4a89-4591-abde-1bedb69d5cfd)
