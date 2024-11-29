<!--
Ohart ongi: README hau automatikoki sortu da <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>ri esker
EZ editatu eskuz.
-->

# CommaFeed YunoHost-erako

[![Integrazio maila](https://apps.yunohost.org/badge/integration/commafeed)](https://ci-apps.yunohost.org/ci/apps/commafeed/)
![Funtzionamendu egoera](https://apps.yunohost.org/badge/state/commafeed)
![Mantentze egoera](https://apps.yunohost.org/badge/maintained/commafeed)

[![Instalatu CommaFeed YunoHost-ekin](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=commafeed)

*[Irakurri README hau beste hizkuntzatan.](./ALL_README.md)*

> *Pakete honek CommaFeed YunoHost zerbitzari batean azkar eta zailtasunik gabe instalatzea ahalbidetzen dizu.*  
> *YunoHost ez baduzu, kontsultatu [gida](https://yunohost.org/install) nola instalatu ikasteko.*

## Aurreikuspena

Google Reader inspired self-hosted RSS reader, based on Quarkus and React/TypeScript.

**Paketatutako bertsioa:** 5.3.4~ynh1

**Demoa:** <https://www.commafeed.com/#/app/category/all>

## Pantaila-argazkiak

![CommaFeed(r)en pantaila-argazkia](./doc/screenshots/screenshot.png)

## Dokumentazioa eta baliabideak

- Aplikazioaren webgune ofiziala: <https://www.commafeed.com/>
- Jatorrizko aplikazioaren kode-gordailua: <https://github.com/Athou/commafeed>
- YunoHost Denda: <https://apps.yunohost.org/app/commafeed>
- Eman errore baten berri: <https://github.com/YunoHost-Apps/commafeed_ynh/issues>

## Garatzaileentzako informazioa

Bidali `pull request`a [`testing` abarrera](https://github.com/YunoHost-Apps/commafeed_ynh/tree/testing).

`testing` abarra probatzeko, ondorengoa egin:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/commafeed_ynh/tree/testing --debug
edo
sudo yunohost app upgrade commafeed -u https://github.com/YunoHost-Apps/commafeed_ynh/tree/testing --debug
```

**Informazio gehiago aplikazioaren paketatzeari buruz:** <https://yunohost.org/packaging_apps>
