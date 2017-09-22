# AngularJS con NodeJS y MongoDB con Generator


## Instalacion

```
npm install
```

## Crear fichero de variable .env y colocar adentro las llaves de acceso

```
SENDGRID_KEY=sendgridKey
MASTER_KEY=masterKey
JWT_SECRET=jwtSecret
```
## Iniciar servicio de MongoDB
```
sudo service mongod start
```
## Dentro de Angular se encuentra el proyecto de angular donde puede ser modificado
## Pero esto involucra que debe compilarse nuevamente para que este disponible en la pagina

```
ng build
```

## Servir la aplicacion

```
npm run dev
```


## Ir a la pagina

```
localhost:9000
```
Esta aplicacion fue construida con api generator, para montar el servidor en un hosting de heroku y pasarlo a produccion ir al link
https://github.com/AlbertoIHP/rest
