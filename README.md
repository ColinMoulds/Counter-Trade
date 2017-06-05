<p align="center"><img width=80% src="https://github.com/ColinMoulds/Counter-Trade/blob/master/media/counter%20core.png"></p>

[![Build Status](https://img.shields.io/badge/build-passed-brightgreen.svg)](https://github.com/ColinMoulds/Counter-Core/tree/master/Application)
[![Dependencies](https://img.shields.io/badge/dependencies-up%20to%20date-brightgreen.svg)](https://github.com/ColinMoulds/Counter-Core#prerequisites)
[![Contributions Welcome](https://img.shields.io/badge/contributions-welcome-brightgreen.svg)](https://github.com/ColinMoulds/Counter-Core/graphs/contributors)
[![License](https://img.shields.io/badge/license-MIT%20License-brightgreen.svg)](https://opensource.org/licenses/MIT)
[<img src="https://discordapp.com/api/guilds/318190682957283329/widget.png?style=shield">](https://discord.me/cdev)

# Counter Core Script

In this repository resides the counter trade script for Counter Strike : Global Offensive.

## Getting Started

This is a quickly coded website for people who want to see how these kind of websites work. Before you decide to use this script be aware, that this script, may have bugs. I also suggest looking through the code to see how it works, and if you spot an error make a pull request.

### Prices

The script gets its prices from two sources. If you don't feel comfortable with any of the API's this script uses, feel free to change them to your preferred one.

1. CSGOFast API for it's high tier items, anything that's not high tier will be ignored.
2. SteamApis.com API for market tier items, using the `safe_price` values provided by it.

### Inventory

To avoid Steam rate-limits all inventories are loaded through SteamApis.com inventory proxy. It utilizes thousands of proxies to maintain a high success rate.

### SteamApis.com

SteamApis is a paid service. You can get the API key at https://steamapis.com

**You need to enable these endpoints in the Upgrade page:**

- `market/items`
- `steam/inventory`

### Prerequisites

Required VPS standards to run the system smoothly.

```
1GB RAM VPS
Ubuntu 14.04 x64 (recommended)
```

## Built With

* [Node](https://github.com/nodejs/node/blob/master/README.md) - JavaScript Web Runtime
* [Npm](https://github.com/npm/npm) - Package Managemer

## Authors

*Initial work* - [Colin Moulds](https://github.com/ColinMoulds)

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details

## Acknowledgments

* Hat tip to anyone who's code was used
* Inspiration
* Coffee
