How to fire things up
----

add the following files to `./secrets/`
- db_root_password.txt
- db_wp_password.txt

install docker

Initialize swarm
`docker swarm init`

create swarm stack
`docker stack deploy --compose-file ./docker-compose.yml wordpress`
