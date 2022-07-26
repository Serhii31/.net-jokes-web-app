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
4. Convert the file to use Unix-style line endings
```bash
sed -i 's/\r$//' entrypoint.sh
```
5. To start application run the following command:
```bash
docker-compose up --build
```
6. To access application open localhost:8080
7. To stop application run the following command:
```bash
docker-compose down
```