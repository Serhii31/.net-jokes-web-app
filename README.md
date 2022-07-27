# ASP.NET Core Jokes Web Application
## Start application locally with Docker
1. Clone the repository:
```bash
git clone https://github.com/Serhii31/.net-jokes-web-app.git
```
2. Change directory to .net-jokes-web-app
```bash
cd .net-jokes-web-app
```
3. Install the latest versions of Docker and Docker-Compose
4. To start application execute the following command in PS:
```bash
.\startup.ps1 entrypoint.sh
```
5. To access application open localhost:8080
6. To stop application run the following command:
```bash
docker-compose down
```