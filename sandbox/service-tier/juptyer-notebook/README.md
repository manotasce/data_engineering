# Infrastructure as Code Project
This section is a good place to start develop and deploy all infra I need for projects.


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
