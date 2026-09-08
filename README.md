# Claves-SSH-
# Actividad interactiva – Autenticación mediante claves SSH

Este repositorio contiene una actividad interactiva utilizada como cierre de una clase de **Administración de Sistemas Operativos III** sobre autenticación mediante claves SSH.

## Objetivo

Comparar de forma visual y participativa dos mecanismos de autenticación utilizados en SSH:

- Autenticación mediante contraseña.
- Autenticación mediante claves SSH.

La actividad busca que los estudiantes puedan identificar las principales diferencias entre ambos mecanismos y justificar sus decisiones oralmente.

## Dinámica

Durante el cierre de la clase se presentan distintas afirmaciones relacionadas con SSH.

Los estudiantes deben indicar si cada afirmación corresponde a:

- **Contraseña**
- **Claves SSH**

Además de clasificar cada elemento, deberán justificar oralmente por qué pertenece a esa categoría.

El docente arrastra cada tarjeta hacia la categoría correspondiente según las respuestas del grupo.

## Conceptos trabajados

- Autenticación mediante SSH.
- Usuario y contraseña.
- Clave pública.
- Clave privada.
- Par de claves SSH.
- Autorización de claves públicas.
- `authorized_keys`.
- Diferencias entre autenticación por contraseña y por claves.
- Uso de claves SSH para conexiones frecuentes a servidores.

## Idea principal

La clave privada permanece protegida en el equipo cliente y no se comparte.

La clave pública puede ser autorizada en uno o varios servidores.

Durante la autenticación, el cliente utiliza su clave privada para generar una prueba criptográfica y el servidor utiliza la clave pública autorizada para verificarla.

## Uso

Abrir el archivo `index.html` en un navegador.

También puede publicarse mediante **GitHub Pages** para acceder a la actividad desde cualquier equipo con navegador web.

## Tecnologías utilizadas

- HTML
- CSS
- JavaScript

## Autor

Ezequiel Costa

Profesorado de Informática  
Administración de Sistemas Operativos III  
2026
