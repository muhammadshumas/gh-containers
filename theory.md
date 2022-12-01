# Jobs & Docker Containers
* We can run the jobs not only in the runner but inside the Docker containers
* So the main advantage is since we define the environment (the containers have the environment) we have full control over environment and installed softwares
* On the other hand with runners we have to choose from list of predefined environments (including softwares)

* The containerized job is hosted by the runner
* The steps of the jobs are executed in the container
* We can also create services utility containers used by our steps (example testing, DB)