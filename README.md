<!--
N.B.: This README was automatically generated by https://github.com/YunoHost/apps/tree/master/tools/readme_generator
It shall NOT be edited by hand.
-->

# Teddit for YunoHost

[![Integration level](https://dash.yunohost.org/integration/teddit.svg)](https://dash.yunohost.org/appci/app/teddit) ![Working status](https://ci-apps.yunohost.org/ci/badges/teddit.status.svg) ![Maintenance status](https://ci-apps.yunohost.org/ci/badges/teddit.maintain.svg)

[![Install Teddit with YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=teddit)

*[Lire ce readme en français.](./README_fr.md)*

> *This package allows you to install Teddit quickly and simply on a YunoHost server.
If you don't have YunoHost, please consult [the guide](https://yunohost.org/#/install) to learn how to install it.*

## Overview

A free and open source alternative Reddit front-end focused on privacy. Inspired by the Nitter project.

### Features

- No JavaScript or ads
- All requests go through the backend, client never talks to Reddit
- Prevents Reddit from tracking your IP or JavaScript fingerprint
- Unofficial API (RSS & JSON support, no rate limits or Reddit account required)
- Lightweight (teddit frontpage: ~30 HTTP requests with ~270 KB of data downloaded vs. Reddit frontpage: ~190 requests with ~24 MB)



**Shipped version:** 2023.09.17~ynh1

**Demo:** https://teddit.net/

## Screenshots

![Screenshot of Teddit](./doc/screenshots/screenshot.png)

## Documentation and resources

* Official app website: <https://teddit.net/>
* Upstream app code repository: <https://codeberg.org/teddit/teddit>
* YunoHost Store: <https://apps.yunohost.org/app/teddit>
* Report a bug: <https://github.com/YunoHost-Apps/teddit_ynh/issues>

## Developer info

Please send your pull request to the [testing branch](https://github.com/YunoHost-Apps/teddit_ynh/tree/testing).

To try the testing branch, please proceed like that.

``` bash
sudo yunohost app install https://github.com/YunoHost-Apps/teddit_ynh/tree/testing --debug
or
sudo yunohost app upgrade teddit -u https://github.com/YunoHost-Apps/teddit_ynh/tree/testing --debug
```

**More info regarding app packaging:** <https://yunohost.org/packaging_apps>