Here’s the **same complete Docker command list**, organized, so it’s easier to remember 👇

---

# 🧾 Docker Basics & Info

docker --version — we use it to check the installed Docker version

docker info — we use it to display system-wide Docker information

docker help — we use it to list all Docker commands

---

# 📦 Image Management

docker pull image_name — we use it to download an image from Docker Hub

docker push image_name — we use it to upload an image to a registry

docker search image_name — we use it to search images in Docker Hub

docker images — we use it to list all local images

docker image ls — we use it to list images (new syntax)

docker rmi image_id — we use it to remove an image

docker image prune — we use it to remove unused images

---

# 🏗️ Image Building

docker build -t image_name . — we use it to build an image from a Dockerfile

docker build -f Dockerfile.dev -t image_name . — we use it to build using a specific Dockerfile

docker history image_name — we use it to view image layers

docker inspect image_name — we use it to view detailed image info

---

# 🚀 Container Run & Creation

docker run image_name — we use it to create and start a container

docker run -d image_name — we use it to run container in detached mode

docker run -it image_name /bin/bash — we use it to run an interactive container

docker run -p 8080:80 image_name — we use it to map ports

docker run --name container_name image_name — we use it to assign a container name

docker run -v host_path:container_path image_name — we use it to mount volumes

docker run --env VAR=value image_name — we use it to pass environment variables

docker run --restart always image_name — we use it to set restart policy

---

# 📊 Container Lifecycle

docker ps — we use it to list running containers

docker ps -a — we use it to list all containers

docker start container_id — we use it to start a stopped container

docker stop container_id — we use it to stop a container

docker restart container_id — we use it to restart a container

docker pause container_id — we use it to pause a container

docker unpause container_id — we use it to resume a container

docker rm container_id — we use it to remove a container

docker container prune — we use it to remove all stopped containers

---

# 🔍 Container Inspection & Monitoring

docker exec -it container_id /bin/bash — we use it to access container shell

docker logs container_id — we use it to view container logs

docker logs -f container_id — we use it to follow logs live

docker attach container_id — we use it to attach terminal to container

docker top container_id — we use it to view running processes

docker stats — we use it to monitor container resource usage

docker inspect container_id — we use it to view detailed container info

---

# 🌐 Network Management

docker network ls — we use it to list networks

docker network create network_name — we use it to create a network

docker network inspect network_name — we use it to inspect a network

docker network rm network_name — we use it to delete a network

docker network connect network_name container — we use it to connect container to network

docker network disconnect network_name container — we use it to disconnect container

---

# 💾 Volume Management

docker volume ls — we use it to list volumes

docker volume create volume_name — we use it to create a volume

docker volume inspect volume_name — we use it to inspect volume

docker volume rm volume_name — we use it to remove a volume

docker volume prune — we use it to remove unused volumes

---

# 🔐 Registry & Image Transfer

docker login — we use it to authenticate to a registry

docker logout — we use it to log out from a registry

docker tag image_name repo/image_name — we use it to tag an image

docker save image_name -o file.tar — we use it to export an image

docker load -i file.tar — we use it to import an image

---

# 🧹 System Cleanup & Diagnostics

docker system df — we use it to view disk usage

docker system prune — we use it to clean unused data

docker system prune -a — we use it to remove all unused images and containers

docker events — we use it to view Docker events in real time

---

# 🧩 Docker Compose

docker compose version — we use it to check compose version

docker compose up — we use it to create and start services

docker compose up -d — we use it to run services in background

docker compose down — we use it to stop and remove services

docker compose ps — we use it to list compose containers

docker compose logs — we use it to view logs

docker compose build — we use it to build services

docker compose restart — we use it to restart services

docker compose exec service_name bash — we use it to access a service

---
