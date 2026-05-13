# site_covoiturage

## Présentation du projet

Le projet consiste à développer une plateforme web interne de covoiturage destinée aux employés de l'entreprise Planet Monetic. Le site a pour objectif de faciliter l’organisation des trajets entre collègues de manière simple, rapide et efficace. La plateforme devra permettre aux utilisateurs de proposer des trajets ou de rejoindre ceux déjà disponibles afin de réduire les coûts de transport et simplifier les déplacements quotidiens.

Le projet vise avant tout un usage pratique et fonctionnel. L’objectif n’est pas de créer une application complexe ou fortement visuelle, mais plutôt un outil interne professionnel et facile à utiliser.

## Utilisateurs concernés

La plateforme sera principalement utilisée par les employés de Planet Monetic. Chaque utilisateur pourra accéder au site après connexion afin de consulter les trajets disponibles ou proposer ses propres trajets.

Les conducteurs auront la possibilité de créer des trajets en indiquant les informations nécessaires, tandis que les passagers pourront rechercher un trajet correspondant à leurs besoins et réserver une place disponible.

## Fonctionnalités principales

Le site devra proposer un système d’authentification simple permettant aux utilisateurs de créer un compte et de se connecter via leur adresse email professionnelle.

Une fois connecté, l’utilisateur accédera à un tableau de bord affichant les trajets disponibles. Les trajets devront être présentés de manière claire avec les informations essentielles telles que le point de départ, la destination, la date, l’heure et le nombre de places restantes.

Les conducteurs devront pouvoir créer un trajet à l’aide d’un formulaire simple comprenant :

le lieu de départ ;
la destination ;
la date ;
l’heure ;
le nombre de places disponibles.

Les utilisateurs souhaitant rejoindre un trajet pourraient demander une place directement depuis la liste des trajets disponibles. La conducteur pourra donc refuser ou accepter.
Les utilisateurs peuvent aussi annuler leur réservation, bien sur, a précisé le jour avant, et pas le matin même ou sinon envoie de message pour dire qu'ils se debrouillent pour aujourd'hui.

Chaque utilisateur disposera également d’une page personnelle regroupant les trajets créés ainsi que les réservations effectuées.

## Interface et design

L’interface devra rester minimaliste et professionnelle. Le site devra privilégier la simplicité d’utilisation plutôt qu’un aspect visuel complexe. L’objectif est d’obtenir une plateforme légère, claire et intuitive.

Le design devra éviter les animations inutiles, les éléments décoratifs excessifs ou les interfaces trop chargées. Les pages devront afficher uniquement les informations importantes afin de garantir une navigation rapide et efficace.

Le site devra également être responsive afin de fonctionner correctement sur ordinateur et sur mobile.

## Technologies utilisées

Le développement du site pourra être réalisé avec Next.js pour le front-end et Supabase pour la gestion du back-end et de la base de données. Tailwind CSS pourra être utilisé pour créer une interface sobre et rapide à développer.

La base de données devra stocker les informations liées aux utilisateurs, aux trajets publiés ainsi qu’aux réservations effectuées.

## Objectif final

L’objectif final du projet est de créer une plateforme interne simple et fonctionnelle permettant aux employés d’organiser facilement leurs trajets de covoiturage au quotidien. Le site devra être rapide, clair et accessible afin de favoriser son utilisation régulière au sein de l’entreprise.

## précision:

Les trajets seront prit en compte selon où les peronnes habitent.
Ex: si deux personnes habitent dans la même ville, pas loin de l'un et de chez l'autre, l'une des personne ira voir l'autre (souvent la personne la plus loin ira jusqu'a la seconde personne puis feront les trajets).


# Outils nécessaires pour développer la plateforme
## Front-end — Interface du site

Le front-end correspond à toute la partie visible du site, c’est-à-dire ce que les utilisateurs verront et utiliseront directement dans leur navigateur.

Pour ce projet, l’outil recommandé est Next.js
.
Next.js permet de créer des sites web modernes rapidement tout en gardant une bonne organisation du projet. Il est très utilisé pour les applications web professionnelles et fonctionne parfaitement pour un site de covoiturage simple.

Pour le design et la mise en page, vous pouvez utiliser Tailwind CSS
.
Cet outil permet de créer une interface propre et minimaliste sans devoir écrire énormément de CSS. Il est particulièrement pratique pour faire des pages simples et professionnelles rapidement.

Pour le développement du site, il est recommandé d’utiliser Visual Studio Code
 comme éditeur de code.
C’est l’un des logiciels les plus utilisés par les développeurs web grâce à sa simplicité et ses nombreuses extensions.

## Back-end — Gestion des données et du serveur

Le back-end correspond à toute la logique du site qui fonctionne “en arrière-plan”. C’est lui qui gère :

les comptes utilisateurs ;
les trajets ;
les réservations ;
la connexion à la base de données.

Pour simplifier énormément le projet, le meilleur choix est Supabase
.

Supabase fournit :

une base de données PostgreSQL ;
l’authentification ;
le stockage des données ;
des API déjà prêtes.

Cela évite de devoir créer un serveur complexe manuellement avec Node.js ou Express.

Base de données

La base de données servira à stocker toutes les informations du site :

utilisateurs ;
trajets ;
réservations.

Avec Supabase, la base utilisée est PostgreSQL
, une base de données très fiable et largement utilisée dans les applications professionnelles.

Gestion du code et travail en équipe

Pour travailler à plusieurs et sauvegarder le projet, il faudra utiliser Git
 ainsi que GitHub
.

Git permet :

de sauvegarder les modifications ;
revenir à une ancienne version ;
travailler en équipe sans écraser le travail des autres.

GitHub permettra d’héberger le projet en ligne.

Design et maquettes

Avant de développer le site, il est conseillé de créer une maquette pour visualiser les pages et l’organisation de l’interface.

Pour cela, l’outil recommandé est Figma
.

Figma permet :

créer les wireframes ;
concevoir les pages ;
tester l’interface avant le développement.
Hébergement du site

Une fois le projet terminé, le site devra être mis en ligne.

Pour héberger le front-end Next.js, le plus simple est Vercel
.
Vercel est spécialement conçu pour Next.js et permet un déploiement très rapide.

Le back-end et la base de données resteront hébergés directement sur Supabase.

Outils optionnels

Selon l’évolution du projet, certains outils pourront être ajoutés plus tard :

Mapbox
 ou Google Maps Platform
 pour afficher une carte ;
Clerk
 pour une authentification plus avancée ;
Postman
 pour tester les API ;
Notion
 pour organiser le projet et les tâches.
