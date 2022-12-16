# Consignes pour rédaction

Je synthétise ici les différentes consignes pour rédiger le rapport.

## Setup

- Vous ouvrez un terminal GitBash
- Vous allez dans un dossier de travail
- Vous faites la commande ```git clone git@github.com:RaphaelTRIBOT/MIG_LH2.git```

## Comment mettre à jour
Si vous savez utiliser git sur vscode, allez-y, sinon:  
Une fois vos modifications faites, vous commitez vos fichiers:
```
git add VOS FICHIERS
git commit (spécifiez un message ayant du sens: "ajout annexe K" par exemple)
git pull
Là vous vérifiez que y'a PAS EU D'ERREUR (utiliser git status pour voir si y'a des messages en rouge)
git push 
```

Il ne devrait pas avoir d'erreur pendant ces étapes, s'il y en a **NE TOUCHEZ A RIEN**, Appelez Raph ou Arthur ou n'importe qui qui maitrise


## Comment rédiger

Il y a 3 choses à faire :
- Corriger les petites erreurs dans votre texte
- Faire votre annexe
- Mettre des images dans vos annexes.

### Je corrige les erreurs dans mon texte

Dans le fichier Rapport MIG LH2.tex

Ce que j'ai écrit n'est pas français ou il manque des choses? Je corrige
J'ai fait référence à des figures ( voir figure 3 etc...) et cela n'est pas cohérent? (figure 27 en vrai) : Je corrige. 

### Je fais mon annexe. 

Dans le fichier Rapport MIG LH2.tex et dans le dossier Annexe du dossier Image

Vous écrivez à la fin du rapport dans la partie qui vous est allouée.
Vous écrivez comme les autres écrivent.

### J'insère des images dans le fichier

Une fois que vous avez écrit votre texte. Il faut insérer des images. Pour cela il faut taper le code suivant:

```latex 
\begin{figure}[h]
\centering
\includegraphics[width=0.8\linewidth]{image/annexe/nom_dossier/nom_figure.extension}
\caption{Titre de votre figure.}
\end{figure}
```

A cet endroit il y aura une image. Il faudra ensuite mettre l'image dans un dossier et appeler cette image dans votre code  (le fameux \includegraphics{ } ).
Vous créez un dossier dans lequel vous mettez votre image et vous la mettez. Il faut recopier le chemin de l'image dans le include. Voila.
