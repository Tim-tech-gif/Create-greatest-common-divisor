# Create-greatest-common-divisor
def gcd(a, b):     while b:         a, b = b, a % b     return abs(a)  # Приклад використання num1 = 56 num2 = 98 result = gcd(num1, num2) print(f"Найбільший спільний дільник {num1} і {num2} дорівнює {result}.")
