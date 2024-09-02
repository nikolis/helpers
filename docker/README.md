# Docker helpfull commands 

### View enviroment variables of running container 
docker exec <container_id> env </p>
docker exec e1cc0100d719 env

### Copy from docker containers directories to host machine directories 
docker cp 474175563f1f:/mehungry_umbrella/_build/prod/rel/mehungry_umbrella/  host_machine_dir_name
