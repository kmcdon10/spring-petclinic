#Deliverables [50 pts]
For this week, please provide screen captures uploaded and embedded into the SUBMISSIONS.md
file the show:

## DOCKER
[5 pts] Your dockerfile. Please provide a link to this file rather than a screen capture.

[Link to Dockerfile](Dockerfile)

[5 pts] Your running docker instance as shown by a ps command.
![Docker instance running](figures/running_docker_instance.png)

[5 pts] Your browser accessing the main page of the website from your local container.
![Web page running on docker](figures/docker_app_webpage_running.png)

## DOCKER COMPOSE - MYSQL ONLY
[5 pts] The output from the docker-compose up command.
![Docker compose output](figures/docker_compose_up_mysql.png)

[5 pts] Your browser accessing the “Veterinarians” page of the website from your local container when you run the 
application from the host system.
![Vet page running on docker](figures/docker_compose_up_vet_page.png)

[5 pts] A section of the stack trace generated when you attempt to run the application container that has been
 updated to use MySQL.
![Communication error stack trace](figures/docker_container_communication_error.png)

## DOCKER COMPOSE - APP SERVER AND MYSQL
[5 pts] Your updated docker-compose.yml file containing the application server, built from your local Dockerfile,
and the existing MySQL configuration. Please provide a link to this file rather than a screen capture.

[Link to docker-compose](docker-compose.yml)

[5 pts] Your updated application-mysql.properties file containing the URL change for the database server. Please provide
 a link to this file rather than a screen capture.

[Link to application properties](src/main/resources/application-mysql.properties)

[5 pts] The output from the docker-compose up command.
![Docker compose stacktrace](figures/docker_compose_up_terminal_error.png)
I couldn't figure out how to solve the error I was getting when I tried to start it up

[5 pts] Your browser accessing the “Veterinarians” page of the website from your local container.
* Not available, due to the error I encountered above
