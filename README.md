# Sonarqube -> docker-compose

Este es un docker-compose para levantar sonar en local.

Comando para iniciar sonar:

docker-compose up –d

** [-d] se utiliza para no dejar pegada la consola.

Un error común es un problema de memoria al levantar, se soluciona con el siguiente comando:

sudo sysctl -w vm.max_map_count=262144

** El número del final debe ser el que te indique el error en consola.
