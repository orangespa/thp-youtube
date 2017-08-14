Projet

Dans ce projet, tu vas devoir recréer la page d'une vidéo Youtube. C'est une excellente introduction à l'insertion de média, et cela va te redonner des bases solides en mise en page.

Tu vas donc de voir insérer une vidéo qui est embed, ainsi que les images qui réprésentent les aperçus sur la barre latérale de YouTube. Il y a beaucoup d'élément qui sont fait avec du JavaScript, que tu n'as pas à faire (on verra JS la semaine prochaine). Dès qu'un élément réagit au click, c'est du JS.

Aussi, pas besoin de faire le site en mobile friendly. On verra lundi prochain comment le faire responsive. Pour le moment concentre-toi sur la mise en page.
Les étapes

On va t'aider dans les étapes :

    fais un nouveaux projet rails youtube (tu as cru que tu allais esquiver Rails ? :sunglasses:)
    controller home, methode index, toussa toussa
    essaie de voir l'architecture de la page : quels seront les divs qui vont être ensemble, comment seront regroupés les principaux éléments
    fais les divs, positionne-les, donne-leur la bonne taille.
        Conseil : background-color sur un div est une arme redoutable pour savoir leur forme, taille, position
    maintenant fais les éléments dans l'ordre suivant :
        la vidéo principale, dans laquelle tu embed une vidéo de ton choix
        la barre latérale, dans laquelle tu vas mettre les images des thumbnails des vidéos, et le texte sur le côté (titre, auteur, etc)
        le titre de la vidéo principale, la description
    Tu commences à avoir une page sympa. Tu peux maintenant mettre un commentaire ou deux pour la forme, et t'attaquer au header
    Si tu te sens très chaud, tu peux faire l'un de ces deux bonus-stage :
        utilise un Youtube Downloader pour télécharger une vidéo de ton choix (courte, pour pas qu'elle pèse 500Mo), puis au lieu d'embed pour la vidéo principale une vidéo Youtube, arrange-toi pour héberger la vidéo et la jouer avec un lecteur média
        quand tu hover les thumbnails des vidéos de la barre latérale, tu constates qu'il y a un petit gif qui donne un aperçu de la vidéo en cours. Arrange-toi pour que ce gif apparaisse dans ton site
    tu n'as plus qu'à push sur heroku ta merveille de site internet :fire:
