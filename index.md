---
# You don't need to edit this file, it's empty on purpose.
# Edit theme's home layout instead if you wanna make some changes
# See: https://jekyllrb.com/docs/themes/#overriding-theme-defaults
layout: home
---

![Swift]({{ "/images/Swift.png" | absolute_url }})

# Formation iOS : développement d’applications en langage Swift

## Contenu

Cette formation permet d'acquérir les compétences de base nécessaires au **développement d’applications iOS en Swift**. Elle couvre les cas d’usages que l’on retrouve dans la grande majorité des applications. À l'issue des 5 jours, vous pourrez démarrer le développement d'une application sur iOS.

La formation couvre toutes les notions qui permettent de développer une application de bout en bout : langage Swift, interface graphique, interactions utilisateurs, service web, debug, publication sur l’App Store…

**L’accent est mis sur la mise en pratique**. Il y a environ ⅓ de cours et ⅔ d’ateliers. Le fil rouge des travaux pratiques est la création d’une « vraie » application iOS : un catalogue de films.

L’environnement de développement est **Xcode 9 pour iOS 11**. Les nouveautés de **Swift 4** sont également abordées.

## Durée
La formation dure **5 jours**.

## Public et pré-requis
Cette formation s’adresse aux développeurs qui ont déjà une expérience de la programmation, et connaissent un langage orienté objet (Java, C#...).
Un Mac est nécessaire pour réaliser les travaux pratiques, avec Xcode 9 et cocoapods installés.

## Programme
La formation dure 5 jours, divisés en cours et en 9 ateliers. Le but est de couvrir les cas d’usages que l’on retrouve dans toutes les applications ou presque.
    
Chaque atelier est précédé d’un cours ou d’une démo. L’accent est mis sur les bonnes pratiques issues d’expériences concrètes dans le domaine.

## Résumé du programme
* Atelier 1 - Votre première application : Xcode et Interface builder
* Atelier 2 - Exploration du langage Swift via le parsing de données
* Atelier 3 -  Composants graphiques pour la navigation
* Atelier 4 - Mise en page avec Auto Layout
* Atelier 5 - Appel de services web
* Cours - Persistance de données
* Atelier 6 - Connexion et compte utilisateur - Formulaires et gestion d’erreurs
* Atelier 7 - Debug et amélioration de code
* Cours - Objective-C et Swift dans un même projet
* Cours - Publication d’une application
* Atelier 8 - Cartes et MapView
* Atelier 9 - Géolocalisation et notifications

## Jour 1

### Atelier 1 : votre 1ère application, Xcode et interface builder
L’atelier 1 est une prise en main de l’IDE Xcode, ainsi que d’interface builder, qui est l’outil de création des interfaces graphiques dans Xcode. Une première application iOS simple est créée.

### Atelier 2 : bases du langage Swift
L’atelier 2 est une exploration et prise en main du langage Swift via le parsing de données JSON. Il consiste en la création d’un modèle de données des films.
Le but de l’atelier est de mettre en pratique les spécificités de Swift, notamment les optionals.
Les Codables, nouveauté de Swift 4, sont abordés.

## Jour 2

### Atelier 3 : composants graphiques et navigation
L’atelier 3 a pour but d’explorer les différents types de composants graphiques proposés par le SDK d’iOS. L’organisation de l’app, la navigation, les transitions entre écrans (segues), ainsi que l’affichage des listes (UITableView) sont présentés. La mise en pratique consiste à créer un catalogue des films sous forme de liste, avec un écran de détail.

### Atelier 4 : mise en page avec auto layout
L’atelier 4 permet de prendre en main le système de mise en page d’iOS : Auto Layout. L’application développée au cours de l’atelier 3 est améliorée pour obtenir une interface graphique plus avancée. Auto layout est un outil incontournable pour gérer les problématiques de mise en page des applications iOS, et notamment les différentes tailles d’écran. Les contraintes de layout, ainsi que les notions de safe area, hugging et resistance sont mises en pratique.

## Jour 3

### Atelier 5 : appel de services web et closures
Tout en continuant sur le thème du fil rouge de l’application « catalogue de films », l’atelier 5 permet la connexion à un service web, et de récupérer des vraies données JSON, ainsi que des images.
Pour cela, un « pod » de networking, Alamofire, est utilisé. Ce module est ajouté au projet via le système de gestion de dépendances Cocoapods. Cet atelier permet d’approfondir un point du language Swift, les closures, qui permettent de gérer facilement du code asynchrone. D’autres fonctionnalités plus avancées de Swift sont également présentées pendant le cours.

### Atelier 6 : connexion et comptes utilisateurs, formulaires
Le but de cet atelier est de connecter l’utilisateur à un compte, pour pouvoir ensuite utiliser des web services d’édition de données. Dans cet objectif, un formulaire de connexion est implémenté. L’identifiant et le mot de passe sont ensuite sauvegardés dans la Keychain d’iOS. La Keychain est la base de données cryptée d’iOS, et sert à persister des données de manière sécurisée. Enfin, les notions de feedback utilisateur via un indicateur d’activité et les UIAlertController pour les messages d’erreur, sont mis en pratique.

## Jour 4

### Cours : persistance de données
Ce cours permet de présenter différentes solutions de persistance de données qui peuvent être utilisées dans un projet iOS : UserDefaults, NSKeyedArchiver, Keychain, CoreData, Realm et Firebase. Les avantages et inconvénients de ces différentes solutions sont abordées.

### Atelier 7 : debug et amélioration de code
Le but de cet atelier est d’utiliser les bons outils fournis par Xcode (le debugger et instruments), pour arriver à corriger des bugs dans une base de code existante. Le cours présente des aspects plus avancés mais incontournables des applications : le cycle de vie de l’app, le cycle de vie des UIViewControllers, GCD et la notion threading, la gestion de la mémoire avec ARC et les cycles de référence.

### Cours et démo : Objective-C et Swift dans un même projet
Toujours sur le thème de l’utilisation d’une base de code existante, ce cours présente comment utiliser Objective-C et Swift dans un même projet. Il est en effet courant d’avoir à maintenir un projet iOS qui a été codé en Objective-C, tout en ajoutant les nouvelles fonctionnalités en Swift.
Cours : publication d’une application sur l’App Store
Ce cours présente les différentes étapes de la publication sur l’App Store : tests sur de vrais devices, beta test avec TestFlight, gestion des rapports de crash avec Crashlytics, gestion des langues, itunesconnect, processus de revue par Apple et publication sur l’App Store.

## Jour 5

### Atelier 8 : cartes et MapView
Cet atelier permet de créer une application qui affiche des lieux insolites repérés depuis Google Earth. Le but est de travailler sur les MapView, le positionnement d’informations sur une carte et de réagir aux déplacements d’un utilisateur sur la carte.

### Atelier 9 : géolocalisation et notifications
Cet atelier permet de créer une application qui prévient l’utilisateur quand il entre dans une zone d'interêt. Le but est de mettre en place la géolocalisation et les notifications.
Plusieurs notions essentielles sont abordées : la gestion des droits utilisateurs, les différentes méthodes de géolocalisation (position plus ou moins précise, visite de longue durée, geofencing), ainsi que le debug de la géolocalisation depuis son bureau.

## Les formateurs
Cette formation a été créée par deux développeurs iOS : Cédric Soubrié ([cedric.soubrie@gmail.com](mailto:cedric.soubrie@gmail.com)) 
et Claire Reynaud ([info@clairereynaud.net](mailto:info@clairereynaud.net)), tous deux freelances iOS depuis 6 ans. Forts de leur expérience (les apps sur lesquelles ils ont travaillé totalisent plus de 2 millions de téléchargements), ils ont créé une formation pragmatique, en allant à l’essentiel des bonnes pratiques.

![Formateurs]({{ "/images/photo.png" | absolute_url }})
