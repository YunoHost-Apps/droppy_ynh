# Droppy pour YunoHost

[![Niveau d'intégration](https://dash.yunohost.org/integration/droppy.svg)](https://dash.yunohost.org/appci/app/droppy) ![](https://ci-apps.yunohost.org/ci/badges/droppy.status.svg) ![](https://ci-apps.yunohost.org/ci/badges/droppy.maintain.svg)  
[![Installer Droppy avec YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=droppy)

*[Read this readme in english.](./README.md)* 

> *Ce package vous permet d'installer Droppy rapidement et simplement sur un serveur YunoHost.  
Si vous n'avez pas YunoHost, consultez [le guide](https://yunohost.org/#/install) pour apprendre comment l'installer.*

## Vue d'ensemble

Droppy est un serveur de stockage de fichiers auto-hébergé avec une interface Web et des capacités pour éditer des fichiers et afficher des médias directement dans le navigateur.

**Version incluse :** 12.2.0

## Captures d'écran

![](https://i.imgur.com/Ziv79rJ.png)

## Configuration

Comment configurer cette application : un fichier de configuration `/var/www/droppy/config/config.json` en SSH.  
Les fichiers partagés sont stockés dans le répertoire suivant : `/home/yunohost.app/droppy/files/`

## Documentation

 * Documentation officielle : https://github.com/silverwind/droppy
 * Documentation YunoHost : 

## Caractéristiques spécifiques YunoHost

#### Support multi-utilisateur

* L'authentification LDAP est-elle prise en charge ? **Non**
* L'application peut-elle être utilisée par plusieurs utilisateurs ? **Oui**

#### Architectures supportées

* x86-64 - [![Build Status](https://ci-apps.yunohost.org/ci/logs/droppy%20%28Apps%29.svg)](https://ci-apps.yunohost.org/ci/apps/droppy/)
* ARMv8-A - [![Build Status](https://ci-apps-arm.yunohost.org/ci/logs/droppy%20%28Apps%29.svg)](https://ci-apps-arm.yunohost.org/ci/apps/droppy/)

## Liens

 * Signaler un bug : https://github.com/YunoHost-Apps/droppy_ynh/issues
 * Dépôt de l'application principale : https://github.com/silverwind/droppy
 * Site web YunoHost : https://yunohost.org/

---

## Informations pour les développeurs

Merci de faire vos pull request sur la [branche testing](https://github.com/YunoHost-Apps/droppy_ynh/tree/testing).

Pour essayer la branche testing, procédez comme suit.
```
sudo yunohost app install https://github.com/YunoHost-Apps/droppy_ynh/tree/testing --debug
ou
sudo yunohost app upgrade droppy -u https://github.com/YunoHost-Apps/droppy_ynh/tree/testing --debug
```
