# Droppy pour YunoHost

[![Niveau d'intégration](https://dash.yunohost.org/integration/droppy.svg)](https://dash.yunohost.org/appci/app/droppy) ![](https://ci-apps.yunohost.org/ci/badges/droppy.status.svg) ![](https://ci-apps.yunohost.org/ci/badges/droppy.maintain.svg)  
[![Installer Droppy avec YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=droppy)

*[Read this readme in english.](./README.md)*
*[Lire ce readme en français.](./README_fr.md)*

> *Ce package vous permet d'installer Droppy rapidement et simplement sur un serveur YunoHost.
Si vous n'avez pas YunoHost, regardez [ici](https://yunohost.org/#/install) pour savoir comment l'installer et en profiter.*

## Vue d'ensemble

Droppy est un serveur de stockage de fichiers auto-hébergé avec une interface Web et des capacités pour éditer des fichiers et afficher des médias directement dans le navigateur.


**Version incluse :** 12.2.0~ynh8



## Captures d'écran

![](./doc/screenshots/screenshot.png)

## Avertissements / informations importantes

## Configuration

Comment configurer cette application : un fichier de configuration `/var/www/droppy/config/config.json` en SSH.  
Les fichiers partagés sont stockés dans le répertoire suivant : `/home/yunohost.app/droppy/files/`

## Documentations et ressources

* Dépôt de code officiel de l'app : https://github.com/silverwind/droppy
* Documentation YunoHost pour cette app : https://yunohost.org/app_droppy
* Signaler un bug : https://github.com/YunoHost-Apps/droppy_ynh/issues

## Informations pour les développeurs

Merci de faire vos pull request sur la [branche testing](https://github.com/YunoHost-Apps/droppy_ynh/tree/testing).

Pour essayer la branche testing, procédez comme suit.
```
sudo yunohost app install https://github.com/YunoHost-Apps/droppy_ynh/tree/testing --debug
ou
sudo yunohost app upgrade droppy -u https://github.com/YunoHost-Apps/droppy_ynh/tree/testing --debug
```

**Plus d'infos sur le packaging d'applications :** https://yunohost.org/packaging_apps