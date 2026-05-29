# RockyBalboa123
# ============================================
# Archivo: print_python.py
# Ejercicio: Método print() en Python
# ============================================

# --- 1. Mensaje simple ---
print("Hola Mundo...")

# --- 2. Declaración de variables (tipado dinámico) ---
a = 2.1
b = 3
c = 'c'
palabra = "Esto es una prueba."

# --- 3. Imprimir tipo de dato con type() ---
print(type(a))       # <class 'float'>
print(type(b))       # <class 'int'>
print(type(c))       # <class 'str'>

# --- 4. Cálculo de media e impresión con round() ---
media = (a + b + 2.5) / 3
print("La media entre a, b y 2.5 es:", round(media, 3))

# --- 5. Imprimir variable con texto ---
i = 5
print("\nEl valor de i es ", i, "\n")

# --- 6. Imprimir cadena de caracteres ---
print(palabra + "\n")

# --- 7. Concatenación con str() ---
print("El valor de i como string: " + str(i))

# --- 8. F-strings (forma moderna) ---
print(f"La variable a = {a}")
print(f"La variable b = {b}")
print(f"La media es: {round(media, 3)}")

# --- 9. Parámetros sep y end ---
print(a, b, c, sep=" | ")
print("Primera parte -", end=" ")
print("misma línea")
