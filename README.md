# 
# My-Notes App

My-Notes is a simple web application for taking notes.

## Features
- Create new notes
- Edit existing notes
- Delete notes



### Running with Docker
1. Make sure you have Docker installed on your machine.
2. Clone this repository. 
(All the html,css and javascript files are orignally pulled from https://github.com/bradtraversy/50projects50days/tree/master/notes-app)

3. Navigate to the project directory.
4. Build the Docker image:
   ```bash
   docker build -t my-notes-app .
5. Run the Docker container:
   ```bash
   docker run -p 80:80 my-app
6. Open your web browser and navigate to http://localhost:8080 to access the app.
7. Clean up the docker using 
``` bash
docker stop my-app
docker rm my-app
docker rmi my-app
