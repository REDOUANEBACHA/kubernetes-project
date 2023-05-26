# Projet CFA INSTA - Redouane Ait El Bacha
Description
Ce projet, nommé CFA INSTA et développé par Redouane Ait El Bacha, vise à résoudre différents problèmes en utilisant une combinaison de technologies et de fonctionnalités. Il comprend des fichiers de déploiement et de services, ainsi que des scripts pour faciliter le déploiement et l'accès aux services.

# Fichiers
## Fichiers de déploiement
deployment-node-redis.yaml
deployment-redis.yaml
deploy-front.yaml
Fichiers de services
services-front.yaml
services-redis.yaml


## Scripts
Il y a deux scripts disponibles :

=>  deploy-front.sh : Ce script permet de déployer le site React sur Kubernetes en gérant à la fois les déploiements et les services nécessaires.
=>   deploy.sh : Ce script permet de déployer Redis et Redis-code en gérant les déploiements et les services correspondants.

## Utilisation
Pour utiliser ce projet, exécutez les scripts suivants :

Copy code
bash deploy-front.sh
bash deploy.sh


Pour accéder aux déploiements via un navigateur, vous devez trouver les adresses IP et les ports correspondants. Vous pouvez utiliser la commande suivante pour les récupérer :

kubectl get services

## Accès à Redis-node
Pour accéder à Redis-node, recherchez l'adresse IP externe et le port correspondant à la ligne :

### NAME : redis-node-redouane-service

Accès au site React
Pour accéder au site React, recherchez l'adresse IP externe et le port correspondant à la ligne :

NAME : front-site-redouane-service

# Image
## DockerFile
Le fichier Dockerfile utilisé pour créer l'image se trouve dans le dossier /redis-react-master.

## Hébergement
L'image de l'application React est hébergée sur cloud.canister.io. Vous pouvez y accéder en utilisant le lien suivant :

// j'ai utiliser l'image de mon college a couse de manque du temps 

cloud.canister.io:5000/luk34/front-site:1