# 🚀 How to run the MySQL and Todo App Containers

## 🐳 Run MySQL Container with Volume

```bash
docker run -d \
  --name mysql-container \
  -p 3306:3306 \
  -v mysql-data:/var/lib/mysql \
  <your_dockerhub_username>/mysql-local:1.0.0