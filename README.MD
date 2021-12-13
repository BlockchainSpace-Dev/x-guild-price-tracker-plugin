# x-guild-price-tracker-plugin
> Xbar plugin for [$GUILD Price Tracker](https://www.coingecko.com/en/coins/blockchainspace)

<p align="center">
<img 
src="https://github.com/BlockchainSpace-Dev/x-guild-price-tracker-plugin/blob/main/README.png?raw=true" alt="$GUILD price tracker view" />
</p>

## Table of Content

* [Features](#features)
  * [Prerequisite](#prerequisite)
  * [How to Install](#how-to-install)
    * [Use with `curl` or `wget`](#use-with-curl-or-wget)
    * [Browse in Plugin](#browse-in-plugin)
* [License](#license)

   
## Features

* [x] Currency support USD, PHP, EUR, HKD, SGD, IDR
* [x] Link to coingecko and blockchainspace website

### Prerequisite
   
* [x] [Xbar](https://xbarapp.com) (_Required_) 
* [x] [Python](https://www.python.org/) (_Required_)
   
### How to Install

#### Use with `curl` or `wget`

```shell
curl -L https://github.com/BlockchainSpace-Dev/x-guild-price-tracker-plugin/blob/main/guild.1m.py\?raw=true \
  -o ~/Library/Application\ Support/xbar/plugins/guild.1m.py && chmod 0775 ~/Library/Application\ Support/xbar/plugins/guild.1m.py
```

Or

```
wget https://github.com/BlockchainSpace-Dev/x-guild-price-tracker-plugin/blob/main/guild.1m.py\?raw=true -O \
  ~/Library/Application\ Support/xbar/plugins/guild.1m.py && chmod 0775 ~/Library/Application\ Support/xbar/plugins/guild.1m.py

```

After that, Open Xbar in Applications & Open menu _**Xbar -> "Refresh all"**_

#### Browse in Plugin
1. Open menu _**Xbar -> "Plugin Browser"**_
2. Select _**"Finance"**_
3. Find _**"x-guild-price-tracker-plugin"**_
4. Click Install
