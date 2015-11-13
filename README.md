# Tp Git

## Github et pull request

Nous allons voir ici comment contribuer à un projet que vous n'avez pas créé.

* [Configurez Git pour GitHub](http://help.github.com/set-up-git-redirect/)
* [Assurez-vous d'avoir vos clés ssh de configurées](https://help.github.com/articles/generating-ssh-keys/)
* Dupliquez (*fork*) le projet tp-conduite-projet-2014 dans votre espace (à vous de trouver le bouton sur la page).
* Récupérez sur votre disque dur les sources de votre projet que vous venez de dupliquer dans votre espace.

        git clone https://github.com/votrecompte/tp-conduite-projet-2014.git

* Indiquez le dépôt Git officiel (le mien) :

        cd tp-conduite-projet-2014
        git remote add official https://github.com/vjousse/tp-conduite-projet-2014.git

* Combien de *remote* (dépôt Git distant) avez-vous ? Comment faire pour le savoir ?

* Sur votre disque dur, ajoutez à la fin de ce fichier le prénom et le nom d'un des membres du binôme. La ligne doit commencer par une étoile. Corrigez la liste pour que la dernière ligne se termine par un point et les autres par des virgules.

* Faites une révision :

        git add README.md
        git commit -m "Un joli message"

* Publiez-la dans votre espace public:

        git push

* Vérifiez sur Github que votre commit a bien été envoyé.

* Dans GitHub faites une demande d'intégration (*pull request*) pour m'envoyer vos modficactions.
* Ajoutez le prénom et le nom de l'autre membre du binôme selon les mêmes règles que tout à l'heure.
* Faites une révision :

        git add README.md
        git commit -m "Un autre joli message"

* Mettez à jour votre disque dur jusqu'à ce que vous récupériez les modifications de quelqu'un d'autre. Ne le faites qu'une fois que vous avez pu réaliser la révision (commit) ci-dessus.

        git pull official master

* Vous devriez avoir un conflit lors de la fusion (merge). Réglez ce conflit. Modifiez la mise en page de la liste pour qu'elle soit correcte.
* Une fois que le conflit est réglé par une révision (git add, git commit), publiez l'ensemble des révisions dans votre espace public :

        git push

* Dans GitHub faites une demande d'intégration (pull request).

## Bitbucket

* Créez un compte sur [Bitbucket](https://bitbucket.org/).

* Essayez de reproduire les étapes vues pour Github. Le dépôt sur Bitbucket se situe ici : [https://bitbucket.org/vjousse/tp-conduite-projet-2014](https://bitbucket.org/vjousse/tp-conduite-projet-2014).

* Pouvez-vous pousser votre code qui est actuellement sur Github directement sur Bitbucket ? Si oui, comment ?

## Remerciements

Fortement inspiré du [TP d'Aurélien Bénel](https://github.com/benel/TP-Git).
* Ciron Fabien.
