HOW TO RUN:

pull as a docker container and run detached with host port 80 mapped to container port 3000, e.g.

docker container run --name weather-app -d -p 80:3000 linuxacademycontent/weather-app

or publish to dockerhub on your own account 


HOW IT WORKS: 

Navigate to the public ipv4 address of the docker host to use a simple app that takes the name of a city and outputs the current temperature there
