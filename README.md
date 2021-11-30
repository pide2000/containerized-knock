# Dockerized knock 

Dockerized knock is a docker container which pulls the knock software (https://github.com/BentonEdmondson/knock) in the latest version, and does its thing. Why a container? Because you don't have to rely on your environment. The only prerequisite is docker/podman. 
#### HOW TO:
Prerequisites: Docker or podman is installed on your system
Run the following command in your shell.    

`$: docker run -v absolute/path/to/your/acsm/files:/home/knock/acsm:z --rm`

The script searches for *.acsm files inside the specified path and calls knock for every file found. NOTE: No whitespace allowed in filenames. 
