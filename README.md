# Simple memento

[![Actions Status](https://github.com/Horizon-Scale/memento/workflows/Markdown%20Lint%20with%20Node%20CI/badge.svg)](https://github.com/Horizon-Scale/memento/actions)

Une liste de ressources web sur le développement.

- [Simple memento](#simple-memento)
  - [Outils](#outils)
    - [Editeurs et IDE](#editeurs-et-ide)
    - [Repository Git](#repository-git)
    - [Qualité logicielle](#qualit%c3%a9-logicielle)
    - [Déploiement](#d%c3%a9ploiement)
      - [Infrastructure As Code](#infrastructure-as-code)
      - [CI/CD](#cicd)
    - [Ressources Web](#ressources-web)
    - [Tests](#tests)
      - [Tests de charges](#tests-de-charges)
      - [Tests automatisés](#tests-automatis%c3%a9s)
      - [Autre](#autre)
    - [Virtualisation et Containerisation](#virtualisation-et-containerisation)
    - [Documentation](#documentation)
  - [Articles](#articles)
    - [DDD - Domain Driven Design](#ddd---domain-driven-design)
    - [TDD - Test Driven Development](#tdd---test-driven-development)
    - [Design Pattern](#design-pattern)
    - [Clean Code](#clean-code)
    - [Containerisation](#Containerisation)
    - [Liste de ressources development web](#liste-de-ressources-development-web)
  - [Livres](#livres)
  - [Podcasts](#podcasts)
  - [Vidéos](#vid%c3%a9os)
  - [Autres Ressources](#autres-ressources)

## Outils

### Editeurs et IDE

- [Visual Studio](https://visualstudio.microsoft.com/fr/vs/) : IDE pour
développer en C#, VB, F# et toute la plateforme .NET
- [Visual Studio Code](https://code.visualstudio.com) : Editeur de texte se
rapprochant d'un IDE, peut etre utilisé pour n'importe quel langage
- [IntelliJ IDEA](https://www.jetbrains.com/idea/) :
IDE pour développer en Java/Kotlin ainsi que toute la plateforme JVM.
- [Pycharm](https://www.jetbrains.com/pycharm/) : IDE pour développer en python

### Repository Git

- [Github](https://github.com/)
- [Gitlab](https://about.gitlab.com/product/source-code-management/)
- [Azure Repos](https://azure.microsoft.com/fr-fr/services/devops/repos/) :
Repository Git intégré a Azure DevOps

### Qualité logicielle

- [Themis de Promyze](http://promyze.com/themis/) : Themis est une plateforme
permettant de diffuser des bonnes pratiques de développement et d'animer une
stratégie de clean code.
- [SonarQube](https://www.sonarsource.com/products/sonarqube/) : SonarQube
compare les fichiers a une base de règles prédéfinis et lève des erreur si notre
nouveau code ne respecte pas ces règles. Doit être installé sur nos propre serveurs.
- [SonarCloud](https://sonarcloud.io/about/) : Version Saas de SonarQube,
accessible en ligne, pour les repository Github, Azure DevOps et BitBucket.

### Déploiement

- [AWX - Ansible Tower](https://github.com/ansible/awx/) : AWX est la version
open source d'Ansible Tower qui est un orchestrateur de playbooks Ansible.

#### Infrastructure As Code

- [Terraform](https://www.terraform.io/) : Terraform permet de scripter notre
infrastructure et de le créer les ressources nécessaire. Disponible sur les
cloud AWS, Azure et GCP.

#### CI/CD

- [Github Actions](https://github.com/features/actions/)
- [Gitlab](https://about.gitlab.com/product/continuous-integration/)
- [Azure Pipeline](https://azure.microsoft.com/fr-fr/services/devops/pipelines/)
: CI/CD intégré a Azure DevOps

### Ressources Web

- [CodePen](https://codepen.io/picks/pens/) : CodePen est une communauté en
ligne et un éditeur permettant de tester et de présenter des extraits de code
TML, CSS et JavaScript créés par les utilisateurs.

- [ColorHunt](https://colorhunt.co/)

- [Pesticide](https://chrome.google.com/webstore/detail/pesticide-for-chrome/bblbgcheenepgnnajgfpiicnbbdmmooh)
: extention chrome pour visualiser les boxs CSS

### Tests

#### Tests de charges

- [Artillery](https://artillery.io/) : Artillery est un outil open source
permettant d'éffectuer des tests de charge d'application web assez simplement
via un système de scénarios.

#### Tests automatisés

- [Nightwatch](https://github.com/nightwatchjs/nightwatch/) : Nightwatch est un
outil permettant des tests end-to-end de site web via Webdriver en utilisant du Node.Js.

#### Autre

- [Postman](https://www.getpostman.com/): Postman est un outil permettant
d'envoyer toutes sortes de requêtes sur une API.

### Virtualisation et Containerisation

- [Docker](https://docker.com): Docker permet de créer, gérer et lancer des
applications containerisées.
- [Kubernetes](https://kubernetes.io): Kubernetes est un orchestrateur de
container disposant de nombreuses fonctionnalités.
- [Traefik](https://traefik.io): Traefik est un outil permettant de faire du
reverse-proxy et du loadbalacing.
- [CoreOS](https://coreos.com/): Une distribution linux
pour le cloud basée que sur la technologie des conteneurs.
- [OpenShift](https://www.openshift.com/):
Une solution PaaS privée et openSource permettant de construire,
déployer et executer des applications dans des containers.

### Documentation

- [Swagger](https://github.com/swagger-api/swagger-ui/) : Swagger génère une
documentation sur les principes OpenAPI.
Il permet aussi de tester les routes de l'API via une interface.
Il existe différente library en fonction du langage de programmation.

- [SoapUI](https://www.soapui.org/downloads/soapui.html) :
Pour faire toute sorte de tests sur une/des API(s).

- [OpenAPI](https://www.openapis.org/)

- [OpenAPI-to-Postman](https://github.com/postmanlabs/openapi-to-postman) :
Plugin permettant de convertir des specifications OpenAPI en collections Postman.

- [OpenAPI-generator](https://github.com/OpenAPITools/openapi-generator) :
Outil permettant de génerer des clients (Java, python php...) à partir d'une
spécification OpenAPI.

- [Docusaurus](https://docusaurus.io) :
Docusaurus est un outil permettant de concevoir,
déployer et maintenir des site de documention.

## Articles

### DDD - Domain Driven Design

- [POURQUOI IL FAUT LIRE LE RED BOOK DU DDD (DOMAIN DRIVEN DESIGN) !](http://promyze.com/pourquoi-lire-red-book-domain-driven-design/)
- [DDD – La conception qui lie le fonctionnel et le code](http://blog.xebia.fr/2009/01/28/ddd-la-conception-qui-lie-le-fonctionnel-et-le-code/)

### TDD - Test Driven Development

- [Se lancer dans le TDD](http://putaindecode.io/articles/se-lancer-dans-le-tdd/)

### Design Pattern

- [Design Pattern Factory & Abstract Factory](https://www.codingame.com/playgrounds/36103/design-pattern-factory-abstract-factory/introduction)
: Article sur la mise en place d'un design pattern factory
 & abstract Factory de manière ludique.

- [Difference entre MVC et MVP](https://progaide.com/question/2056-que-sont-mvp-et-mvc-et-quelle-est-la-diff-rence)
: Question/réponses autour de la question de la différence
entre les design patterns MVC et MVP.

### Clean Code

- [A FEW PRINCIPLES OF CLEAN CODE](http://x-team.com/blog/principles-clean-code/)

### Containerisation

- [CoreOS](https://blog.octo.com/a-la-decouverte-de-coreos/): Pour débuter avec
CoreOs.

- [OpenShift](https://blog.octo.com/openshift-3-le-paas-prive-avec-docker/):
Pour debuter avec openshift.

### Liste de ressources development web

- [LISTE DE RESSOURCES DEVELOPMENT WEB](https://www.appbrewery.co/p/web-development-course-resources/)

## Livres

- Clean Code - Robert C.Martin
- Clean Architecture - Robert C.Martin
- Clean Agile - Robert C.Martin

## Podcasts

- [Artisan Développeur](http://artisandeveloppeur.fr/podcast/)

## Vidéos

- [Devoxx FR](https://www.youtube.com/channel/UCsVPQfo5RZErDL41LoWvk0A/videos)

## Autres Ressources

- [Github Student Pack](https://education.github.com/pack)
