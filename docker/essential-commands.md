# Docker Essential Commands
Simply running the command docker in the terminal allows you to check out all the commands that are used

1. Check Docker Version <br>
'''bash <br>
docker --version

2. Pull an image from Docker Hub <br>
docker pull nginx

3. List Local Docker Hub <br>
docker images

4. Run a Container (from Image) <br>
docker run nginx

5. Run + Expose Port <br>
docker run -d -p 8080:80 nginx

6. List Running Containers <br>
docker ps

7. List all Containers (stopped too) <br>
docker ps -a 

8. Stop a running Container <br>
docker stop <container_id_or_name>

9. Remove a Container <br>
docker rm <container_id_or_name>

10. Remove an Image <br>
docker rmi <image_id_or_name>

## BONUS: Inspecting, Logs and Cleanup
1. Inspecting a Container <br>
docker inspect <container_id_or_name> <br>
2. View Logs from a Container <br>
docker  logs <container_id_or_name> <br>
3. Remove all Stopped Containers <br>
docker container prune <br>
4. Remove all Unused Images <br>
docker image prune <br>
5. Full CLean Sweep <br>
docker system prune <br>


## Useful Flags to Remmeber
1. -d : detached mode (runs in background) <br>
2. -p : map ports host:container <br>
3. --name : give a custom name <br>
4. -v : mount volume host_dir:container_dir <br>
5. -it : interactive terminal (good for bash) 


## Pro Tips :
>> Tag images when building: <br>
docker build -t myapp:v1 . <br>
>> Use .dockerignore like .gitignore to skip files in build. <br>
>>Keep images clean with prune often — they pile up fast!
