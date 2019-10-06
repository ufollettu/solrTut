
docker-compose up -d --build
docker-compose down
# to load example data
docker exec -it --user=solr solrd bin/post -c cards example/exampledocs/manufacturers.xml