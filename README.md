# Tp Git
gooooooooooooooo

* Vérifiez que vous avez bien *Git* d'installé. Que vous donne la commande suivante dans le terminal :

        git --version

## Github

* [Configurez Git pour GitHub](http://help.github.com/set-up-git-redirect/)
* Dupliquez (*fork*) le projet tp-conduite-projet-2014 dans votre espace.
* Récupérez sur votre disque dur les sources du projet.

        git clone git@github.com:votrecompte/tp-conduite-projet-2014.git

* Indiquez le dépôt Git officiel (le mien) :

        cd tp-conduite-projet-2014
        git remote add official git@github.com:vjousse/tp-conduite-projet-2014.git 

* Combien de *remote* avez-vous ? Comment faire pour le savoir ?

* Sur votre disque dur, ajoutez à la fin de ce fichier le prénom et le nom d'un des membres du binôme. La ligne doit commencer par une étoile. Corrigez la liste pour que la dernière ligne se termine par un point et les autres par des virgules.

* Faites une révision :

        git add README.md
        git commit

* Publiez-la dans votre espace public:

        git push

* Dans GitHub faites une demande d'intégration (*pull request*). 
* Ajoutez le prénom et le nom de l'autre membre du binôme selon les mêmes règles que tout à l'heure.
* Faites une révision :

        git add README.md
        git commit

* Mettez à jour votre disque dur jusqu'à ce que vous récupériez les modifications de quelqu'un d'autre.

        git pull official master

* Réglez le conflit. Modifiez la mise en page de la liste pour qu'elle soit correcte.
* Une fois que le conflit est réglé par une révision, publiez l'ensemble des révisions dans votre espace public :

        git push

* Dans GitHub faites une demande d'intégration (pull request).

## Bitbucket

* Créez un compte sur [Bitbucket](https://bitbucket.org/).

* Essayez de reproduire les étapes vues pour Github.

* Pouvez-vous pousser votre code qui est actuellement sur Github directement sur Bitbucket ? Si oui, comment ?

## Remerciements

Fortement inspiré du [TP d'Aurélien Bénel](https://github.com/benel/TP-Git).
Loulou
et Grougrou
