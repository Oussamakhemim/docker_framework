# Framework de visualisation de données avec Docker

## Installation

- construire le container `graphql` :

        $ cd graphql
        $ rm -fr node_modules/
        $ docker build -t graphql .

- démarrer la pile de containers graphql/mongo

        $ cd ..
        $ docker-compose -f stack.yml up -d


