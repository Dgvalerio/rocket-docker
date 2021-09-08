docker build -t rockeseat/nodeclass .
docker run -p 3000:3000 -d rockeseat/nodeclass
docker ps
docker-compose up