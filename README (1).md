
# Gestion des Etudiants de l'ENSI


Ce projet est une application web full-stack qui permet la création, la lecture, la mise à jour et la suppression de données stockées dans une base de données MySQL en utilisant React Hooks pour le frontend et Spring Boot pour le backend.

L'application offre une interface utilisateur conviviale permettant de créer, lire, mettre à jour et supprimer des données. Elle utilise React Router pour gérer la navigation entre les pages et Axios pour communiquer avec l'API RESTful fournie par Spring Boot.

Le projet est organisé en deux parties : le frontend et le backend. Le dossier "client" contient le code source du frontend, tandis que le dossier "server" contient le code source du backend. Le frontend et le backend sont développés de manière indépendante et communiquent entre eux via l'API RESTful fournie par Spring Boot.



## Front-end
Le frontend de l'application est développé en utilisant la bibliothèque React JS avec la fonctionnalité de hooks pour gérer l'état de l'application et l'interaction avec l'utilisateur. Les hooks React permettent de gérer de manière plus efficace et flexible l'état de l'application, en évitant la nécessité de créer des classes pour les composants.



## Back-end
Le backend est développé en utilisant Spring Boot, qui fournit un cadre pour construire des applications Java rapidement et facilement. La persistance des données est gérée par Spring Data JPA, qui permet de facilement communiquer avec la base de données MySQL.


## API Reference

#### Get all items

Description : Récupérer un élément par son ID

```http
  GET /api/items/${id}
```

| Parameter | Type     | Description                       |
| :-------- | :------- | :-------------------------------- |
| `id`      | `string` | **Required**. Id de l'élément     |


Description : Ajouter un nouvel élément

```http
 POST /api/items
```

| Parameter | Type     | Description                       |
| :-------- | :------- | :-------------------------------- |
| `first name`    | `string` | **Required**. Nom de l'élément.   |
| `last name`    | `string` | **Required**. prénom de l'élément.  |
| `e-mail`    | `string` | **Required**. adresse e-mail de l'élément.  |



Description : Modifier un élément existant

```http
PUT /api/items/${id}
```

| Parameter | Type     | Description                       |
| :-------- | :------- | :-------------------------------- |
| `id`      | `string` | **Required**. Id de l'élément     |




## Installation

Installer la partie Front-end avec npm start

Installer la partie Back-end avec Run As : Spring Boot App


## Screenshots

![App Screenshot](https://scontent.ftun10-1.fna.fbcdn.net/v/t1.15752-9/342873960_982927186033450_1772928000427483735_n.png?_nc_cat=105&ccb=1-7&_nc_sid=ae9488&_nc_ohc=VKtmyEcxHD4AX-A8tTw&_nc_ht=scontent.ftun10-1.fna&oh=03_AdRbIZqc98fk0ChmWwlTRcroulJeBYlDC64IlmComQ4cWA&oe=64787DFA)

Ajouter un etudiant :
![App Screenshot](https://scontent.ftun10-1.fna.fbcdn.net/v/t1.15752-9/341960705_3085337591770046_7330985730456264342_n.png?_nc_cat=100&ccb=1-7&_nc_sid=ae9488&_nc_ohc=N1fqNKiup0gAX8Xda15&_nc_ht=scontent.ftun10-1.fna&oh=03_AdQ5D451TnEFzyFNd_GwYtqzUL2YRicgs3vZRym8OA68ug&oe=64786F6B)

Modifier un etudiant :
![App Screenshot](https://scontent.ftun10-1.fna.fbcdn.net/v/t1.15752-9/342693140_1927402654277003_8769890644360297177_n.png?_nc_cat=104&ccb=1-7&_nc_sid=ae9488&_nc_ohc=cslClr9c9ygAX-eWmYZ&_nc_ht=scontent.ftun10-1.fna&oh=03_AdR59-Bo_Xnz7LnqYWa7NFwbzIRttwAczeOMXoAjwW1OQw&oe=6478777E)

Details de l'etudiant :
![App Screenshot](https://scontent.ftun10-1.fna.fbcdn.net/v/t1.15752-9/343306960_186968180479192_1610326552452828136_n.png?_nc_cat=109&ccb=1-7&_nc_sid=ae9488&_nc_ohc=-LC5c0hsFUUAX-uOWTF&_nc_ht=scontent.ftun10-1.fna&oh=03_AdQLBWySEadm-7TLtC_OmFpME0maPRkHVaC20OmgqU7Mag&oe=6478759B)

