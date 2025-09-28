# Sistema de Chat con Colas de Mensajes

## Presentado por: 
- Juan Pablo Duque 
- Thomas Gonzalez
- Hellen Yanes 

## Descripción
Este proyecto implementa un sistema de chat en C  utilizando colas de mensajes para la comunicación entre procesos.
Un servidor central administra las salas de chat, y los clientes pueden unirse a ellas para enviar y recibir mensajes en tiempo real.

## Compilación
En la carpeta del proyecto:

``` gcc server.c -o server -lrt -lpthread ```
``` gcc client.c -o client -lrt -lpthread ```

## Ejecución 
En una terminal iniciar el servidor: 

``` ./server ```

Iniciar clientes en otras terminales:

``` ./client <nombre_usuario> ```
