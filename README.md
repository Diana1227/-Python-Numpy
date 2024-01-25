# -Python-Numpy

import numpy as np

a = np.arange(10)

print("Исходный массив:")
print(a)

print("\nЭлементы с индексами от 3 до 6:")
print(a[3:7])

a[7:10] = [10, 20, 30]

print("\nИзмененный массив:")
print(a)
