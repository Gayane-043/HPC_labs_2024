# Сумма элементов вектора на CPU и GPU
В данной лабораторной работе представлен подсчет суммы элементов вектора на CPU и GPU, реализованный с помощью языка программирования Python.
#### Ход выполнения работы:

#### 1. Реализована функция для нахождения суммы элементов вектора на CPU;

#### 2. Реализована функция для нахождения суммы элементов вектора на GPU: для этого из CPU копия вектора передается на GPU, подсчитывается сумма элементов вектора с помощью функции sum, после этого результат передается обратно на CPU;
   
#### 3. Указываем размерность вектора и создаем его случайным образом, вызываем функции расчета суммы элементов CPU и GPU и выводим результаты.

Размерность вектора менялась от 1000 до 1000000. 

Таблица, отражающая время выполнения подсчета суммы элементов вектора с применением технологии CUDA:

![image](https://github.com/user-attachments/assets/d15bb4a5-d219-4416-a476-4481a4f9ea7a)

Из полученных результатов можно сделать вывод, что GPU обеспечивает увеличение скорости, которая растет при увеличении размерности вектора.
