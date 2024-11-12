def newton_raphson_root_fourth(a, tolerance=1e-6, max_iterations=100):
    x = a / 2.0
    for _ in range(max_iterations):
        f_x = x**4 - a
        f_prime_x = 4 * x**3
        x_new = x - f_x / f_prime_x
        if abs(x_new - x) < tolerance:
            return x_new
        x = x_new
    return x
a = 16
root = newton_raphson_root_fourth(a)
print(f"The fourth root of {a} is approximately: {root}")