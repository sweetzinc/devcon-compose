
## devcontainer
Note: a local (Windows11) folder is mounted to the devcontainer via `docker-compose.yml: "volumes" `

### Opening Folder
* For this opening, we need to explicitly set the folder mount through `docker-compose.yml`
1. VSCode Command: Dev Containers: Open Folder in Container...
2. VSCode Terminal: `python torch_gpu_test.py`

### Cloning a repo
* VSCode Command: Dev Containers: Clone Repository in Container Volume...

[Documentation](https://code.visualstudio.com/docs/devcontainers/containers#_quick-start-open-a-git-repository-or-github-pr-in-an-isolated-container-volume)
