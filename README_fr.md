<!--
Nota bene : ce README est automatiquement généré par <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
Il NE doit PAS être modifié à la main.
-->

# Noalyss pour YunoHost

[![Niveau d’intégration](https://dash.yunohost.org/integration/noalyss.svg)](https://dash.yunohost.org/appci/app/noalyss) ![Statut du fonctionnement](https://ci-apps.yunohost.org/ci/badges/noalyss.status.svg) ![Statut de maintenance](https://ci-apps.yunohost.org/ci/badges/noalyss.maintain.svg)

[![Installer Noalyss avec YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=noalyss)

*[Lire le README dans d'autres langues.](./ALL_README.md)*

> *Ce package vous permet d’installer Noalyss rapidement et simplement sur un serveur YunoHost.*  
> *Si vous n’avez pas YunoHost, consultez [ce guide](https://yunohost.org/install) pour savoir comment l’installer et en profiter.*

## Vue d’ensemble

Noalyss est un serveur de comptabilité destiné à être hébergé sur Internet afin de contenir la comptabilité d’un nombre illimité de sociétés et d’utilisateurs ne se connaissant pas. Chaque société a ses propres dossiers comptables, ses propres utilisateurs, et ne peut pas interférer avec la comptabilité des autres, à moins d’y être expressément autorisé.

**Version incluse :** 9.1.0.7~ynh2

**Démo :** <http://demo.noalyss.eu/index.php>

## Captures d’écran

![Capture d’écran de Noalyss](./doc/screenshots/Sélection_099_0.png)

## Documentations et ressources

- Site officiel de l’app : <http://noalyss.eu>
- Documentation officielle de l’admin : <https://wiki.noalyss.eu/doku.php>
- YunoHost Store : <https://apps.yunohost.org/app/noalyss>
- Signaler un bug : <https://github.com/YunoHost-Apps/noalyss_ynh/issues>

## Informations pour les développeurs

Merci de faire vos pull request sur la [branche `testing`](https://github.com/YunoHost-Apps/noalyss_ynh/tree/testing).

Pour essayer la branche `testing`, procédez comme suit :

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/noalyss_ynh/tree/testing --debug
ou
sudo yunohost app upgrade noalyss -u https://github.com/YunoHost-Apps/noalyss_ynh/tree/testing --debug
```

**Plus d’infos sur le packaging d’applications :** <https://yunohost.org/packaging_apps>
