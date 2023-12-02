# Forum_Chat_AES_Security

** Partie 1 : AESCrypto - Chiffrement et Déchiffrement :**
Nous utilisons la classe AESCrypto pour gérer les opérations de chiffrement et de déchiffrement.
Cela inclut la méthode encrypt pour chiffrer un message et la méthode decrypt pour le déchiffrer.
De plus, la méthode generateSecretKey est utilisée pour générer une clé secrète AES.

**Partie 2 : ChatServerImpl - Serveur RMI :**
La classe ChatServerImpl joue un rôle central dans le projet en tant que serveur RMI (Remote
Method Invocation) qui orchestre la communication entre les clients connectés. Son objectif
principal est de fournir une plateforme où les clients peuvent s'enregistrer, échanger des messages
de manière sécurisée, et recevoir des mises à jour en temps réel.

**Partie 3 : ChatClientImpl - Client RMI avec Interface**
Graphique :
La classe ChatClientImpl représente le client RMI avec une interface graphique (GUI). Son rôle
est de permettre à un utilisateur de se connecter au serveur, d'envoyer des messages de manière
sécurisée, et d'afficher les messages reçus dans une interface utilisateur conviviale.
