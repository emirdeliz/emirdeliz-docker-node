# emirdeliz-vs-workspace-container

This is a simple repo to use with the vscode container approach.

### How to use?

- Run the script ```make-symlink.sh```. This script make a symbol link for the ```.devcontainer``` folder on the parent folder (workspace root).
- Edit the file ```.devcontainer/.env.docker.template``` and set the docker image and docker platform.
- Open the vscode container.

### Requirements:

This container needs [docker-sync](http://docker-sync.io) to use as docker volume.

![Screen Shot 2023-02-13 at 08 00 18](https://user-images.githubusercontent.com/6270495/218440784-22fe9e11-b378-4c2c-a35b-3500db8ede12.png)
