# launching firefox inside the container

step1 : make a docker file


step2 : build the image

step3 : push to docker hub


in local system use :  docker run -it --rm --net=host  --env="DISPLAY"  --volume="$HOME/.Xauthority:/root/.Xuthority:rw" imagename
step4 : use anywhere to launch the firefox.
