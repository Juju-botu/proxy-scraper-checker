# Proxy Scraper Checker 🤖

**You can get proxies under the corresponding folders (updated every ~15 minutes)**

Get and check free anonymous HTTP, SOCKS4, SOCKS5 proxies from different sources. Supports getting exit-node's geolocation for each proxy.

Note: the proxies used to be updated under [monosans/proxy-list](https://github.com/monosans/proxy-list) but since it is not working anymore, I am running Actions and uploading the lists on this repository :)

## Note about git clone

To make `git clone` much faster, use the `--depth 1` flag.

## Usage ⚙️

- Make sure `Python` version is 3.6 or higher.
- Install dependencies from `requirements.txt`.
- Edit `config.py` according to your preference.
- Run `main.py`.

## Folders description 📁

When the script finishes running, the following folders will be created:

- `proxies` - proxies with any anonymity level.

- `proxies_anonymous` - anonymous proxies.

- `proxies_geolocation` - same as `proxies`, but including exit-node's geolocation.

- `proxies_geolocation_anonymous` - same as `proxies_anonymous`, but including exit-node's geolocation.

Geolocation format is ip:port::Country::Region::City.

## Buy me a coffee ☕
(not "me" me, buy it for the original developer!)
Ask for details in [Telegram](https://t.me/monosans) or [VK](https://vk.com/id607137534).

## License 📜

[MIT](LICENSE) 

This product includes GeoLite2 data created by MaxMind, available from http://www.maxmind.com.
