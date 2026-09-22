# Un exemple de client / serveur - Flutter / NestJS (2026)

Ce dépôt signale le cours **« Un exemple de client / serveur - Flutter / NestJS (2026) »**, publié à l'adresse :

**https://stahe.github.io/flutter-nestjs-sept-2026/**

## Présentation

Ce document porte vers des technologies actuelles l'application pédagogique **RdvMedecins** (prise de rendez-vous chez le médecin), déjà déclinée dans les cours consacrés à Angular, React et Vue.js. Il en propose ici une version mobile : un client **Flutter** (Dart) qui s'appuie sur un serveur **NestJS** (TypeScript) exposant une API JSON protégée par authentification JWT (rôles ADMIN / USER).

Le document s'adresse à un lecteur qui connaît déjà au moins un framework web (Angular, React ou Vue.js) et découvre Flutter par comparaison : chaque notion Flutter est reliée à son équivalent dans ces frameworks.

Le cours couvre :

- la mise en place de l'environnement de travail (VSCode, SDK Flutter, Android Studio, SDK Android, préparation d'un téléphone Android et d'un émulateur, `flutter doctor`) ;
- l'installation et le lancement du serveur NestJS de l'application (base MySQL, configuration, tests avec un navigateur et avec Postman) ;
- une introduction à Flutter (widgets, `StatelessWidget`/`StatefulWidget`, gestion d'état avec `provider`, langage Dart) ;
- l'étude commentée, fichier par fichier, du client Flutter de l'application RdvMedecins ;
- le portage d'un même code source vers trois familles de cibles : mobile (Android/iOS), bureau (Windows/macOS/Linux) et web, avec les pièges propres au mobile (adresse du serveur, trafic HTTP en clair, écrans étroits) ;
- une conclusion sur ce qui a été construit et les pistes pour aller plus loin.

## Auteurs

- **Auteur principal :** IA Claude (Anthropic)
- **Réviseur :** Serge Tahé

