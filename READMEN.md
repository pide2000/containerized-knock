# Dockerized knock 

Dockerized knock is a docker container which pulls the knock software (https://github.com/BentonEdmondson/knock) in the latest version, and automagically converts acsm files to DRM free epub. Why a container? Because you don't have to rely on your environment, only prerequisite is docker/podman. 
#### HOW TO:
Prerequisites: Docker or podman is installed on your system
Run the following command in your shell. 
$: docker run -v [absolute/path/to/your/acsm/files.acsm]:/home/knock/acsm:z --rm
As you can see above, the script searches for *.acsm files and starts knock on every file found inside the specified acsm path. NOTE: No whitespace allowed in filenames. 
