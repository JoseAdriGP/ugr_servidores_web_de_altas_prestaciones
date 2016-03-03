---
title: SWAP Ejercicios Tema 2
layout: post
author: erseco
source-id: 1x2kGMixyvNDq1E-nvcjoYPKQmjgrxfqwEJgTGKXnxGo
published: true
---
# SWAP - Ejercicios Tema 2

### Ejercicio 2.1. Calcular la disponibilidad del sistema si tenemos dos réplicas de cada elemento (en total 3 elementos en cada subsistema)

<table>
  <tr>
    <td></td>
    <td>normal</td>
    <td>duplicado</td>
    <td>triplicado</td>
  </tr>
  <tr>
    <td>web</td>
    <td>85%</td>
    <td>97,75%</td>
    <td>99,66</td>
  </tr>
  <tr>
    <td>app</td>
    <td>90%</td>
    <td>99%</td>
    <td>100%</td>
  </tr>
  <tr>
    <td>bd</td>
    <td>99,90%</td>
    <td>100,00%</td>
    <td>100%</td>
  </tr>
  <tr>
    <td>dns</td>
    <td>98%</td>
    <td>99,96%</td>
    <td>100%</td>
  </tr>
  <tr>
    <td>firewall</td>
    <td>85%</td>
    <td>97,75%</td>
    <td>99,66</td>
  </tr>
  <tr>
    <td>switch</td>
    <td>99%</td>
    <td>99,99%</td>
    <td>100%</td>
  </tr>
  <tr>
    <td>cpd</td>
    <td>99,99%</td>
    <td>99,99%</td>
    <td>99,99</td>
  </tr>
  <tr>
    <td>isp</td>
    <td>95%</td>
    <td>99,75%</td>
    <td>100%</td>
  </tr>
</table>


### Ejercicio 2.2. Buscar frameworks y librerías para diferentes lenguajes que permitan hacer aplicaciones altamente disponibles con relativa facilidad.

### Como ejemplo, examina PM2 https://github.com/Unitech/pm2

### que sirve para administrar clústeres de NodeJS. 

* MySQL Router para balancear bases de datos MySQL de forma sencilla

* QNX High Availability Framework  para tener maquinas de tiempo real QNX con alta disponibilidad

* PM2 para gestionar nodos parece muy sencillo, puedes ir lanzando instancias

* El gestor de contenedores Docker tambien permite facil escalabilidad, así como las máquinas virtuales XEN, que permiten pasar una instancia de un SO en ejecución entre varias máquinas en caliente.

### Ejercicio 2.3. ¿Cómo analizar el nivel de carga de cada uno de los subsistemas en el servidor?

### Buscar herramientas y aprender a usarlas. ...¡o recordar cómo usarlas!

<table>
  <tr>
    <td>comando</td>
    <td>explicación</td>
  </tr>
  <tr>
    <td>top</td>
    <td>Muestra el uso de la memoria y la CPU</td>
  </tr>
  <tr>
    <td>netstat</td>
    <td>Para monitorizar la carga de la red, aunque hay herramientas mucho mejores</td>
  </tr>
  <tr>
    <td>df</td>
    <td>Para ver como vamos de disco</td>
  </tr>
</table>


### **Ejercicio 2.4.** Buscar ejemplos de balanceadores software y hardware (productos comerciales).

Buscar productos comerciales para servidores de aplicaciones.

Buscar productos comerciales para servidores de almacenamiento.

<table>
  <tr>
    <td>Balanceador Software</td>
    <td>HAProxy como balanceador de carga http por software</td>
  </tr>
  <tr>
    <td>Balanceador Hardware</td>
    <td>TP-LINK TL-R470T+ Load Balance Broadband Router por hardware</td>
  </tr>
  <tr>
    <td>Balanceador de aplicaciones</td>
    <td>Barracuda Load Balancer ADC</td>
  </tr>
  <tr>
    <td>Servidor almacenamiento</td>
    <td>Netgear ReadyNAS Home RN10400-100EUS</td>
  </tr>
</table>


