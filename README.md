# TP Git

## Prise en main

Refaites les commandes vues en cours.

* Créez un dépôt en local
* Ajoutez des fichiers à votre dépôt
* Envoyez vos fichiers sur un dépôt distant créé sur Github
* Modifiez supprimez des fichiers et faites de nouvelles versions

Vous pouvez vous aider de http://rogerdudler.github.io/git-guide/index.fr.html par exemple (ou sinon, Google est votre ami).

## Github et pull request

Nous allons voir ici comment contribuer à un projet que vous n'avez pas créé.

* [Configurez Git pour GitHub](http://help.github.com/set-up-git-redirect/)
* [Assurez-vous d'avoir vos clés ssh de configurées](https://help.github.com/articles/generating-ssh-keys/)
* Dupliquez (*fork*) le projet tp-conduite-projet dans votre espace (à vous de trouver le bouton sur la page).
* Récupérez sur votre disque dur les sources de votre projet que vous venez de dupliquer dans votre espace.

        git clone https://github.com/votrecompte/tp-conduite-projet.git

* Indiquez le dépôt Git officiel (le mien) :

        cd tp-conduite-projet
        git remote add official https://github.com/vjousse/tp-conduite-projet.git

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

## Gitlab

* Créez un compte sur [Gitlab](https://gitlab.com/).

* Essayez de reproduire les étapes vues pour Github.

* Pouvez-vous pousser votre code qui est actuellement sur Github directement sur Gitlab ? Si oui, comment ?

## Remerciements

Fortement inspiré du [TP d'Aurélien Bénel](https://github.com/benel/TP-Git).


## Liste des forker:

* Titouan Teyssier.
* Valentin Pelloin.
* Trottier Arthur.
