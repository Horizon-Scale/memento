# Simple memento

Une liste de ressources web sur le développement.

- [Simple memento](#simple-memento)
  - [Outils](#outils)
    - [Repository Git](#repository-git)
    - [Qualité logicielle](#qualit%c3%a9-logicielle)
    - [Déploiement](#d%c3%a9ploiement)
      - [Infrastructure As Code](#infrastructure-as-code)
      - [CI/CD](#cicd)
    - [Tests](#tests)
      - [Tests de charges](#tests-de-charges)
      - [Tests automatisés](#tests-automatis%c3%a9s)
    - [Documentation](#documentation)
  - [Articles](#articles)
    - [DDD - Domain Driven Design](#ddd---domain-driven-design)
    - [TDD - Test Driven Development](#tdd---test-driven-development)
    - [Clean Code](#clean-code)
  - [Livres](#livres)
  - [Podcasts](#podcasts)
  - [Vidéos](#vidéos)

## Outils

### Repository Git

- [Github](https://github.com/)
- [Gitlab](https://about.gitlab.com/product/source-code-management/)
- [Azure Repos](https://azure.microsoft.com/fr-fr/services/devops/repos/) : Repository Git intégré a Azure DevOps

### Qualité logicielle

- [Themis de Promyze](http://promyze.com/themis/) : Themis est une plateforme permettant de diffuser des bonnes pratiques de développement et d'animer une stratégie de clean code.
- [SonarQube](https://www.sonarsource.com/products/sonarqube/) : SonarQube compare les fichiers a une base de règles prédéfinis et lève des erreur si notre nouveau code ne respecte pas ces règles. Doit être installé sur nos propre serveurs.
- [SonarCloud](https://sonarcloud.io/about/) : Version Saas de SonarQube, accessible en ligne, pour les repository Github, Azure DevOps et BitBucket.

### Déploiement

- [AWX - Ansible Tower](https://github.com/ansible/awx/) : AWX est la version open source d'Ansible Tower qui est un orchestrateur de playbooks Ansible.

#### Infrastructure As Code

- [Terraform](https://www.terraform.io/) : Terraform permet de scripter notre infrastructure et de le créer les ressources nécessaire. Disponible sur les cloud AWS, Azure et GCP

#### CI/CD

- [Github Actions](https://github.com/features/actions/)
- [Gitlab](https://about.gitlab.com/product/continuous-integration/)
- [Azure Pipeline](https://azure.microsoft.com/fr-fr/services/devops/pipelines/) : CI/CD intégré a Azure DevOps

### Tests

#### Tests de charges

- [Artillery](https://artillery.io/) : Artillery est un outil open source permettant d'éffectuer des tests de charge d'application web assez simplement via un système de scénarios.

#### Tests automatisés

- [Nightwatch](https://github.com/nightwatchjs/nightwatch/) : Nightwatch est un outil permettant des tests end-to-end de site web via Webdriver en utilisant du Node.Js.

### Documentation

- [Swagger](https://github.com/swagger-api/swagger-ui/) : Swagger génère une documentation sur les principes OpenAPI. Il permet aussi de tester les routes de l'API via une interface. Il existe différente library en fonction du langage de programmation.

## Articles

### DDD - Domain Driven Design

- [POURQUOI IL FAUT LIRE LE RED BOOK DU DDD (DOMAIN DRIVEN DESIGN) !](http://promyze.com/pourquoi-lire-red-book-domain-driven-design/)
- [DDD – La conception qui lie le fonctionnel et le code](http://blog.xebia.fr/2009/01/28/ddd-la-conception-qui-lie-le-fonctionnel-et-le-code/)

### TDD - Test Driven Development

- [Se lancer dans le TDD](http://putaindecode.io/articles/se-lancer-dans-le-tdd/)

### Clean Code

- [A FEW PRINCIPLES OF CLEAN CODE](http://x-team.com/blog/principles-clean-code/)

## Livres

- Clean Code - Robert C.Martin
- Clean Architecture - Robert C.Martin
- Clean Agile - Robert C.Martin

## Podcasts

- [Artisan Développeur](http://artisandeveloppeur.fr/podcast/)

## Vidéos

- [Devoxx FR](https://www.youtube.com/channel/UCsVPQfo5RZErDL41LoWvk0A/videos)
