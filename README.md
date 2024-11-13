# CrossPlatformMkr
# Варіант 54

Описано рекурсивну функцію з трьома параметрами F(a, b, c): 

    якщо a ≤ 0 або b ≤ 0 або c ≤ 0, то F(a, b, c) = 1

    якщо a > 20 чи b > 20 чи c > 20, то F(a, b, c) = F(20, 20, 20)

    якщо a < b та b < c, то F(a, b, c) = F(a, b, c-1) + F(a, b-1, c-1) - F(a, b-1) , c)

    інакше F(a, b, c) = F(a-1, b, c) + F(a-1, b-1, c) + F(a-1, b, c-1) - F(a -1, b-1, c-1)

Однак, якщо вказану функцію реалізувати безпосередньо, то навіть для невеликих значень a, b та c (наприклад, a = 15, b = 15, c = 15), програма працюватиме кілька годин! Необхідно реалізувати ефективний алгоритм обчислення функції F, який встигне знайти будь-яке значення менш ніж за одну секунду!

Вхідні дані

Вхідний файл INPUT.TXT містить три цілі числа a, b, c - параметри функції F (-104 ≤ a, b, c ≤ 104).
Вихідні дані

У вихідний файл OUTPUT.TXT виведіть значення функції F(a, b, c).

![image](https://github.com/user-attachments/assets/57e80f77-bb59-472d-b985-65108f1ffd09)
