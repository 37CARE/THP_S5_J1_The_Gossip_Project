# README

The Gossip Project in Rails

This README would normally document whatever steps are necessary to get the application up and running.

This applicaiton is made with love by Alexandre Labonne (@Lab's) and Brice Jones (@brice) from Toulouse.

Ruby/rails version

version ruby:
$ ruby --version ruby 2.5.1p57 (2018-03-29 revision 63029) [x86_64-darwin17]

version rails:
$ rails --version Rails 5.2.3

version PostGreSQL:
$ psql --version psql (PostgreSQL) 11.2

System dependencies

base de données PostGreSQL
Pensez à changer le database.yml pour mettre un user adapté à votre contexte. Cela pourrait empecher le db:migrate !
Configuration

faire un git clone https://github.com/37CARE/THP_S5_J1_The_Gossip_Project
bundle install
faire un rails db:create 
faire un rails db:migrate 
faire un rails db:seed
How to run the test suite

Lancer le serveur avec $ rails server
http://localhost:3000==

L'application permet:

d'afficher les potins en card Bootstrap avec l'item du menu Home: l'auteur et le titre du ragôt.

chaque card permet d'avoir le profil utilisateur et
le contenu du potin
l'item du menu Team affiche les membres de la team Toulouse

l'item du menu Contact affiche les contacts pour nous joindre.

une page cachée est accessible : en saisissant l'URI suivante: http://localhost:3000/welcome/votre_nom où 'votre_nom' est un texte libre...