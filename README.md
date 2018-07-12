# docker-php7

Docker containers with php7 mysql redis and composer node
```
docker-compose build
docker-compose run
docker-compose stop
docker-compose start
```
to execute composer

Go to src folder and
```
docker run --rm --interactive --tty --volume $PWD:/app composer require --ignore-platform-reqs --no-scripts PACKAGE-NAME
```

to execute node, npm o yarn
```
docker run --rm --interactive --tty --volume $PWD:/usr/src/app -w /usr/src/app node npm 
docker run --rm --interactive --tty --volume $PWD:/usr/src/app -w /usr/src/app node yarn
docker run --rm --interactive --tty --volume $PWD:/usr/src/app -w /usr/src/app node node
```
