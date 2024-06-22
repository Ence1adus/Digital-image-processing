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
| 0.9058 | 0.010240 | 0.026784 |0.026784|

![image](https://github.com/Ence1adus/Digital-image-processing/assets/144054132/7b12e496-8172-4dc1-91ab-86de113414de)
