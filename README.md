<!--
N.B.: This README was automatically generated by https://github.com/YunoHost/apps/tree/master/tools/README-generator
It shall NOT be edited by hand.
-->

# InvoiceNinja 5 for YunoHost

[![Integration level](https://dash.yunohost.org/integration/invoiceninja5.svg)](https://dash.yunohost.org/appci/app/invoiceninja5) ![Working status](https://ci-apps.yunohost.org/ci/badges/invoiceninja5.status.svg) ![Maintenance status](https://ci-apps.yunohost.org/ci/badges/invoiceninja5.maintain.svg)  
[![Install InvoiceNinja 5 with YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=invoiceninja5)

*[Lire ce readme en français.](./README_fr.md)*

> *This package allows you to install InvoiceNinja 5 quickly and simply on a YunoHost server.
If you don't have YunoHost, please consult [the guide](https://yunohost.org/#/install) to learn how to install it.*

## Overview

Create and email invoices, track payments, expenses, and time tasks

**Shipped version:** 5.5.23~ynh1


**Demo:** https://app.invoiceninja.com/dashboard

## Screenshots

![Screenshot of InvoiceNinja 5](./doc/screenshots/Create-Invoices-in-Seconds.png)

## Disclaimers / important information

### Warning

This is the new version of InvoiceNinja. Installation into a sub-directory is currently impossible.

Invoice Ninja is the the leading self-hosted invoicing platform to create & email invoices, track payments and expenses, and time billable tasks & projects for clients.

## YunoHost specific features

#### Multi-user support

* There is no official LDAP support
* The first user gets created after installing Invoice Ninja. The email-address is the one of your administrator user of the app. The password is the administration password you provided while installing.
* Other users can be created from inside the application

## Documentation and resources

* Official app website: <https://invoiceninja.org>
* Official user documentation: <https://invoiceninja.github.io/>
* Official admin documentation: <https://invoiceninja.github.io/>
* Upstream app code repository: <https://github.com/invoiceninja/invoiceninja>
* YunoHost documentation for this app: <https://yunohost.org/app_invoiceninja5>
* Report a bug: <https://github.com/YunoHost-Apps/invoiceninja5_ynh/issues>

## Developer info

Please send your pull request to the [testing branch](https://github.com/YunoHost-Apps/invoiceninja5_ynh/tree/testing).

To try the testing branch, please proceed like that.

``` bash
sudo yunohost app install https://github.com/YunoHost-Apps/invoiceninja5_ynh/tree/testing --debug
or
sudo yunohost app upgrade invoiceninja5 -u https://github.com/YunoHost-Apps/invoiceninja5_ynh/tree/testing --debug
```

**More info regarding app packaging:** <https://yunohost.org/packaging_apps>
