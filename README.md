# dockerexp1_lab8
| S.No. | Command                                          | Use                                                    |
| ----- | ------------------------------------------------ | ------------------------------------------------------ |
| 1     | `wsl --install`                                  | Installs WSL and its required components.              |
| 2     | `wsl --update`                                   | Updates WSL.                                           |
| 3     | `wsl --status`                                   | Displays WSL status and settings.                      |
| 4     | `wsl -l -v`                                      | Lists Linux distributions and their WSL versions.      |
| 5     | `docker --version`                               | Displays the Docker version.                           |
| 6     | `docker info`                                    | Displays Docker engine information.                    |
| 7     | `docker run hello-world`                         | Tests whether Docker is working.                       |
| 8     | `docker pull nginx`                              | Downloads the Nginx image from Docker Hub.             |
| 9     | `docker images`                                  | Lists downloaded Docker images.                        |
| 10    | `docker run -d -p 8080:80 --name my-nginx nginx` | Creates and runs an Nginx container in the background. |
| 11    | `docker ps`                                      | Lists running containers.                              |
| 12    | `docker ps -a`                                   | Lists all containers, including stopped ones.          |
| 13    | `docker stop my-nginx`                           | Stops the Nginx container.                             |
| 14    | `docker rm my-nginx`                             | Removes the Nginx container.                           |
| 15    | `docker rmi nginx`                               | Removes the Nginx image.                               |
