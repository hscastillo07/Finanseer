# Finanseer

Para poder ejecutar el programa es necesario:

Descargar los archivos y ubicarse en la carpeta client.
Ejecutar el comando npm install para instalar todas las dependencias necesarias.
Una vez instalado, ejecutar el comando npm run dev

En esta version es necesario que el usuario cree dos archivos de variable de entorno,
en el lado del client debes crear un archivo llamado .env.local que contenga lo siguiente:

VITE_BASE_URL=http://localhost:1337

en el lado del server debes crear un archivo llamado .env que contenga:

MONGO_URL = 'mongodb+srv://user:1234@cluster0.koxvpai.mongodb.net/?retryWrites=true&w=majority'

PORT = 1337


Y listo! deberias poder ver el programa en localhost:5173.
Si no puedes ejecutar el codigo despues de esto, tal vez debas instalar npm o node.js. 
Recuerda estar posicionado en la carpeta client en todo momento
