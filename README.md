# TP_DOCKER_1

Mehdi OUZAA

TP1 DOCKER :
1) désactiver Hyper-V
2) Installer Docker ( et WSL2 en même temps ) 
3) vérifier la version sur le terminal avec la commande : docker version
														
4) Vérifier la version du docker avec la commande : docker-compose version
																		
5) Pour exécuter un serveur web sur Docker dans un conteneur Docker et récupérer l'image depuis Docker Hub, on suit les étapes suivante :
- Téléchargez l'image Docker depuis Docker Hub sur votre machine en utilisant la commande « docker pull » :
	

6) Ensuite on éxécute un conteneur à partir de cette image en utilisant la commande « docker run ». On mappe les ports appropriés pour accéder au serveur web depuis ma machine hôte. Par exemple, pour exposer le port 80 du conteneur Nginx sur le port 8080 de votre machine hôte, vous pouvez taper la commande suivante « docker run -d -p 8080:80 nginx » :

7) Pour vérifier si l’on dispose bien d'une image Docker localement sur notre système, on peux utiliser la commande « docker images »
											
