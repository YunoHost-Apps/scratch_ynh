# Scratch pour YunoHost

[![Niveau d'intégration](https://dash.yunohost.org/integration/scratch.svg)](https://dash.yunohost.org/appci/app/scratch) ![](https://ci-apps.yunohost.org/ci/badges/scratch.status.svg) ![](https://ci-apps.yunohost.org/ci/badges/scratch.maintain.svg)  
[![Installer Scratch avec YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=scratch)

*[Read this readme in english.](./README.md)*
*[Lire ce readme en français.](./README_fr.md)*

> *Ce package vous permet d'installer Scratch rapidement et simplement sur un serveur YunoHost.
Si vous n'avez pas YunoHost, regardez [ici](https://yunohost.org/#/install) pour savoir comment l'installer et en profiter.*

## Vue d'ensemble

Langage de programmation pour créer vos propres histoires, jeux et animations interactifs

**Version incluse :** 3.0~ynh1

**Démo :** https://llk.github.io/scratch-gui/develop/

## Captures d'écran

![](./doc/screenshots/800px-Scratch_3.0_Éditeur.png)

## Documentations et ressources

* Site officiel de l'app : https://scratch.mit.edu/
* Documentation officielle de l'admin : https://fr.scratch-wiki.info/wiki/Scratch_3.0
* Dépôt de code officiel de l'app : https://github.com/LLK/scratch-gui
* Documentation YunoHost pour cette app : https://yunohost.org/app_scratch
* Signaler un bug : https://github.com/YunoHost-Apps/scratch_ynh/issues

## Informations pour les développeurs

Merci de faire vos pull request sur la [branche testing](https://github.com/YunoHost-Apps/scratch_ynh/tree/testing).

Pour essayer la branche testing, procédez comme suit.
```
sudo yunohost app install https://github.com/YunoHost-Apps/scratch_ynh/tree/testing --debug
ou
sudo yunohost app upgrade scratch -u https://github.com/YunoHost-Apps/scratch_ynh/tree/testing --debug
```

**Plus d'infos sur le packaging d'applications :** https://yunohost.org/packaging_apps