# docker-flask-test2
This project is a simple demonstration of how to containerize a Flask application using Docker. It aims to provide a practical example of deploying a minimal Flask web app inside a Docker container for testing and development purposes.


docker build -t docker-flask-test .
remove all containers and stop -> docker container rm -f$(docker container ls -q)
remove all images -> docker image rm $(docker image ls -aq)