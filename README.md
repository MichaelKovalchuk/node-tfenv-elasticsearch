# Docker build | login | push

In Dockerfile, put the commands you want, then run: (you’ll want to be in the folder directory, hence the . path)
docker build -t {name of the image that you want to reference later : tag} . e.g. `docker build -t michaelkovalchuk/node-tfenv-elasticsearch:14 .`
Then:
`docker login -u USER -p password`
docker push {name of image} . e.g. `docker push michaelkovalchuk/node-tfenv-elasticsearch:14`
