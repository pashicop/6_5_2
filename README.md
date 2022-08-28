sudo docker run -d --name elastic --net elastic -p 9200:9200 -p 9300:9300 -e "discovery.type=single-node" -it elasticsearch:7.17.6 /bin/bash
sudo docker run -d -m 512m --name elastic --net elastic -p 9200:9200 -p 9300:9300 -e "discovery.type=single-node" elasticsearch:7.17.6
