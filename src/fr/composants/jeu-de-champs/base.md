---
layout: 'layouts/base.njk'
github: https://github.com/cds-snc/gcds-components/tree/main/packages/web/src/components/gcds-fieldset
figma: https://www.figma.com/file/mh2maMG2NBtk41k1O1UGHV/Canadian-Digital-Service%E2%80%A8---GC-Design-System?node-id=2687%3A9818&t=ciEmm7GYyGAY73zZ-0
permalink: false
tags: ['fieldsetFR', 'header']
---

# Jeu de champs <br>`<gcds-fieldset>`

_Autres noms : champ de formulaire._

Un jeu de champs est un groupe de plusieurs composants ou éléments d'un formulaire.

{% docLinks locale stage figma github %}
{% enddocLinks %}

{% componentPreview "Aperçu du composant de jeu de champs" "px-300 pt-400" %}
<gcds-fieldset fieldset-id="fieldset" legend="Légende" hint="Texte explicatif/Exemple de message.">
<gcds-input input-id="form-input" label="Étiquette de champ" hint="Texte explicatif/Exemple de message." size="6">
</gcds-input>
<gcds-select select-id="form-select" label="Étiquette de sélection" hint="Texte explicatif/Exemple de message." default-value="Sélectionnez l'option">

  <option value="option-1">Option 1</option>
  <option value="option-2">Option 2</option>
  <option value="option-3">Option 3</option>
</gcds-select>
</gcds-fieldset>
{% endcomponentPreview %}
