# Template Python

This project aims to be a "clone, run, code" with as few steps as possible.

It runs Python 3.9.13 on Debian Bullseye.

Well, using python you have conda and many other tools. This sample environment is a portable and common one to use with VSCode. And conda does not includes some other things, if you need a database at a specific version or a bus or any other dependency, docker-compose is the simplest and fastest solution to get a common environement. Is is also easy to change a little bit the given Dockerfile and docker-compose to deploy a new microservice to your swarm / kubernetes cluster.

## Steps

1. **Having the environment running**
   - Linux : VSCode + Docker
   - Mac : VScode + Docker Desktop
   - Windows : VSCode + WSL + Docker Desktop
   - VSCode extensions
     - Both : `ms-vscode-remote.remote-containers`
     - Windows : `ms-vscode-remote.remote-wsl`
2. **Clone this repo**
   - _Windows : clone into your WSL box_
3. **Change python version to your needs in `.devcontainer/devcontainer.json`**
4. **Open with VSCode**
5. **Run VSCode `Debug: Start Debugging` command**
   - _Open your main python and press <kbd>F5</kbd>_