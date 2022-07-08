# Projet-API

1/La methode GET pour afficher les informations sur un joueur: https://apiapplication1.herokuapp.com/api/v1/stats/4

Reponse
{
    "id": 4,
    "Nom_du_joueur": "Serge Gakpe",
    "Annees_dexpériences": 17,
    "Buts_marqués": 10,
    "Buts_ratés": 7
}



2/La methode PUT pour modifier des informations d'un joueur: https://apiapplication1.herokuapp.com/api/v1/stats/300

Requete
{
    "id": 300,
    "Nom_du_joueur": "Alexis Romao",
    "Annees_d'expériences": 20,
    "Buts_marqués": 9,
    "Buts_ratés": 9
}


 Reponse
{
    "id": 300,
    "Nom_du_joueur": "Alexis Romao",
    "Buts_marqués": 9,
    "Buts_ratés": 9
}



3/La methode POST pour Insérer : https://apiapplication1.herokuapp.com/api/v1/stats/

Requete
{
    "id": 4,
    "Nom_du_joueur": "Serge Gakpe",
    "Annees_dexpériences": 17,
    "Buts_marqués": 17,
    "Buts_ratés": 7
}

Reponse
{
    "id": 4,
    "Nom_du_joueur": "Serge Gakpe",
    "Annees_dexpériences": 17,
    "Buts_marqués": 17,
    "Buts_ratés": 7
}



4/La methode DELETE pour supprimer des informations : https://apiapplication1.herokuapp.com/api/v1/stats/2

Requete
{
    "id": 2,
    "Nom_du_joueur": "Zinedine Zidane",
    "Annees_d'expériences": 20,
    "Buts_marqués": 15,
    "Buts_ratés": 6
}

Réponse
 Aucune réponse car l'information a été supprimée.


