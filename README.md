# manal-ouakil-enset-adria-test
L'architecture de microservices est une approche de développement logiciel qui divise une application en petits services indépendants, offrant une flexibilité et une évolutivité accrues. Cette application est mise en œuvre en utilisant Spring Boot pour le backend, Angular pour le frontend et Eureka pour la découverte de services.
L'architecture est représentée comme suivant: 
![image](https://github.com/OuakilManal22/manal-ouakil-enset-adria-test/assets/105586177/a71a171f-03e2-42b5-894a-2bd3d468b6f9)

Les services Spring Boot sont organisés en couches : les contrôleurs, les services, les repositories, les entités. Cette structure facilite la gestion et la séparation des préoccupations.
- Repositories et Entités
Les repositories sont responsables de l'accès à la base de données, tandis que les entités représentent les objets stockés.
WALLET-SERVICE:
![image](https://github.com/OuakilManal22/manal-ouakil-enset-adria-test/assets/105586177/f944b671-7061-4f36-8cd4-a7969cc46514)
![image](https://github.com/OuakilManal22/manal-ouakil-enset-adria-test/assets/105586177/1859e930-1194-470c-a495-dc1fc7d81c9b)

![image](https://github.com/OuakilManal22/manal-ouakil-enset-adria-test/assets/105586177/3e69b322-c686-4543-85fd-2afdbf87bad8)
![image](https://github.com/OuakilManal22/manal-ouakil-enset-adria-test/assets/105586177/ab9ce741-4dcb-4977-9e58-9f994beed905)


TRANSFERT-SERVICE:
![image](https://github.com/OuakilManal22/manal-ouakil-enset-adria-test/assets/105586177/451cab05-1968-4a43-9c72-edd761901933)


Services de configuration:
Chaque service s'inscrit auprès du serveur Eureka, ce qui permet aux autres services de le trouver et de communiquer avec lui.
![image](https://github.com/OuakilManal22/manal-ouakil-enset-adria-test/assets/105586177/4d408b9c-6010-44ca-bbc2-1e0b4d3c8d73)
![image](https://github.com/OuakilManal22/manal-ouakil-enset-adria-test/assets/105586177/8ae4aaa4-19b9-4a96-a428-1ce28658bee3)

Nous pouvons maintenant accéder aux services via la gateway:
![image](https://github.com/OuakilManal22/manal-ouakil-enset-adria-test/assets/105586177/2b42f31b-c8a0-496a-affb-eee8e4472985)

http://localhost:8888/TRANSFERT-SERVICE/transferts
![image](https://github.com/OuakilManal22/manal-ouakil-enset-adria-test/assets/105586177/c2935f10-9ca4-44d3-a343-3a093cc4e18e)

http://localhost:8888/WALLET-SERVICE/wallets

![image](https://github.com/OuakilManal22/manal-ouakil-enset-adria-test/assets/105586177/131133aa-70b8-4b69-89ca-fecfcd639af4)

FRONT-END:
![image](https://github.com/OuakilManal22/manal-ouakil-enset-adria-test/assets/105586177/70d1f1eb-46f7-4ab7-8cf0-8e000efba2ef)



