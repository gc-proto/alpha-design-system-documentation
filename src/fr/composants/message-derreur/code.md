---
title: Message d'erreur
layout: 'layouts/component-documentation.njk'
translationKey: 'errormessageCode'
tags: ['errormessageFR', 'code']
date: 'git Last Modified'
---

## Création d'un message d'erreur

Rédigez un message d'erreur pour chaque contrainte de réponse d'un composant, lorsque ce composant est requis.

Tous les composants du système de conception GC sont déjà livrés avec une gestion des erreurs par défaut pour les composants de formulaire requis.

## Codage et accessibilité des messages d'erreur

### Rédigez des messages d'erreur pour faciliter l'accomplissement des tâches.

- Assurez-vous que l'on puisse accéder immédiatement aux contrôles du formulaire associés au libellé auquel le message d'erreur est attaché.
- Rédigez un message d'erreur spécifique pour éviter qu'il s'affiche à nouveau alors que l'utilisateur·rice pensait l'avoir corrigé.
- Ne proposez pas d'étapes supplémentaires. Précisez ce qu'il faut faire pour corriger l'erreur pour que l'on puisse prendre des mesures et soumettre de nouveau — voire revalider — les modifications sans devoir suivre des étapes supplémentaires.
- Fournissez une ou deux solutions pour corriger l'erreur, plutôt qu'une démarche en plusieurs étapes.

### Rédigez un message d'erreur classique

Fournissez une orientation simple et rapide qui se situe dans le contexte et interrompt le déroulement de l'action le moins possible par :

- Un repérage clair de l'erreur;
- Une définition de l'erreur qui ne signale pas les actions de l'utilisateur·rice comme la source du problème;
- Un appel à l'action spécifique et exploitable.

La personne qui reçoit un message d'erreur doit :

- Trouver l'erreur et être en mesure d'y avoir accès;
- Savoir quoi faire pour la corriger;
- Être en mesure de réaliser des modifications;
- Soumettre à nouveau les modifications ou les valider sans avoir à remplir à nouveau le formulaire complet.

{% include "partials/getcode.njk" %}

<iframe
  title="Survol des propriétés et des évènements relatifs à gcds-error-message."
  src="https://cds-snc.github.io/gcds-components/iframe.html?viewMode=docs&demo=true&singleStory=true&id=components-error-message--events-properties"
  width="1200"
  height="1000"
  style="display: block; margin: 0 auto;"
  frameBorder="0"
  allow="clipboard-write"
></iframe>
