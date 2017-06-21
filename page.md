---
title: Page
layout: page
---

# Vous voulez améliorer le temps de chargement de votre site? Supprimer la base de données!


![Fonctionnement simplifié d'un CMS]({{ site.baseurl }}/img/Toms_Diagram_1.png)


Un site construit avec un CMS comme Wordpress utilise une base de données qui contient
tout le contenu du site. Requêter la base de données à chaque fois qu'une page est chargée
prend du temps. La plupart des CMS utilise un cache (càd conserve en mémoire les pages web)
pour accélérer le processus mais ça rend votre site plus difficile à maintenir.


![Fonctionnement d'un site static]({{ site.baseurl }}/img/static-site-JAMstack.png)


A contrario, un site statique ne contient que des fichiers (HTML, CSS et Javascript) qu'un serveur web
peut interpréter. Evidemment sans base de données et sans backend,
vous devez intégrer des services tierces pour gérer les fonctionnalités avancées.
Par exemple, Mailchimp pour vos newsletter, Vimeo ou Youtube pour intégrer des vidéos, Disqus pour gérer les commentaires, etc.


_Resources_
Les images proviennent de cet [article](https://builtvisible.com/go-static-try-jamstack/)
