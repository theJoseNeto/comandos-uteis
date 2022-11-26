# Comandos úteis

## Como acessar o terminal de um container docker

```
 sudo docker exec -it <container_id> /bin/bash
```
<br/><br/>
## Como usar o psql dentro do container docker 

```
sudo docker exec -it <container_id> /bin/bash 
```
** Agora dentro do terminal do container:
```
psql -h localhost -p 5432 -U postgres -W
```
