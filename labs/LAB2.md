## Modules

Nous allons à présent créer un module NestJS afin de définir la fonctionnalité de gestion des bières.

- Via la CLI, générez un nouveau module NestJS `BeersModule`.

```shell
nest generate module beers
```

- Externalisez le CRUD (créé précédemment) permettant de gérer les bière dans un contrôleur spécifique : `BeersController`

```shell
nest generate controller beers
```

- Associez ce nouveau contrôleur au module `BeersModule` créé au début de cet exercice.

- Ajoutez au module principal de votre application le module `BeersModule`.
