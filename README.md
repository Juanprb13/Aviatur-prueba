# Prueba Aviatur 

Esta prueba tiene backend y front-end en nodeJS y Angular

## Installation
## BackEnd

dirigase a la carpeta '/backend' y ejecute los siguientes comandos

```bash
npm i
npm start
```
cuando ejecute los dos comandos verifica que el servidor este corriendo sin problemas 

## FrontEnd

dirigase a la carpeta '/hoteles' y ejecute los siguientes comandos

```bash
npm i
npm i -g @angular/cli
ng serve
```
cuando todo este funcionando de manera correta, verifique que el CLI de angular si este instalado en su maquina, de lo contrario no va a poder ver el proyecto de angular 

El servidor de front escucha este puerto 

http://localhost:4200/


El proyecto se puede filtrar por nombre y por cantidad de estrellas.
Puedes colocar el nombre de un hotel, pero tiene que ser identico, al darle enter el back se encargara de filtrar la data y mostratela filtrada 

si quieres volver a ver todos los datos solo da clic en el boton de "Ver todos "
para el filtro por estrella solo dale clic y el te lo filtrara solo 

si se queda bugueado o no muestra data revisa que el imput name no tenga espacios, no me dio el tiempo para hacer la crud completa pero se hizo front y back, tener eso en cuenta 
