# Simple Notes App
This is a simple notes app built with React and Django.

## Requirements
1. Python 3.9
2. Node.js
3. React

## Installation
1. Clone the repository
```
git clone https://github.com/Sujal-SM/django_notes_app_dockerised.git
```

2. Build the app
```
docker build -t notes-app .
```

3. Run the app
```
docker run -d -p 8000:8000 notes-app:latest
```

## Nginx

Install Nginx reverse proxy to make this application available

`sudo apt-get update`
`sudo apt install nginx`

nginx runs on port no. 80


## Docker Commands

### Build the image
```bash
docker build -t <your-username>/django_notes_app_docker:latest .

docker run -d -p 8000:8000 <your-username>/django_notes_app_docker:latest

Push to docker hub:

docker push <your-username>/django_notes_app_docker:latest

if you want to pull:

docker pull <your-username>/django_notes_app_docker:latest
``` 

