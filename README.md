# Development Sandbox
As a data engineer in a team, usually a stack is needed in order
to solve business issues. I created this project to host common
service tier to handle data in hypotetic scenario

## Jupyter Notebook
Build my own Jupyter Notebook for play with data on my on computer. I took the docker-compose code base from [docker-stack for Jupyter](https://github.com/jupyter/docker-stacks)] 

### Prerrequisites for Docker
1. Install docker-machine.
2. Create default machine.
3. Run `eval $(docker-machine env)` to configure your shell 
4. Run bash file `run.sh`

### Prerrequisites for Kubernetes
1. Install minikube (for local development)
2. Install kubectl
3. Run the command `kubectl apply -f kubernetes`
4. Run the command `kubectl -n jupyter logs <podname> -c scipy-notebook` to get token for Juyper Notebook server.
