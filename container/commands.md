## Docker Container Commands

### 🟦 attach
Attach local standard input, output, and error streams to a running container.
```bash
docker attach {container_id}
```

### 🟦 commit
Create a new image from a container’s changes.
```bash
docker commit {container_id} {new_image_name}
```

### 🟦 cp
Copy files/folders between a container and the local filesystem.
```bash
docker cp {container_id}:{path_to_file_in_container} {path_to_local_destination}
```

### 🟦 create
Create a new container.
```bash
docker create {image_name}
```

### 🟦 diff
Inspect changes to files or directories on a container’s filesystem.
```bash
docker diff {container_id}
```

### 🟦 exec
Execute a command in a running container.
```bash
docker exec -it {container_id} {command}
```


### 🟦 export
Export a container’s filesystem as a tar archive.
```bash
docker export {container_id} > {local_tar_file}.tar
```
### 🟦 inspect
Display detailed information on one or more containers.
```bash
docker inspect {container_id}
```
### 🟦 kill
Kill one or more running containers.
```bash
docker kill {container_id}
```
### 🟦 logs
Fetch the logs of a container.
```bash
docker logs {container_id}
```
### 🟦 ls
List containers.
```bash
docker container ls
```
### 🟦 pause
Pause all processes within one or more containers.
```bash
docker pause {container_id}
```
### 🟦 port
List port mappings or a specific mapping for the container.
```bash
docker port {container_id}
```
### 🟦 prune
Remove all stopped containers.
```bash
docker container prune
```
### 🟦 rename
Rename a container.
```bash
docker rename {old_container_name} {new_container_name}
```
### 🟦 restart
Restart one or more containers.
```bash
docker restart {container_id}
```
### 🟦 rm
Remove one or more containers.
```bash
docker rm {container_id}
```
### 🟦 run
Create and run a new container from an image.
```bash
docker run {image_name}
```
### 🟦 start
Start one or more stopped containers.
```bash
docker start {container_id}
```
### 🟦 stats
Display a live stream of container(s) resource usage statistics.
```bash
docker stats {container_id}
```
### 🟦 stop
Stop one or more running containers.
```bash
docker stop {container_id}
```
### 🟦 top
Display the running processes of a container.
```bash
docker top {container_id}
```
### 🟦 unpause
Unpause all processes within one or more containers.
```bash
docker unpause {container_id}
```
### 🟦 update
Update configuration of one or more containers.
```bash
docker update {options} {container_id}
```
### 🟦 wait
Block until one or more containers stop, then print their exit codes.
```bash
docker wait {container_id}
```<br>

--- 

Replace `{container_id}`, `{new_image_name}`, `{path_to_file_in_container}`, `{path_to_local_destination}`, `{image_name}`, `{old_container_name}`, `{new_container_name}`, `{command}`, `{options}`, and `{local_tar_file}` with your actual values.