Bonjour Monsieur Coutant,
Bonjour Monsieur Mathis,

Tout d’abord, je vous remercie pour le temps que vous allez accorder à l’évaluation de ce travail, et je souhaite vous apporter quelques précisions.

Le site est désormais en ligne sur Plesk, accessible à cette adresse :
👉 https://meta-test.kupschus.etu.mmi-unistra.fr/
L’URL redirige automatiquement vers la page de connexion, qui correspond à la page demandée.
Les fichiers ont été commités et poussés sur la branche master, tandis que j’ai laissé la branche main libre, afin de mettre en avant le README et attirer l'attention directement dessus.

-----------------------------------------------------------------------
1. Connexion

La page contient un formulaire de connexion fonctionnel. Les autres liens présents sont pour l’instant non actifs (#), à l’exception du lien « Essai gratuit 14 jours ».
J’ai utilisé le framework Tailwind CSS, que je découvrais à cette occasion. J’ai testé deux méthodes d’intégration : l’installation complète en local (avec les dépendances, fichiers d’entrée/sortie, etc.), et l’utilisation directe via un CDN dans le <head> du fichier de base. Dans un souci de légèreté et comme je ne prévoyais pas de styles personnalisés complexes ou de JavaScript intégré, j’ai finalement opté pour la version CDN. Cela dit, j’ai tout de même testé l’installation locale pour comprendre le fonctionnement de Tailwind, que je ne connaissais pas.

-----------------------------------------------------------------------
2. Fonctionnalités Symfony

Le formulaire a été développé avec le framework Symfony, qui me semble adapté pour ce type de fonctionnalités. J’ai également ajouté un formulaire d’inscription accessible via le lien d'inscription depuis la page de connexion. Ce n’était pas demandé initialement, mais je me suis dit que cela pouvait enrichir l’ensemble et vous permettre, si vous le souhaitez, de tester tout le processus avec vos propres identifiants.

Par défaut, un compte est déjà créé et utilisable pour vos tests :
Identifiant : user@exemple.com
Mot de passe : password

J’ai vu dans les consignes qu’il était demandé d’utiliser user comme identifiant, mais comme le champ dans la maquette est un champ adresse e-mail, j’ai préféré rester cohérente. Je peux bien sûr l’adapter si nécessaire.

➡️ Les mots de passe sont bien hachés, pour des raisons de sécurité.

------------------------------------------------------------------------
3. Organisation du code

J’ai essayé de garder le code aussi clair et structuré que possible.
Vous trouverez quelques commentaires dans le code afin de faciliter la compréhension de certaines parties. L’ensemble est organisé de manière à rester lisible et cohérent avec l’architecture Symfony.

------------------------------------------------------------------------
4. Comportements et messages

Si une erreur survient (identifiants incorrects, formulaire incomplet, etc.), des messages d’alerte apparaissent en rouge ou orange.
Une inscription réussie redirige vers la page de connexion.
Une connexion réussie redirige vers une page « connecté », avec une option de déconnexion.

À noter : les fonctionnalités telles que la connexion via Google ou « se souvenir de moi » ne sont pas implémentées. J’avais également commencé à mettre en place la vérification d’email à l’inscription, mais j’ai choisi de ne pas finaliser cette partie afin de rester dans le périmètre initial demandé.

-----------------------------------------------------------------------
5. Délai de travail

Comme vous pourrez le constater sur le repository GitHub, l’essentiel du travail a été réalisé autour du 8 août. J’avais anticipé votre mail, Monsieur Mathis, afin de m’organiser au mieux. Les pushs suivants correspondent principalement à des ajustements pour améliorer le rendu et mettre le site en ligne.

-----------------------------------------------------------------------
6. Versions techniques utilisées

Node.js : v22.14.0
PHP : v8.3.17
Templating : Twig
Back-end : PHP avec Symfony
Front-end : Tailwind

--------------------------------------------------------------------------
Je précise aussi que je n’ai pas pris le temps de faire le responsive ou l’accessibilité, car ce n’était pas l’objectif principal de l’exercice, et je ne voulais pas y passer plus de temps que nécessaire.

Je reste bien entendu disponible pour toute précision complémentaire, et je vous remercie à nouveau pour votre attention.

Ce projet m’a permis de consolider plusieurs compétences et de découvrir de nouveaux outils. Je tiens à vous faire part de mon réel investissement dans ce travail, dans la perspective de l’alternance que je souhaite vivement intégrer.

Cordialement,
Abigaelle Kupschus
