# Finanseer

Para poder ejecutar el programa es necesario:

Descargar los archivos y ubicarse en la carpeta client.
Ejecutar el comando npm install para instalar todas las dependencias necesarias.
Una vez instalado, ejecutar el comando npm run dev

En esta version es necesario que el usuario cree dos archivos de variable de entorno,
en el lado del client debes crear un archivo llamado .env.local que contenga lo siguiente:

VITE_BASE_URL=http://localhost:1337

en el lado del server debes crear un archivo llamado .env que contenga:

MONGO_URL = 'mongodb+srv://user:password@cluster0.koxvpai.mongodb.net/?retryWrites=true&w=majority'
Debes crear tu propia base de datos e implementarla con un link parecido al de arriba

PORT = 1337

Tambien debes tener en cuenta que ahora el proyecto cuenta tanto como con client como con server, por lo cual debes abrir dos terminales distintas y ejecutar el comando npm run dev en ambas carpetas.

Deberias poder ver el programa en localhost:5173.


Dependiendo a tus necesidades solo debes editar el archivo data.js ubicado en backend/data de manera que los atributos sean consistentes con el frontend y listo! puedes visualizar cualquier tipo de datos y valores monetarios tales como indicadores economicos, valor de una moneda especifica, valor de un recurso.

Si quieres hacer uso adecuado del apartado de predicciones debes ingresar datos de un año entero para poder predecir los valores del año siguiente.

Si no puedes ejecutar el codigo despues de esto, tal vez debas instalar npm o node.js. 
Recuerda estar posicionado en la carpeta client en todo momento
