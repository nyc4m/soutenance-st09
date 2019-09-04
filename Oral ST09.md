---
title: Soutenance ST09 Siclo Mobile
author: Baptiste Prunot
date: 5 septembre 2019
theme: moon
---

# Siclo Mobile


## L'entreprise

![source : siclo-mobile](images/siclo.png){width=400px}

::: notes
+ Studio de developpement
+ une dizaine de personne
+ fondée par deux ingénieurs français
:::

##  Localisation

![source : google maps](images/map.png)

::: notes
 + financièrement c'est intéressant
 + culturellement aussi
:::

## Siclo ? Xích lô !

![source : wiktionnary vietnam](images/xichlo.jpg){height=400}

# Jobigo

## Principe
::::::{.columns}
:::{.column width="50%"}
![source : playstore](images/jobigo.png){width=500}
:::
:::{.column width="50%"}
![source : jobigo](images/jobigo_app_1.jpg){height=450}
:::
::::::

::: notes

   + aider des chercheurs d'emploi à trouver un emploi

   + faciliter la publication d'offres par les employeurs

   + établir un système de chat

:::

## Participation

![source : pixabay](images/notification.png){width=450}

::: notes

    + fin de projet
    + notifications

:::

## Type de notifications

::: incremental
+ Offre d'emploi
+ Candidature
+ Acceptation
+ Nouveau message
:::

## Fonctionnement

![](images/notification_fonctionnement.png)

::: notes
 + deux fournisseurs : APNS et Google
 + expliquer le fonctionnement
  + verifier que l'utilisateur a un token
  + vérifier qu'il est d'accord pour recevoir des notifications
:::

## Technologies 

::::::{.columns}

:::{.column width="30%"}
![source : api-platform](images/api-platform.png)
:::

:::{.column width="50%"}
![source : le monde informatique](images/docker.png)
:::

::::::

# SITA - Smart ULD

##  L'entreprise

![source : sita](images/sita.png)

::: notes
 + Société Internationale de Télécommunications Aeronautique
 + Formée par toutes les grosses compagnies aeriennes européenes
 + standardisation des télécomunication dans l'aviation
:::

## Projet

![source : wikipedia](images/uld.jpg){width=600px}

::: notes
 + Capteur dans les uld (Unit Load Device)
 + tracking (temperature, geo, pression, choc)
 + second prix au Cargo Innovation Awards 2019
:::

## Pourquoi ?

::: incremental
 - Prototype non fiable ❌ 
 - Maintenance compliquée ❌ 
:::

::: notes
   1. premier prototype pas très performant en javascript (stagiaire)
   1. flow de données important, argent en jeu
:::

## Principe

![version simplifiée de l'architecture](images/micro_services.svg){}

::: notes

   + microservices
   + réécriture en typescript
   + système de queue

:::

## Technologies


::::::{.columns}

:::{.column width="33%"}
  ![source : wikipedia](images/node.png)
:::

:::{.column width="33%"}
  ![source : github de microsoft](images/typescript.png){height=300px}
:::

:::{.column width="33%"}
  ![source : vectorlogo](images/rabbitmq.svg){height=300px}
:::

::::::

## Résultats

::: notes
+ un programme qui fonctionne
+ une architecture plus maintenable
+ un code plus clair
:::

# Mynabes

## Projet

![source : mynabes](images/mynabes.png)

::: notes

+ rapprocher les voisins
+ demander un service
+ faire les courses de quelqu'un d'autre

:::

## Fonctionnement

::: incremental
 + Fonctionnement par voisinnage 📍
 + Fil d'actualité 📰
 + Système de favoris ❤️
 + Discussion instantanée 📱
 + Fonctionnalité de recherche 🔎
:::

## Technologie

![](images/laravel.jpg)

# Bilan
    
# Questions ?
