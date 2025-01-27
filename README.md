# Análisis

### ¿Qué tan fácil fue adivinar las contraseñas? 
El uso del fichero Rockyou.txt facilitó en gran medida la desencriptación de estas contraseñas, además de que todas las claves que se debían adivinar seguían un patrón sencillo (*palabra* + **año** + *).

### ¿Cuánto tiempo aproximadamente duró el equipo en adivinar las contraseñas?
Sorprendentemente, el tiempo de ejecución del código desarrollado por el equipo estuvo en un intervalo de entre 630 y 970 milisegundos (~1 segundo). Este código fue capaz de procesar y agregar un año junto a un asterisco a cada contraseña, para luego convertirlas en un hash y compararlas con otros hashes filtrados, logrando así adivinar las contraseñas.

![image](https://github.com/user-attachments/assets/ab7c1f5f-909f-4335-8910-bed4a4f81b9c)

### ¿Qué particularidad tienen estas contraseñas? 
Todas las contraseñas siguen un mismo patrón común (*palabra* + **año** + *), donde tienen la particularidad de contener palabras clave que hacen parte de las contraseñas más comunes (nombres, comida, paises, meses, marcas, entre otros), un año (en un rango relativamente de los más recientes) y un caracter especial concurrente en contraseñas como el asterisco.

### ¿Con base en lo encontrado en este ejercicio, qué recomendaciones darías para tener una contraseña segura?
+ No seguir patrones (en especial si se basan en combinaciones sencillas de palabras y números).
+ Formar juegos de palabras.
+ Si se incluyen números, que estos no sea referentes a cosas comunes como años.
+ Incluir más de un carácter especial.
+ Variar entre mayúsculas, minúsculas y números.
+ No contener información personal como nombres o fechas especiales.
+ Mínimo contener 10 caracteres.
