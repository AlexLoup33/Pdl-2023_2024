# Projet Développement Logiciel / 2023 - 2024

## Présentation du projet

Ce projet a pour but d'archiver le travail réalisé durant le semestre pour la matière "Projet Développement Logiciel" de la promotion 2023 - 2024 de l'Université de Bordeaux.

## Membres du projet

- [Alexandre Lou-Poueyou](https://github.com/AlexLoup33)

## Organisation du projet

Ce projet est répartie en 2 parties :

- La partie des TP réalisés en cours du semestre et qui sont disponibles dans le dossier `TP`, avec un sous-dossier par TP.

- La partie du projet final, qui est disponible dans le dossier `Projet`.

## Usage

Pour utiliser ce projet, il suffit de cloner le dépôt Git sur votre machine :

```bash
git clone https://github.com/AlexLoup33/Pdl-2023_2024.git
```

#TP1 :

Aller dans le répertoire TP1
```bash
cd TP/TP1/backend
```

Compiler et lancer le démarrage du serveur
```bash
mvn spring-boot:run
```

Rendez vous sur la page http://localhost:8080/ pour voir le résultat, puis essayer les commandes suivantes :
```bash
curl -X GET "http://localhost:8080/images"

curl -X POST -F "file=@<pwd>" "http://localhost:8080/images"

curl -X DELETE "http://localhost:8080/images/<id>"
```

