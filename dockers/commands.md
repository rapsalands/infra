# Commands
Some common docker commands.

1. List running containers: `docker ps`
2. List running and exited containers: `docker ps -a`
3. Stop a container: `docker stop [container_name | container_id]`
	With above command, container is stopped but still in memory.

4. Remove Docker container from memory: `docker rm [container_name]`
5. List images: `docker images`
6. Delete image: `docker rmi [container_name]`
7. Run a container from image. Its downloads the image (if not found locally) and runs it if found.
    1. `docker run [container_name]`: Runs the container but blocks the console. Basically container attaches to the console.
    2. `docker -d run [container_name]`: Runs the container in detached mode which does not block the console.
	

8. Download the image but not run: `docker pull [container_name]`
9. Execute command on docker container: `docker exec [container_name] [command]`
