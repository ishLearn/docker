# ISH/Learn Docker
## Why this repo? 
Cloning this repo and running the docker compose stack is the easiest way to host your own instance of ISH/Learn.

## Self-hosting ISH/Learn 
1. Clone this repository: `git clone https://github.com/ishLearn/docker.git`
2. Run `docker compose up` to run deploy the stack. This will automatically
    1. download the latest versions of the required docker containers (otherwise, you can do it manually with `docker compose pull`)
    2. run the containers: `docker compose up`. You may want to use the `--detached` (or `-d`) flag which will start the containers and then run them detached from the terminal window. 
