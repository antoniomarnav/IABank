# IABank
Para levantar el n8n con ollama en un servidor local necesitamos:
* Docker Desktop
* Git

Tenemos que clonar el repositorio de self-hosted-ai-starter-kit de n8n
git clone https://github.com/n8n-io/self-hosted-ai-starter-kit.git

Abrimos un cmd dentro de la descarga y lanzamos el docker, en este caso con perfil cpu:
docker compose --profile cpu pull

Una vez termine, escribimos en el cmd para levantarlo:
docker compose create && docker compose --profile cpu up

Den la ruta http://localhost:5678/ tendremos el n8n corriendo
