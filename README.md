# Conduite-De-Projet

Cloner un dépôt existant
Si vous souhaitez obtenir une copie d'un dépôt Git existant — par exemple, un projet auquel vous aimeriez contribuer — la commande dont vous avez besoin s'appelle git clone. Si vous êtes familier avec d'autres systèmes de gestion de version tels que Subversion, vous noterez que la commande est clone et non checkout. C'est une distinction importante — Git reçoit une copie de quasiment toutes les données dont le serveur dispose. Toutes les versions de tous les fichiers pour l'historique du projet sont téléchargées quand vous lancez git clone. En fait, si le disque du serveur se corrompt, vous pouvez utiliser n'importe quel clone pour remettre le serveur dans l'état où il était au moment du clonage (vous pourriez perdre quelques paramètres du serveur, mais toutes les données sous gestion de version seraient récupérées — cf. chapitre 4 pour de plus amples détails).

Vous clonez un dépôt avec git clone [url]. Par exemple, si vous voulez cloner la bibliothèque Git Ruby appelée Grit, vous pouvez le faire de la manière suivante :

$ git clone git://github.com/schacon/grit.git
