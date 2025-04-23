## join my servers

### Cloud server
boris-mc0.aternos.me

## single server
docker run -d \
  -e EULA=TRUE \                     
  -e ONLINE_MODE=FALSE \              
  -e VERSION=1.20 \                   
  -p 25565:25565 \                     
  --name mc0 \               
  itzg/minecraft-server               

## multi servers
- cd /multi
- docker-compose up -d

## mc commands
docker exec -i <ID> rcon-cli

## host
127.0.0.1:25565
