1. Init Docker Swarm - `docker swarm init`
2. Deploy Docker Swarm - `docker stack deploy -c "*.yml" "swarm-name"`
3. Display Services - `docker service ls`
4. Scale Service - `docker service scale "service-name"=#`
5. Update Service Image - `docker service update --image "docker-image" "service-name"`
6. Stop Docker Swarm - `docker stack rm "swarm-name"`