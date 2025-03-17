# Site du Réseau IABM

Le site du Réseau IABM est construit avec **Jekyll** et déployé via **[GitHub Pages](https://docs.github.com/en/pages/setting-up-a-github-pages-site-with-jekyll)**. Pour construire le site, Jekyll utilise un template et le combine avec du contenu **Markdown**. Pour modifier le contenu du site, il n'y a donc qu'à modifier les fichiers
Markdown (`.md`) de ce dépôt GitHub.

Pour [ajouter un labo dans l'annuaire](#ajouter-un-labo), [publier un article](#ajouter-un-article) ou [modifier les pages statiques du site](#modifier-les-pages-statiques), vous êtes encouragés à [ouvrir une Pull Request](#ouvrir-une-pull-request) sur la branche `main` de ce dépôt. Vous pouvez [tester localement vos modifications](#tester-localement-le-site) avant de proposer vos changements.

Ce [tuto](https://reseau-iabm.github.io/tuto/2025/03/11/markdown.html) vous aidera à prendre rapidement en main la syntaxe Markdown.

## Ouvrir une Pull Request

Pour ajouter des informations ou proposer des modifications, il faut ouvrir une [Pull Request](https://docs.github.com/en/pull-requests) (idéalement en [forkant](https://docs.github.com/fr/pull-requests/collaborating-with-pull-requests/working-with-forks/fork-a-repo) préalablement
ce dépôt GitHub) et attendre l'approbation d'un reviewer.

Quelques exemples:
- [Ajouter un labo à l'annuaire](https://github.com/reseau-iabm/reseau-iabm.github.io/pull/1)
- [Ajouter un post](https://github.com/reseau-iabm/reseau-iabm.github.io/pull/3)

## Tester localement le site

1. [Installer Jekyll](https://jekyllrb.com/docs/installation/);
2. Se placer dans `docs`;
3. Lancer la commande `bundle install`;
4. Lancer la commande `bundle exec jekyll serve`.

[Pour plus d'informations.](https://docs.github.com/en/pages/setting-up-a-github-pages-site-with-jekyll/testing-your-github-pages-site-locally-with-jekyll)

## Ajouter un labo

Pour ajouter un laboratoire à l'annuaire, créez un fichier markdown (`.md`) dans le dossier `_labos`.
Dans l'en-tête, indiquez le **nom**, la **ville**, l'**adresse**, des **contacts** de votre laboratoire, ainsi qu'un éventuel **site internet**. Vous pouvez également ajouter le **logo** de votre laboratoire, qu'il vous faudra rajouter dans `images/labos`.

Enfin, ajouter une description de votre laboratoire dans le corps du fichier.

Référez-vous à [un example](https://github.com/reseau-iabm/reseau-iabm.github.io/blob/main/docs/_labos/aramis.md?plain=1) pour vous aider.

## Ajouter un article

Pour ajouter un post, créez un markdown (`.md`) dans le dossier `_posts`. Dans l'en-tête, indiquez
le **titre**, la **date**, l'**auteur**, une ou plusieurs **catégorie(s)**, et éventuellement
des **tags**. Laisser `layout` à `post`.

Écrivez ensuite votre article avec la syntaxe Markdown dans le corps du fichier. 

Référez-vous
à [un example](https://github.com/reseau-iabm/reseau-iabm.github.io/blob/main/docs/_posts/2025-03-17-bienvenue.md?plain=1) pour vous aider.

## Modifier les pages statiques

Pour proposer des modifications des pages statiques (page d'accueil, description du réseau, etc.),
modifiez le fichier markdown correspondant à la base du dossier `docs`. 
