# booking app

app for show bookings

## TΓ³picos
*  **[π Requerimientos / tecnologias](#-requerimientos)**
*  **[π Solucion](#-Solucion)**
*  **[π Estructura de Directorios](#-estructura-de-directorios)**
*  **[π Pruebas](#-pruebas)**

## π Requerimientos / Tecnologias
```
Nodejs 14.16.0
Angular 11.2.4
Ionic 5.4.16
Cordova 10.0.0
```
## π Solucion

Utilizando como base el proyecto booking-web en donde se utiliza Angular se integro con Ionic y Apache cordova para generar app hibridas partiendo del proyecto base

## π Estructura de Directorios
```
π¦ resume-api 
β
β  
ββπ src                  CΓ³digo fuente
β β
β ββπ app               componentes, mΓ³dulos, servicios, utils
β β
β ββπ assets            archivos
β β       
β ββπ environments      Configuracion de ambientes
β
ββπ README.md            Documentacion del software
```

## π Pruebas
### Ejecutar
1. Para Ejecutar el proyecto se debe clonar, luego de clonar se deben de descargar las dependencias, y luego iniciar o generar ejecutables
>comandos:
```
git clone git@github.com:wrumbos/booking-app.git
cd booking-web
npm install
ionic cordova build android (para generar apk)
ionic cordova run android (Para correr en un navegador)
```
### Home pagina simple que contiene un titulo
![](resources/images/1.jpeg)
### inicio de session pagina contiene un formulario para inciar session contempla validaciones
![](resources/images/2.jpeg)
![](resources/images/3.jpeg)
### booking al lograr un inicio de session exitoso a los usuarios puede consultar los bookings en donde se tendra una lista con las posibilidades de los campos id y precio filtar y ordenar
![](resources/images/4.jpeg)
