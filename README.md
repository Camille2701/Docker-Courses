# Docker-Courses

les images:
trouver une image https://hub.docker.com/

Télécharger une image

docker pull <image>
voir les images téléchargées

docker images
Clean non used object

docker system prune
supprimer une image

docker rmi <image>
les conteneurs:
run un conteneur a partir d'une image

docker run -d <image>
docker run -p 3000:3000 -d nom_de_votre_image:tag
supprimer un conteneur

docker rm <conteneur>
Voir les conteneurs actifs:

docker ps
Voir tous les conteneurs:

docker ps -a
relancer un conteneur

docker start <conteneur>
Stopper un conteneur:

docker stop <conteneur>
