# Data Mining Project

Beldjilali Iliès & Folléas Brice

## Get started

Clone the project from his github repository

``
git clone https://github.com/ilies-bel/datamining-project.git
cd datamining-project
``

Lauch the docker-compose which will run the postgres database

``
docker-compose up --build
``
Finally, you can start the python project

``
python3 ./src/main.py
``
## Getting report

Downloaded images are saved 
```
├── _ datamining-project
│   ├── lib
│   │   ...
│   └── src
├── _Assets
└── reports_files
```

## User profile

At firstn users have generated directly from the postgresql database's docker container's creation with a script inserting a set of users. Then, the idea of using a seed funcion like we have done for the creation of the history of the paintings seen by users came to our mind.
The users informations are standard information such as username, email, password and also preferences of the user such as the favorite color, orientation or size.
The main goal of the users information is to be observable during visualization through a graph.

## Recommandation System

Êtes-vous maintenant prêt à recommander des images à un utilisateur ? Dans cette tâche, votre objectif est de construire le système de recommandation. Quelle approche avez-vous décidé de prendre ? Filtrage collaboratif, basé sur le contenu ou une approche hybride ? Pour chaque utilisateur, êtes-vous maintenant en mesure de construire une profil ? Quel type d'information avez-vous utilisé pour établir un profil d'utilisateur profil ? Qu'est-ce qui manque ? Quelles sont les limites de votre proposition ?

## Tests

Getting the recommandation result, we used functional testing to evaluate the relevancy of the recommandation system.
