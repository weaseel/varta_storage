# Integration Blueprint

[![GitHub Release][releases-shield]][releases]
[![License][license-shield]](LICENSE)
[![hacs][hacsbadge]][hacs]
[![Community Forum][forum-shield]][forum]

_Home Assistant Integration to integrate with [VARTA Storage][varta_storage]._

**This integration will set up the following platforms.**

Platform | Description
-- | --
`sensor` | Shows various information's from the VARTA Batteries like current charge/discharge power, state of charge, maintenance informations, fan status, totals for consumption, power to grid and power from grid

## Installation

1. Using the tool of choice open the directory for your HA configuration (where you find `configuration.yaml`).
1. If you do not have a `custom_components` directory there, you need to create it.
1. In the `custom_components` directory create a new folder called `varta_storage`.
1. Download _all_ the files from the `custom_components/varta_storage/` directory in this repository.
1. Place the files you downloaded in the new directory you created.
1. Restart Home Assistant
1. In the HA UI go to "Configuration" -> "Integrations" click "+" and search for "VARTA Storage"

## Configuration is done in the UI

<!---->

## Contributions are welcome!

If you want to contribute to this please read the [Contribution guidelines](CONTRIBUTING.md)

***

[hacs]: https://github.com/hacs/integration
[hacsbadge]: https://img.shields.io/badge/HACS-Custom-orange.svg?style=for-the-badge
[forum-shield]: https://img.shields.io/badge/community-forum-brightgreen.svg?style=for-the-badge
[forum]: https://community.home-assistant.io/
[license-shield]: https://img.shields.io/github/license/ludeeus/integration_blueprint.svg?style=for-the-badge
[releases-shield]: https://img.shields.io/github/release/ludeeus/integration_blueprint.svg?style=for-the-badge
[releases]: https://github.com/Vip0r/vartastorage-hacs/releases
[varta_storage]: https://www.varta-ag.com/