# Login seguro para un sistema legado

Prototipo hecho en Google Colab con Python.

## Caso de uso
Una tienda usa un sistema antiguo que guarda usuarios y contraseñas en texto plano.
Este prototipo valida esos datos, migra solo los correctos a una base de datos nueva
y guarda las contraseñas como hash con sal.

## Qué incluye
- Validación de usuario, correo y contraseña.
- Hash de contraseñas con PBKDF2 y sal aleatoria.
- Consultas parametrizadas para evitar inyección SQL.
- Login con bloqueo después de 3 intentos fallidos.

## Cómo probarlo
[Abrir en Google Colab](https://colab.research.google.com/github/DavorgRP/Login_Seguro_Sistema_Legado.ipynb)

Ejecuta las celdas en orden, de la 1 a la 6.
