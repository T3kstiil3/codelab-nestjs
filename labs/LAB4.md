## Validation

* Activez la validation de manière globale à l'application 
* Ajouter les contraintes suivantes sur votre classe Beer
    * `id` doit être un `number`
    * `label` doit être une `string`
    * `description` doit être une `string`, avec un taille entre 10 et 80 caractères
    * `image` doit être une `string`, et se terminer par `.svg` (via un custom validateur)
    * `price` doit être une `number`, compris entre 0 et 100
    * `stock` doit être une `entier`
