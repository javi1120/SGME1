# creed
# para permitir peticiones al backend sin problema de cors se debe crear el archivo proxy.conf.json 
# de igual forma se debe poner en el angular json 

  "serve": {
    "options": {
      "proxyConfig": "proxy.conf.json"
    }
  }

# .ignore me quita las librerias de node modules 
# 1
Comandos github:
Ingresar a una terminal de comandos:
Ingresamos a la carpeta del backend:
cd .\BACK_SGME\
Instalamos los paquetes necesarios:
npm i
Iniciamos el backend:
npm start
—-------
Ahora el front end:
cd .\PROYECT_SGME
npm install
Ahora iniciamos el proyecto:
ng serve -o

# 2
revisar credenciales en .env
guardar cambios

iniciar el back: npm start 
iniciar el front end: ng serve --port 4300  (o) -o  

isntalar paquetes
npm install nodemon 

para iniciar sin cors
chrome.exe --disable-web-security --user-data-dir="C:/ChromeDev"
para crear un nuevo modulo , crear en la terminal ng g c internal_pages/"reportes" -- puede ser otro nombre
luego modificar la parte de la base de datos
SELECT * from sgme.menus
insertar los datos manera manual si es posible.
nombre - puede ser cualquiera, estado - true,  