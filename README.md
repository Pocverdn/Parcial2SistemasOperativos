# Parcial 2 Sistemas Operativos

### Integrantes:
* Santiago Sanchez Carvajal
* Samuel Velez Gaviria
* El Maxi MC

## Resumen

Este proyecto es un programa de procesamiento de imagenes desarrollado en C, esta diseñado para trabajar en linux y tiene como proposito emplear lo visto en clase de sistemas operativos, entre eso tecnicas de:

* Manejo de matrices (grises y RGB)
* Uso de concurrencia y paralelización con pthreads para acelerar las operaciones
* Gestión de memoria manual

El proyecto cuenta con un total de cinco funciones, una proporcionado por el profesor y cuatro hechas por el equipo de trabajos, las funciones hechas por los estudiantes son:

* Rotación de imagenes por hilos
* Detección de bordes por hilos
* Escalamiento de imagenes por hilos
* Suavizar imagenes por hilos


## Requisitos

Asegurarse de contar con las dependencias adecuadas para el manejo de imagenes, estas son:

* stb_image.h
* stb_image_write.h

Adicionalmente es recomendable emplear un sistema operativo linux como ubuntu, un copilador de C y la libreria de pthreads


## Copilar y ejecutar

Para copilar el codigo es necesario ejecutar el siguiente comando

`gcc -o img main.c -pthread -lm`

Esto garantizar que se importe la librerias de pthread para trabajar con hilos.

Finalmente ejecuta el siguiente comando para correr el programa

`./img [ruta_imagen.png]`

## Ejemplo de uso

### Paso 1 ejecutar:

<img width="892" height="376" alt="image" src="https://github.com/user-attachments/assets/f2b1af97-9d63-40b2-8f04-1484cca1d9f8" />
<img width="1269" height="526" alt="image" src="https://github.com/user-attachments/assets/02651909-1b8e-4d8b-b5c0-a8f4c0156ed7" />

### Paso 2 Rotar imagen 180°:

<img width="828" height="321" alt="image" src="https://github.com/user-attachments/assets/eb45b5e7-006e-4d34-bbc2-7ef95941748a" />

### Parte 3 guardar imagen:

<img width="637" height="303" alt="image" src="https://github.com/user-attachments/assets/f6e0c807-c71a-4468-b2ad-84d1f59b91b0" />

### Resultado

![potter](https://github.com/user-attachments/assets/70e542fd-a845-406a-9f07-a73133f47bad)
<img width="1600" height="1200" alt="test" src="https://github.com/user-attachments/assets/9e6d6e3f-7ec6-41cd-810e-3c050a6964d3" />


