## desafio-global-child

## Configuración inicial

Previo a la ejecución del proyecto se debe crear en el directorio raiz del mismo un archivo `.env` con 4 variables 
```
NODE_ENV=local
NODE_URL="http://localhost:8080/"
SALT=$2b$10$8yXiHZej9hIp0Me8TzwhHe
MONGODB_URI=mongodb+srv://developer:xKC5-!M2BngHsNg@cluster0.lwkvzm9.mongodb.net/login?retryWrites=true&w=majority
```
Una vez configuradas las variables de entorno se debe ejecutar el siguiente comando para inicializar la aplicación

```
npm run dev
```
Para probar el formulario de info del sistema se debe ingresar al sgte enlace:

visit http://localhost:8080/info

Para probar el endpoint de calculo se debe ingresar al sgte enlace y pasar por query param la cantidad opcionalmente:

visit http://localhost:8080/api/random?cant=5000
