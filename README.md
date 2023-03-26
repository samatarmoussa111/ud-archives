# Installation

````
# On clone le dépot
git clone https://github.com/samatarmoussa111/ud-archives.git

# On se déplace dans le dossier
cd ud-archives

# On installe les dépendances !
composer install

# On créé la base de données
php bin/console doctrine:database:create

# On exécute les migrations
php bin/console doctrine:migrations:migrate

# On lance le serveur
php bin/console server:run 
