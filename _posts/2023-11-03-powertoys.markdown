---
layout: post
title: "PowerToys, un ami qui vous veut du bien"
date: 2023-11-03 14:42:45 +0100
categories: Méthodologie, outils
excerpt: "Windows a des limites, dépassez-les grâce à PowerToys, une application qui pimpera votre PC en quelques clics."
image: "https://github.com/ludovicdean/devendevenir.github.io/tree/main/images/powertoys.png"
---

&nbsp;

!["Bannière de l'article sur Powertoys"](/images/hal-gatewood-powertoys-unsplash.jpg)
Photo de <a href="https://unsplash.com/fr/@halacious?utm_content=creditCopyText&utm_medium=referral&utm_source=unsplash">Hal Gatewood</a> sur <a href="https://unsplash.com/fr/photos/tastiera-del-computer-nera-Pr578ZCufII?utm_content=creditCopyText&utm_medium=referral&utm_source=unsplash">Unsplash</a>

## Introduction

<p style="text-align:justify;">
Après quelques années à travailler sur des ordinateurs sous Windows j'ai fréquemment rencontré des problématiques d'affichage dès lors que l'on a plus d'un écran.
La multiplicité des périphériques d'affichage a l'avantage de pouvoir conserver plusieurs fenêtres simultanément visibles. 
</p>
<p style="text-align:justify;">
En revanche, disposer correctement ces fenêtres sans s'arracher les cheveux à chaque démarrage est une véritable gageure.
Ce problème semble être parvenu aux oreilles de Microsoft, qui a créé l'application PowerToys, qui règle ce problème parmi tant d'autres. 
</p>

&nbsp;

## Alors c'est quoi PowerToys ?

<p style="text-align:justify;">
Powertoys c'est une application disponible [ici](https://learn.microsoft.com/fr-fr/windows/powertoys/), qui permet de répondre à un ensemble de problématiques liées à l'utilisation avancée d'un ordinateur :
</p>

- Gestion de fenêtres toujours visibles
- Gestion de l'activité de l'ordinateur
- Gestion des fenêtres
- Modules complémentaires de l'explorateur de fichiers
- Gestion du clavier

<p style="text-align:justify;">
A l'instar de Notion qui est le maestro de l'info, PowerToys est le chef d'orchestre ultime pour votre ordinateur, qui va rajouter des fonctionnalités difficiles à quitter après y avoir goûté. Après ce rapide passage en revue des capacités de PowerToys, il est temps d'aborder plus en détail chacun de ses modules.
</p>

