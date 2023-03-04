# dev-container-node18-podman-template

jumpstart VSCode dev container for podman

https://code.visualstudio.com/docs/devcontainers/containers

https://blog.while-true-do.io/podman-configure-vscode-for-containers/


# The podman version of devcontainer setup. 


The Node containers from devcontainer template uses "node" as it's user so the container user needs to be set as such.


https://github.com/devcontainers/images/blob/c087e361571e2200c3b40ed86d14a8ced84c388a/src/javascript-node/.devcontainer/Dockerfile#L10


Use 

- Clone this repo, 
- Open in VScode 
- F1 ->Dev Containers: Rebuild and Reopen in Container


Useful commands:

```Podman system reset``` - nukes everything in podman