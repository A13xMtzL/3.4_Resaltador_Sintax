# Resaltador de Sintaxis en Racket
Este proyecto es un resaltador de sintaxis para archivos de código en C, implementado en el lenguaje de programación Racket.

### Funcionalidades
El programa realiza las siguientes tareas:

1. Lee un archivo de texto que contiene código en C.
2. Analiza el archivo de texto carácter por carácter.
3. Identifica y resalta la sintaxis del código en C, incluyendo palabras reservadas, tipos de datos, números, elementos léxicos y comentarios.
4. Genera un archivo HTML con el código resaltado.
### Uso
Para usar este programa, debes tener instalado Racket en tu computadora.

Para ejecutar el programa, debes ingresar la siguiente línea en la consola de Racket:

```
(input lectura_archivo "C")
```

Donde `lectura_archivo` es la ruta del archivo que quieres analizar.

### Configuración
Antes de ejecutar el programa, debes cambiar las rutas de los archivos en las siguientes líneas de código:
  
  ```
  (define ruta_archivo "C:/Users/Usuario/Desktop/Proyecto/entrada.txt
  
  (define ruta_archivo_salida "C:/Users/Usuario/Desktop/Proyecto/salida.html")
  ```

  `lectura_archivo` es la ruta del archivo que quieres analizar y `salida_resaltador` es la ruta donde se guardará el archivo HTML generado.