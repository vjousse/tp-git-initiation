# Prise en main

Nous allons utiliser [Github](http://github.com) et [Bitbucket][http://bitbucket.org]. Commencez par créer un compte sur chacun de ces services.

## Configurez votre git local

Dites-lui comment vous vous appelez :

    git config --global user.name "Votre nom/surnom"

Vous pouvez vérifier que ça a bien fonctionné avec :

    git config --global user.name

Faites de même pour votre email (de préférence celui que vous avez utilisé pour vous inscrire aux services ci-dessus).

    git config --global user.email "votre_email@exemple.com"

Et on vérifie avec :

    git config --global user.email


## Créez votre premier dépôt local

- Créez un dépôt à partir d'un répertoire contenant déjà des fichiers
- Ajoutez tous ces fichiers dans une version
- Utilisez `git log` pour voir l'historique de vos versions

## Envoyez ce dépôt sur Github

- Créez un dépôt distant (open source) sur Github pour votre projet.
- Faites en sorte d'envoyer les modifications de votre dépôt local sur Github.

## Récupérer un dépôt Github

- Choisissez le dépôt d'un de vos voisins et récupérez le en local.
- Faites un changement, créez une nouvelle version.
- Essayez d'envoyer cette version sur Github. Que se passe-t-il ? Pourquoi ?
- À votre avis, comment-faire pour que cela fonctionne ?

## Clés SSH

Il n'a pas du vous échapper qu'à chaque fois que vous voulez envoyer une modification sur Github, il vous demande à chaque fois votre mot de passe. C'est sympa 5 minutes, mais à la longue ça devient vite inutilisable. Il existe un moyen d'éviter cela : au lieu de vous authentifier par login/mot de passe, Git peut vous authentifier grâce à vos clés SSH. Si vous ne savez pas ce que c'est (je ne connais pas par cœur vos cours de réseau et votre niveau) n'hésitez pas à me demander : c'est quelque chose d'important à connaître (et qui n'est pas spécifique à Git).

Pour les instructions, pas la peine de réinventer la roue, [Github a un très bon tutoriel là dessus](https://help.github.com/articles/generating-ssh-keys/).

