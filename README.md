# Instructions
1. Build & Run
bash
# Build image
```
docker build -t flask-app .
```
# Run container 
```
docker run -p 5000:5000 flask-app
```
# Run in background 
```
docker run -d -p 5000:5000 --name my-flask flask-app
```
➔ Access: http://localhost:5000

2. Manage Container
bash

# Stop container
```
docker stop my-flask
```
# Start again
```
docker start my-flask
```

🚀 Done! Container is running at http://localhost:5000.

