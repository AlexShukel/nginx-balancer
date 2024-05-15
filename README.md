# Load balancer using nginx

docker-compose up -d
docker-compose ps
docker-compose logs -f server-1
docker-compose logs -f server-2
docker-compose logs -f server-3
watch -n 1 curl -s localhost:9999
docker rm -f load-balancer-detailed_server-3_1
