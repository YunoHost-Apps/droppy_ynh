# Droppy for YunoHost

[![Integration level](https://dash.yunohost.org/integration/droppy.svg)](https://dash.yunohost.org/appci/app/droppy) ![](https://ci-apps.yunohost.org/ci/badges/droppy.status.svg) ![](https://ci-apps.yunohost.org/ci/badges/droppy.maintain.svg)  
[![Install Droppy with YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=droppy)

*[Lire ce readme en français.](./README_fr.md)*

> *This package allows you to install Droppy quickly and simply on a YunoHost server.  
If you don't have YunoHost, please consult [the guide](https://yunohost.org/#/install) to learn how to install it.*

## Overview

Droppy is a self-hosted file storage server with a web interface and capabilities to edit files and view media directly in the browser.

**Shipped version:** 12.2.0

## Screenshots

![](https://i.imgur.com/Ziv79rJ.png)

## Configuration

How to configure this app: a JSON configuration file with SSH. `/var/www/droppy/config/config.json`.  
Shared files are stored in the following directory: `/home/yunohost.app/droppy/files`

## Documentation

 * Official documentation: https://github.com/silverwind/droppy
 * YunoHost documentation: 

## YunoHost specific features

#### Multi-user support

* Is LDAP supported? **No**
* Can the app be used by multiple users? **Yes**

#### Supported architectures

* x86-64 - [![Build Status](https://ci-apps.yunohost.org/ci/logs/droppy%20%28Apps%29.svg)](https://ci-apps.yunohost.org/ci/apps/droppy/)
* ARMv8-A - [![Build Status](https://ci-apps-arm.yunohost.org/ci/logs/droppy%20%28Apps%29.svg)](https://ci-apps-arm.yunohost.org/ci/apps/droppy/)

## Links

 * Report a bug: https://github.com/YunoHost-Apps/droppy_ynh/issues
 * Upstream app repository: https://github.com/silverwind/droppy
 * YunoHost website: https://yunohost.org/

---

## Developer info

Please send your pull request to the [testing branch](https://github.com/YunoHost-Apps/droppy_ynh/tree/testing).

To try the testing branch, please proceed like that.
```
sudo yunohost app install https://github.com/YunoHost-Apps/droppy_ynh/tree/testing --debug
or
sudo yunohost app upgrade droppy -u https://github.com/YunoHost-Apps/droppy_ynh/tree/testing --debug
```
