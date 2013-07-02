MoovSimplyIssues
================

This repository contains the issues related to MoovSimply project.

Users with write access to both can reference and close Issues back and forth across the repositories, but those without the required permissions will see references that contain a minimum of information.

For example, if you pushed a commit to the private repository's default branch with a message that read Fixes organization/public-repo#12, the issue would be closed, but only users with the proper permissions would see the cross-repository reference indicating the commit that closed the issue. Without the permissions, a reference still appears, but the details are omitted. 




You can test our application here : http://moovsimply.herokuapp.com/

-------------------------------------------------------------------------------

Nouveautés
- Horaires pour la SNCF (horaires prévisionnels)
- Horaires pour la RATP (horaires temps réel métro)
- Fonction Recherche par station avec autocomplétion
- Filtre pour choisir le moyen de transport (issue #10)
- Action Re-centrage de la carte sur position de l’utilisateur (issue #17)
- Favicon (issue #7)

Fonctionnalités implémentées
- Récupérer tous les moyens de transport public autour de l’utilisateur : affichage sur carte et liste
- Informations temps réels pour les stations Autolib et Vélib : stations ouvertes/fermées, nombre de véhicules disponibles, nombre de bornes disponibles
- Géolocalisation d’une station à partir de la liste des stations

Fonctionnalités en cours
- Horaires pour la RATP (horaires temps réel autre que métro)
- Horaires pour la SNCF (horaires temps réel: lignes L et C)
- Regroupement des stations proches

Fonctionnalités à venir
- Gestion des détails pour les stations superposées
- Gestion des favoris
