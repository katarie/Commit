Pour activer un dossier comme repository Git, il suffit de se placer dans ce dossier avec le Terminal puis d'utiliser la commande git init. 

Pour gérer un repository, Git génère un index de tous les fichiers dont il doit faire le suivi. Lorsque vous créez un fichier dans un repository, vous devez donc l'ajouter à l'index Git à l'aide de la commande git add nomDeVotreFichier.extension. Par exemple :

git add checklist-vacances.md

Pour gagner du temps, vous pouvez ajouter tous les fichiers dans le répertoire courant en tapant

git add .

dans la console. Évidemment, faites bien attention quand vous utilisez ce raccourci à ne pas rajouter trop de fichiers à l'index.

Lorsque vous modifiez votre repository, vous devez demander à Git d'enregistrer vos modifications en faisant un git commit. L'option -m vous permet de lui envoyer un message décrivant les modifications effectuées
Par exemple : 

git commit -m "Ajouté ma checklist-vacances.md (woohoo!)" 
git push origin master