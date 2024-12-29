17Sx | Noa Obringer


# PHPSymfonyEcommerce

## Procédure d'installation

1. Clonez le repository :

   ```bash
   git clone https://github.com/17Sx/PHPSymfonyEcommerce.git
   cd PHPSymfonyEcommerce
   ```

2. Modifiez le fichier `.env` avec vos informations d'accès à la base de données.

3. Installez les dépendances manquantes :

   ```bash
   composer update
   ```

4. Créez la base de données :

   ```bash
   php bin/console doctrine:database:create
   ```

5. Exécutez les migrations pour mettre à jour la base de données :

   ```bash
   php bin/console doctrine:migrations:migrate
   ```

6. Lancez le serveur Symfony :

   ```bash
   symfony server:start
   ```