![Page d'accueil de PowerToys](/images/powertoys-homepage.png)

&nbsp;

## Au paradis des fenêtres

<p style="text-align:justify;">
Mon métier m'amène à travailler avec des écrans multiples, généralement 3 (PC portable + 2 écrans) et de multiples applications que je souhaite garder visibles (Teams, e-mails, éditeur de code etc.). Comment conserver toutes ces fenêtres en faisant uniquement appel aux capacités de Windows ? Appuyer sur la touche **Windows** puis une flèche pour gérer par moitié ou quart d'écran est vite limité. C'est ici que Fancy Zones entre sur le ring et vient nous sauver la mise.
</p>

<video autoplay="autoplay" loop="loop" width="768" height="512">
  <source src="/images/powertoys-fancy-zones.webm" type="video/webm">
</video>
<p style="text-align:justify;">
Vous pouvez définir autant de zones que vous le souhaitez pour chacun de vos écrans. Il vous suffira ensuite lorsque vous déplacez une fenêtre de maintenir la touche **Maj** pour que les zones s'affichent. Quand le focus passe sur une zone, vous pouvez relâcher le clic, la fenêtre s'ajustera automatiquement à cette zone. Fini les mails ou les messages Teams ratés, vos fenêtres restent ouvertes.
</p>

&nbsp;

## On se réveille !

<p style="text-align:justify;">
Vos activités vous demandent de garder votre ordinateur actif ? PowerToys peut prendre le pas sur la gestion de l'alimentation avec son module Awake. L'activation du module permet d'accéder aux options d'alimentation et de les personnaliser selon vos besoins.
</p>

<video autoplay="autoplay" loop="loop" width="768" height="512">
  <source src="/images/powertoys-awake.webm" type="video/webm">
</video>

&nbsp;

## J'adore cette couleur mais c'était quoi déjà ?

<p style="text-align:justify;">
Le développement web peut nous amener à rechercher des couleurs pour un site, ou a reproduire des couleurs qui nous plaisent. Il n'est pas toujours facile de retrouver les teintes exactes que l'on recherche. Ici encore PowerToys propose un outil qui résout ce type de problème, Color Picker.
</p>

<video autoplay="autoplay" loop="loop" width="768" height="512">
  <source src="/images/powertoys-color-picker.webm" type="video/webm">
</video>

&nbsp;

## Pimpez votre explorateur de fichiers

<p style="text-align:justify;">
Trouver un fichier, l'ouvrir, le parcourir, réaliser que ce n'est pas le bon, le fermer, recommencer. Fini le calvaire, les extensions de l'explorateur de fichier sont faites pour vous. Vous pouvez sélectionner pour quels types de fichiers vous souhaitez activer l'aperçu.
</p>

![Paramétrage des extensions de l'explorateur de fichiers Windows](/images/powertoys-explorateur-fichiers.png)

&nbsp;

<p style="text-align:justify;">
Il suffit d'appuyer sur **Alt+P** pour s'assurer que l'aperçu est bien activé dans l'explorateur de fichiers. Lorsqu'on sélectionne un fichier, son aperçu est généré dans la partie droite de l'écran. La largeur de l'aperçu peut être modifiée.
</p>

<video autoplay="autoplay" loop="loop" width="768" height="512">
  <source src="/images/powertoys-apercu.webm" type="video/webm">
</video>

&nbsp;

## À tous les virtuoses du clavier

<p style="text-align:justify;">
Parmi les développeurs il existe une espèce rare, les fous du clavier. Ils ont cette capacité insensée de passer leur journée sur un PC en passant moins de 10 minutes la main sur leur souris. Comment font-ils ? Aucune idée, les magiciens ne révèlent jamais leurs secrets. PowerToys nous propose un gestionnaire de clavier, qui permet de remapper des touches.
</p>

<video autoplay="autoplay" loop="loop" width="768" height="512">
  <source src="/images/powertoys-keyboard-manager.webm" type="video/webm">
</video>
<p style="text-align:justify;">
Vous avez la possibilité de remapper les touches de votre clavier à l'échelle de votre ordinateur (peu adapté, ou en évitant les touches seules) ou à l'échelle d'une seule application, il faut alors utiliser le menu du bas de la fenêtre.
</p>

## À nos amis photographes

<p style="text-align:justify;">
Quand je trie des photos il m'arrive de souhaiter renommer un ensemble de fichiers avec le même nom suivi d'un numéro. Cela peut être fastidieux quand le volume de fichiers devient important. Ici encore PowerToys nous facilite la vie grâce à PowerRename, qui est disponible dans le menu contextuel de l'explorateur lorsqu'on fait un clic droit sur un ensemble de fichiers.
</p>

<video autoplay="autoplay" loop="loop" width="768" height="512">
  <source src="/images/powertoys-power-rename.webm" type="video/webm">
</video>

&nbsp;

## Conclusion

<p style="text-align:justify;">
Comme vous l'avez vu PowerToys regorge de fonctionnalités, que je n'ai pas toutes développées ici mais feront peut-être l'objet d'un second article. Charge à vous de faire de PowerToys votre bras droit afin de simplifier votre quotidien. L'application n'en est qu'à sa version 0.75.1 et est régulièrement mise à jour. Il a récemment été évoqué la possibilité que PowerToys soit intégrée nativement à Windows 11. Affaire à suivre !
</p>
