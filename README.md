# App ruby AirBnB Dog - THP

## Pour installer et tester

Il suffit de télécharger ou de cloner le répository
`$ git clone https://github.com/AtheDev/App_ruby_AirBnB_Dog.git`

Lance la commande `$ bundle install` pour installer les gems nécessaires au bon fonctionnement de l'application.

Mettez à jour votre structure de BDD avec la commande: `$ rails db:migrate` . La base de données n'est pas téléchargée sur github, il est donc nécessaire de lancer les différentes migrations.

Ajoutez des données dans votre BDD avec la commande: `$ rails db:seed` .

Ouvre la console de rails avec la commande `$ rails c` et verifiez que les données ont bien été créées en utilisant la gem table_print:
  -> tp Dog.all
  -> tp Dogsitter.all
  -> tp City.all
  -> tp Stroll.all
  -> tp JoinTableDogStroll.all
