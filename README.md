<!--
N.B.: This README was automatically generated by https://github.com/YunoHost/apps/tree/master/tools/README-generator
It shall NOT be edited by hand.
-->

# Filebrowser for YunoHost

[![Integration level](https://dash.yunohost.org/integration/filebrowser.svg)](https://dash.yunohost.org/appci/app/filebrowser) ![Working status](https://ci-apps.yunohost.org/ci/badges/filebrowser.status.svg) ![Maintenance status](https://ci-apps.yunohost.org/ci/badges/filebrowser.maintain.svg)

[![Install Filebrowser with YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=filebrowser)

*[Lire ce readme en français.](./README_fr.md)*

> *This package allows you to install Filebrowser quickly and simply on a YunoHost server.
If you don't have YunoHost, please consult [the guide](https://yunohost.org/#/install) to learn how to install it.*

## Overview

filebrowser provides a file managing interface within a specified directory and it can be used to upload, delete, preview, rename and edit your files. It allows the creation of multiple users and each user can have its own directory. It can be used as a standalone app or as a middleware.


**Shipped version:** 2.23.0~ynh4

## Screenshots

![Screenshot of Filebrowser](./doc/screenshots/screenshot.PNG)

## Documentation and resources

* Official app website: <https://filebrowser.org>
* Official admin documentation: <https://filebrowser.org/>
* Upstream app code repository: <https://github.com/filebrowser/filebrowser>
* YunoHost documentation for this app: <https://yunohost.org/app_filebrowser>
* Report a bug: <https://github.com/YunoHost-Apps/filebrowser_ynh/issues>

## Developer info

Please send your pull request to the [testing branch](https://github.com/YunoHost-Apps/filebrowser_ynh/tree/testing).

To try the testing branch, please proceed like that.

``` bash
sudo yunohost app install https://github.com/YunoHost-Apps/filebrowser_ynh/tree/testing --debug
or
sudo yunohost app upgrade filebrowser -u https://github.com/YunoHost-Apps/filebrowser_ynh/tree/testing --debug
```

**More info regarding app packaging:** <https://yunohost.org/packaging_apps>
