<h1 align="center">🌿Twig : moteur de template</h1>

### C'est quoi Twig ?
Twig est moteur de modèles flexible, rapide et sécurisé pour PHP. Il permet de séparer la logique mêtier `PHP` de la logique design `HTML/CSS`.

Les principales caractéristiques sont...
- Rapide : Twig compile les modèles en code PHP optimisé. La charge de travail par rapport au code PHP standard a été réduite au minimum.
- Sécurisé : Twig dispose d'un mode sandbox pour évaluer le code de modèle non fiable. Cela permet d'utiliser Twig comme langage de modèle pour les applications où les utilisateurs peuvent modifier la conception du modèle.
- Flexible : Twig s'appuie sur un analyseur lexical et syntaxique flexible. Cela permet au développeur de définir ses propres balises et filtres personnalisés, et de créer son propre DSL.

### Prérequis
Twig 3.x nécessite au moins PHP 8.1.0 pour fonctionner.

### Syntaxe de base :
- Variable `{{ variable }}`,
- Filtres `{{ variable | filtre }}`,
- Structures de contrôle `{% if %} `
