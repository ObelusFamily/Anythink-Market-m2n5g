# Welcome to the Anythink Market repo

To start the app use Docker. It will start both frontend and backend, including all the relevant dependencies, and the db.

Please find more info about each part in the relevant Readme file ([frontend](frontend/readme.md) and [backend](backend/README.md)).

## Development

When implementing a new feature or fixing a bug, please create a new pull request against `main` from a feature/bug branch and add `@vanessa-cooper` as reviewer.

## First setup

**[TODO 05/01/2018 @vanessa-cooper]:** _It's been a while since anyone ran a fresh copy of this repo. I think it's worth documenting the steps needed to install and run the repo on a new machine?_

# Getting Started with Docker

- Docker is a container platform which simplifies and accelerates your workflow, while giving developers the freedom to innovate with their choice of tools, application stacks, and deployment environments for each project.
- A container is nothing but a standardized unit of software that allows developers to isolate their app from its environment, solving the “it works on my machine” headache.It is a standard unit of software that packages up code and all its dependencies so the application runs quickly and reliably from one computing environment to another
- A Docker container image is a lightweight, standalone, executable package of software that includes everything needed to run an application: code, runtime, system tools, system libraries and settings

## How to install Docker on your machine ?

- Using docker is pretty simple, but for that you need to install Docker on your machines.
- To install for all devices [click me](https://docs.docker.com/get-docker/).
- After downloading the suitable file your device, 
  * Run the program and follow along with the instructions.
- You can verify docker is ready by running the following commands in your terminal :  ```docker -v ``` and ``` docker-compose-v ```
- This is how it should be
![Screenshot (343)](https://user-images.githubusercontent.com/91843271/184675546-44bf38eb-1763-48f8-9c76-3b82f1ca231f.png)



## After Docker installation 

- If Docker is working correctly, the backend should be running and able to connect to your local database. Let's test this by pointing your browser to   http://localhost:3000/api/ping 
- This is the result or the page
![image](https://user-images.githubusercontent.com/91843271/184677781-8315d546-4e7f-4c24-b04f-b0d2ecc0746b.png)



## Once docker is running is successfully
 it’s time to check the ***frontend*** and make sure it’s connected to the ***backend***.
 - If everything is working properly, you’ll be able to ***create a new user*** on http://localhost:3001/register
 - This is the site which you will enter
 ![image](https://user-images.githubusercontent.com/91843271/184677810-35ccc567-bb57-46e3-97e1-f170f4fc9676.png)
 - Create one __account__ (choose a cool nickname and everything). 
 - Just make sure that you ***run all scripts*** in the next quests on one of the containers created by ``` docker-compose up ```.  Also, you can use ``` docker exec``` to run commands on a running container.
 
## Once you have completed all this , then you are good to go.
 
  
  


