# Teddit pour YunoHost

[![Niveau d'intégration](https://dash.yunohost.org/integration/teddit.svg)](https://dash.yunohost.org/appci/app/teddit) ![](https://ci-apps.yunohost.org/ci/badges/teddit.status.svg) ![](https://ci-apps.yunohost.org/ci/badges/teddit.maintain.svg)  
[![Installer Teddit avec YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=teddit)

*[Read this readme in english.](./README.md)*
*[Lire ce readme en français.](./README_fr.md)*

> *Ce package vous permet d'installer Teddit rapidement et simplement sur un serveur YunoHost.
Si vous n'avez pas YunoHost, regardez [ici](https://yunohost.org/#/install) pour savoir comment l'installer et en profiter.*

## Vue d'ensemble

A free and open source alternative Reddit front-end focused on privacy. Inspired by the Nitter project.

### Features

- No JavaScript or ads
- All requests go through the backend, client never talks to Reddit
- Prevents Reddit from tracking your IP or JavaScript fingerprint
- Unofficial API (RSS & JSON support, no rate limits or Reddit account required)
- Lightweight (teddit frontpage: ~30 HTTP requests with ~270 KB of data downloaded vs. Reddit frontpage: ~190 requests with ~24 MB)
- Self-hostable. Anyone can setup an instance. An instance can either use Reddit's API with or without OAuth (so Reddit API key is not necessarily needed).


**Version incluse :** 0.4.0~ynh1

**Démo :** https://teddit.net/

## Captures d'écran

![](./doc/screenshots/screenshot.png)

## Documentations et ressources

* Site officiel de l'app : https://teddit.net/
* Dépôt de code officiel de l'app : https://codeberg.org/teddit/teddit
* Documentation YunoHost pour cette app : https://yunohost.org/app_teddit
* Signaler un bug : https://github.com/YunoHost-Apps/teddit_ynh/issues

## Informations pour les développeurs

Merci de faire vos pull request sur la [branche testing](https://github.com/YunoHost-Apps/teddit_ynh/tree/testing).

Pour essayer la branche testing, procédez comme suit.
```
sudo yunohost app install https://github.com/YunoHost-Apps/teddit_ynh/tree/testing --debug
ou
sudo yunohost app upgrade teddit -u https://github.com/YunoHost-Apps/teddit_ynh/tree/testing --debug
```

**Plus d'infos sur le packaging d'applications :** https://yunohost.org/packaging_apps