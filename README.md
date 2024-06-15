<!--
N.B.: This README was automatically generated by <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
It shall NOT be edited by hand.
-->

# OwnTracks for YunoHost

[![Integration level](https://dash.yunohost.org/integration/owntracks.svg)](https://dash.yunohost.org/appci/app/owntracks) ![Working status](https://ci-apps.yunohost.org/ci/badges/owntracks.status.svg) ![Maintenance status](https://ci-apps.yunohost.org/ci/badges/owntracks.maintain.svg)

[![Install OwnTracks with YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=owntracks)

*[Read this README in other languages.](./ALL_README.md)*

> *This package allows you to install OwnTracks quickly and simply on a YunoHost server.*  
> *If you don't have YunoHost, please consult [the guide](https://yunohost.org/install) to learn how to install it.*

## Overview

This is a web interface for OwnTracks built as a Vue.js single page application. The recorder itself already ships with some basic web pages, this is a more advanced interface with more functionality, all in one place.

### Features

- Last known (i.e. live) locations:
- Location history (data points, line or both)
- Location heatmap
- Quickly fit all shown objects on the map into view
- Display data in a specific date and time range
- Filter by user or specific device
- Calculation of distance travelled
- Download selected location data as JSON
- Highly customisable


**Shipped version:** 2.15.2~ynh1

## Screenshots

![Screenshot of OwnTracks](./doc/screenshots/screenshot.png)

## Documentation and resources

- Official app website: <https://owntracks.org/>
- Upstream app code repository: <https://github.com/owntracks/frontend>
- YunoHost Store: <https://apps.yunohost.org/app/owntracks>
- Report a bug: <https://github.com/YunoHost-Apps/owntracks_ynh/issues>

## Developer info

Please send your pull request to the [`testing` branch](https://github.com/YunoHost-Apps/owntracks_ynh/tree/testing).

To try the `testing` branch, please proceed like that:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/owntracks_ynh/tree/testing --debug
or
sudo yunohost app upgrade owntracks -u https://github.com/YunoHost-Apps/owntracks_ynh/tree/testing --debug
```

**More info regarding app packaging:** <https://yunohost.org/packaging_apps>
