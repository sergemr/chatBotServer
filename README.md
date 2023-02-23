Conectar OpenAI a Dialogflow CX
Cosas que necesitará
Dialogflow CX agente

algunos conocimientos de Dialogflow CX también

OpenAI cuenta y clave de API

crear una cuenta aquí

NGROK para exponer nuestro servidor local a internet para pruebas

consígalo desde aquí

empezar con ngrok http 5001

Nodejs como herramienta de programación

instalarlo desde aquí

Como usarlo
instala todos los paquetes necesarios en la carpeta del proyecto
usa el comando npm install --save

crear un archivo .env en la carpeta y establecer dos variables PORT y OPENAI_API_KEY
ejecuta el servidor local npm run start
arranca el motor NGROK
asegúrate de que los puertos son los mismos

establece la url de NGROK en la sección Webhook
TU URL/dialogflow NGRK debería ser algo como esto

prueba la conexión

# chatBotServer
