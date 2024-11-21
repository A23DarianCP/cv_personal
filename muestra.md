# Muestra de Trabajo

## Ejemplo en kotlin
fun main() {
    var num = readln()!!.toInt()
    if(num %2 == 0) {
        println("$num es un número par")
    }
    else {
        println("$num es un número impar")
    }
}
## Ejemplo en html
<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Mi Página Web</title>
    <!-- Favicon en formato .ico -->
    <link rel="icon" href="favicon.ico" type="image/x-icon">
    <!-- Favicon en formato PNG para diferentes tamaños -->
    <link rel="icon" type="image/png" sizes="16x16" href="favicon-16x16.png">
</head>
<body>
    <h1>Bienvenido a mi página web</h1>
    <p>Esta es una página HTML sencilla con favicon en varios formatos.</p>
</body>
</html>
# Programa en Python

suma = 0

while True:
    numero = int(input("Ingresa un número (0 para terminar): "))
    if numero == 0:
        break
    suma += numero
    print(f"La suma actual es: {suma}")

print(f"La suma final es: {suma}")

