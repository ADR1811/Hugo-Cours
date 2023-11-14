---
title: "COMMENT INSTALLER HUGO LA TROISIEME VA VOUS CHOQUER"
date: 2023-11-14T00:00:00Z
draft: false
---

# Bienvenue sur mon blog Hugo !

[Hugo](https://gohugo.io/) est un générateur de site statique open-source écrit en Go. Il est rapide, facile à utiliser et très flexible. Dans cet article, je vais vous montrer comment j'ai créé ce blog avec Hugo.

## Image de google 
![Texte alternatif de l'image](https://cellar-c2.services.clever-cloud.com/content/2023/03/tabea-schimpf-e2icf0r6N64-unsplash.jpg)

## Installation de Hugo

La première étape consiste à installer Hugo sur votre ordinateur. Vous pouvez télécharger la dernière version de Hugo sur le [site officiel](https://gohugo.io/getting-started/installing/). Une fois que vous avez téléchargé Hugo, vous pouvez vérifier que l'installation s'est bien déroulée en exécutant la commande suivante dans votre terminal :

```bash
hugo version
```

## Création d'un nouveau site Hugo

Une fois que vous avez installé Hugo, vous pouvez créer un nouveau site Hugo en exécutant la commande suivante dans votre terminal :

```bash
hugo new site my-blog
```

Cette commande crée un nouveau site Hugo dans le dossier `my-blog`. Vous pouvez maintenant vous rendre dans le dossier `my-blog` et initialiser un dépôt Git :

```bash
cd my-blog
git init
```

## Ajout d'un thème Hugo

Une fois que vous avez créé un nouveau site Hugo, vous pouvez ajouter un thème Hugo en exécutant la commande suivante dans votre terminal :

```bash
git submodule add
```

## Création d'un nouveau contenu

Une fois que vous avez ajouté un thème Hugo, vous pouvez créer un nouveau contenu en exécutant la commande suivante dans votre terminal :

```bash
hugo new posts/my-first-post.md
```

Cette commande crée un nouveau contenu dans le dossier `content/posts` avec le nom `my-first-post.md`. Vous pouvez maintenant éditer le fichier `my-first-post.md` et ajouter du contenu à votre nouveau contenu.

## Génération du site Hugo

Une fois que vous avez créé un nouveau contenu, vous pouvez générer votre site Hugo en exécutant la commande suivante dans votre terminal :

```bash
hugo
```

Cette commande génère votre site Hugo dans le dossier `public`. Vous pouvez maintenant vous rendre dans le dossier `public` et initialiser un dépôt Git :

```bash
cd public
git init
```

## Déploiement du site Hugo

Une fois que vous avez généré votre site Hugo, vous pouvez le déployer en exécutant la commande suivante dans votre terminal :

```bash
git add .
git commit -m "Initial commit"
git push origin master
```

Cette commande déploie votre site Hugo sur GitHub Pages. Vous pouvez maintenant visiter votre site Hugo à l'adresse suivante : [https://your-username.github.io/my-blog/](https://your-username.github.io/my-blog/).

## Conclusion

Dans cet article, j'ai montré comment j'ai créé ce blog avec Hugo. J'espère que vous avez trouvé cet article utile et que vous avez appris quelque chose de nouveau. Si vous avez des questions ou des commentaires, n'hésitez pas à les laisser dans la section commentaires ci-dessous.