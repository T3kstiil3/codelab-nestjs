## Authentification

* Récupérez la branche `step5`
* Installez les modules NPM nécessaires pour une Authentification JWT
* Via le service `JwtService`, implémentez la méthode `login` du service `UserService`
    * Elle doit retourner un objet `{ expiresIn: 3600, accessToken: `Bearer ${accessToken}`, }`, avec `accessToken` le résultat retourné par la méthode `sign` du service `JwtService`
* Sécurisez la route permettant de créer et mettre à jour des bières
