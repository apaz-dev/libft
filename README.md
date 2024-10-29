# 📚 Libft 

**Libft** mi primer proyecto de 42madrid.

## ✨ Resumen del proyecto

Este proyecto consiste en programar una librería en C.
Tu librería tendrá un montón de funciones de propósito general en las que se apoyarán
tus programas.

## 📖 Descripción de funciones

### 1. Funciones de Manipulación de Cadenas 📏

Estas funciones son esenciales para manipular cadenas de caracteres y se basan en las funciones estándar de ```<string.h>```:

  -```ft_strlen```: Calcula la longitud de una cadena.
  
  -```ft_strcpy, ft_strncpy```: Copia una cadena en otra.
    
  -```ft_strdup```: Duplica una cadena en un nuevo bloque de memoria.
     
  -```ft_strcat, ft_strncat```: Concatena cadenas.
  
  -```ft_strchr, ft_strrchr```: Localiza caracteres dentro de una cadena.
  
  -```ft_strcmp, ft_strncmp```: Compara cadenas de caracteres.
  
  -```ft_strstr, ft_strnstr```: Encuentra subcadenas dentro de una cadena.

###  2. Funciones de Manipulación de Memoria 💾

Estas funciones son útiles para gestionar la memoria manualmente y se basan en funciones de ```<stdlib.h>```:

  -```ft_memset```: Rellena un bloque de memoria con un valor específico.
  
  -```ft_bzero```: Llena con ceros un bloque de memoria.
  
  -```ft_memcpy```: Copia memoria de una ubicación a otra.
  
  -```ft_memmove```: Mueve un bloque de memoria. (Tiene en cuenta el overlapping)
  
  -```ft_memchr```: Busca un byte en un bloque de memoria.

  -```ft_memcmp```: Compara dos bloques de memoria.
  
  -```ft_calloc```: Reserva y limpia un bloque de memoria.
  
### 3. Funciones de Conversión 🔄

Funciones que transforman datos entre distintos tipos:

  -```ft_atoi```: Convierte una cadena en un número entero.
  
  -```ft_itoa```: Convierte un número entero en una cadena.
  
  -```ft_tolower, ft_toupper```: Convierte caracteres de mayúsculas a minúsculas y viceversa.

### 4. Funciones de Verificación de Caracteres 🔍

Estas funciones son utilizadas para verificar tipos de caracteres:

  -```ft_isalpha```: Verifica si el carácter es alfabético.
  
  -```ft_isdigit```: Verifica si el carácter es numérico.
  
  -```ft_isalnum```: Verifica si el carácter es alfanumérico.
  
  -```ft_isascii```: Verifica si el carácter es ASCII.
  
  -```ft_isprint```: Verifica si el carácter es imprimible.

### 5. Funciones Adicionales ✨

Estas funciones adicionales complementan la biblioteca básica:

  -```ft_substr```: Crea una subcadena a partir de una cadena dada.
  
  -```ft_strjoin```: Une dos cadenas en una nueva cadena.
  
  -```ft_strtrim```: Elimina caracteres en blanco al inicio y final de una cadena.
  
  -```ft_split```: Divide una cadena en subcadenas utilizando un delimitador.
  
  -```ft_strmapi```: Aplica una función a cada carácter de una cadena, generando una nueva.
  
  -```ft_putchar_fd```: Escribe un carácter en un descriptor de archivo.
  
  -```ft_putstr_fd```: Escribe una cadena en un descriptor de archivo.
  
  -```ft_putendl_fd```: Escribe una cadena seguida de un salto de línea en un descriptor de archivo.
  
  -```ft_putnbr_fd```: Escribe un número en un descriptor de archivo.

## ⚙️ Compilación

Para compilar la biblioteca, clona este repositorio y ejecuta el comando:

```C
make
```
