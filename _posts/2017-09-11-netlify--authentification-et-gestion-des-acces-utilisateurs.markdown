---
title: "Netlify : authentification et gestion des accès utilisateurs"
date: "2017-09-11 13:59:21 +0200"
description:
image:
---

En intégrant un service d'identification, Netlify continue d'étoffer son offre de services et se positionne comme une solution de plus en plus complète pour le développement et le déploiement d'applications modernes basées sur la JAMstack.
{: .intro }

La startup basée à San Francisco continue de développer des fonctionnalités pour enrichir les possibilités offertes par sa plate-forme. Cette semaine Netlify a annoncé sur son blog l'ajout de la gestion d'identification pour les sites hébergés sur sa plate-forme.

La fonctionnalité est encore en bêta mais on peut déjà la tester via l' exemple fourni. Le tout se configure en quelques clics depuis l'interface d'administration.

Une fois les réglages effectués, vous avez donc la possibilité de permettre aux utilisateurs de votre site déployé en statique de s'enregistrer et de se connecter.

Dans l'exemple fourni, Netlify montrer comment ce service peut par exemple permettre d'ajouter une authentification via Google, GitHub, GitLab ou BitBucket à Netlify CMS. Auparant vous ne pouviez vous connecter que si vous disposiez d'un compte chez GitHub.

Comme Netlify n'aime pas faire les choses à moitié, l'intégration de la fonctionnalité est assez complète et fournit notamment un widget pour l'enregistrement que vous pouvez voir en action dans l'animation suivante :

{% include figure.html url="/assets/images/netlify-identity/auth.gif" description="Connexion avec son compte Google dans Netlify CMS" %}
