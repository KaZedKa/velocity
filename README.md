Docker image to run velocity server. 
To use run: docker run -d kazedka/velocity -p 25565:25565 -name velocity 

Can edit the config by doing: 
1. docker exec velocity /bin/bash
2. once inside the docker container shell, use "nano velocity.toml"

You also have to edit the forwarding.secret file to have your secret key for the paper server. 
