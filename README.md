## Description



Le but de ce projet est de développer un système de gestion de contacts
avec authentification, permettant aux utilisateurs de se connecter, de
gérer leurs contacts et d'avoir un accès personnalisé en fonction de leur
profil (administrateur ou invité).
---Côté Client :
 -Se connecter au serveur via un socket en fournissant un login et un
mot de passe.
 - Limiter les tentatives de connexion à 3 fois maximum en cas de mot
de passe incorrect.
  -Récupérer le profil de l'utilisateur (admin ou invité) après une
connexion réussie.
- En tant qu'admin, afficher un menu permettant de saisir des
informations et de les envoyer au serveur pour stockage dans un
fichier "contacts.txt".
---Côté Serveur :
 -Être prêt à recevoir les connexions des clients.
 -Vérifier l'authentification des clients (login, mot de passe) et
personnaliser le menu en fonction du profil (admin ou invité).
 -Afficher l'historique instantané des clients.
 -Gérer les contacts (ajout, modification, suppression, recherche) et afficher les requêtes reçues, traitant les demandes des clients en
conséquence.
