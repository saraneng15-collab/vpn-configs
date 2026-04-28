# VPN Configs

[![Frequent Update](https://github.com/pog7x/vpn-configs/actions/workflows/frequent_update.yml/badge.svg)](https://github.com/pog7x/vpn-configs/actions/workflows/frequent_update.yml)

Automated aggregator that collects free VPN configuration files from multiple open-source repositories across GitHub and mirrors them into a single, regularly updated location.

## How It Works

1. A GitHub Actions workflow runs **every hour** on a cron schedule.
2. The script reads a curated list of source URLs from `urls.txt`.
3. Each source is fetched, deduplicated via MD5 hash comparison, and saved to the `githubmirror/` directory.
4. The table below is regenerated with the latest update timestamps.

## Configs

|Num|              File             |                                                                                Source                                                                               |Update time|Update date|
|---|-------------------------------|---------------------------------------------------------------------------------------------------------------------------------------------------------------------|-----------|-----------|
| 1 | [`1.txt`](githubmirror/1.txt) |                              [sakha1370/OpenRay](https://github.com/sakha1370/OpenRay/raw/refs/heads/main/output/all_valid_proxies.txt)                             |   17:13   | 28.04.2026|
| 2 | [`2.txt`](githubmirror/2.txt) |                                 [sevcator/5ubscrpt10n](https://raw.githubusercontent.com/sevcator/5ubscrpt10n/main/protocols/vl.txt)                                |   17:13   | 28.04.2026|
| 3 | [`3.txt`](githubmirror/3.txt) |                           [yitong2333/proxy-minging](https://raw.githubusercontent.com/yitong2333/proxy-minging/refs/heads/main/v2ray.txt)                          |   17:14   | 28.04.2026|
| 4 | [`4.txt`](githubmirror/4.txt) |                                     [acymz/AutoVPN](https://raw.githubusercontent.com/acymz/AutoVPN/refs/heads/main/data/V2.txt)                                    |   17:13   | 28.04.2026|
| 5 | [`5.txt`](githubmirror/5.txt) |                        [miladtahanian/V2RayCFGDumper](https://raw.githubusercontent.com/miladtahanian/V2RayCFGDumper/refs/heads/main/sub.txt)                       |   17:13   | 28.04.2026|
| 6 | [`6.txt`](githubmirror/6.txt) |                              [roosterkid/openproxylist](https://raw.githubusercontent.com/roosterkid/openproxylist/main/V2RAY_RAW.txt)                              |   17:13   | 28.04.2026|
| 7 | [`7.txt`](githubmirror/7.txt) |                            [Epodonios/v2ray-configs](https://github.com/Epodonios/v2ray-configs/raw/main/Splitted-By-Protocol/trojan.txt)                           |   17:13   | 28.04.2026|
| 8 | [`8.txt`](githubmirror/8.txt) |                             [CidVpn/cid-vpn-config](https://raw.githubusercontent.com/CidVpn/cid-vpn-config/refs/heads/main/general.txt)                            |   17:13   | 28.04.2026|
| 9 | [`9.txt`](githubmirror/9.txt) |[mohamadfg-dev/telegram-v2ray-configs-collector](https://raw.githubusercontent.com/mohamadfg-dev/telegram-v2ray-configs-collector/refs/heads/main/category/vless.txt)|   17:13   | 28.04.2026|
| 10|[`10.txt`](githubmirror/10.txt)|                                    [mheidari98/.proxy](https://raw.githubusercontent.com/mheidari98/.proxy/refs/heads/main/vless)                                   |   17:13   | 28.04.2026|
| 11|[`11.txt`](githubmirror/11.txt)|                           [youfoundamin/V2rayCollector](https://raw.githubusercontent.com/youfoundamin/V2rayCollector/main/mixed_iran.txt)                          |   17:13   | 28.04.2026|
| 12|[`12.txt`](githubmirror/12.txt)|                          [expressalaki/ExpressVPN](https://raw.githubusercontent.com/expressalaki/ExpressVPN/refs/heads/main/configs3.txt)                          |   17:13   | 28.04.2026|
| 13|[`13.txt`](githubmirror/13.txt)|                      [MahsaNetConfigTopic/config](https://raw.githubusercontent.com/MahsaNetConfigTopic/config/refs/heads/main/xray_final.txt)                      |   17:13   | 28.04.2026|
| 14|[`14.txt`](githubmirror/14.txt)|                                   [LalatinaHub/Mineral](https://github.com/LalatinaHub/Mineral/raw/refs/heads/master/result/nodes)                                  |   17:13   | 28.04.2026|
| 15|[`15.txt`](githubmirror/15.txt)|                  [miladtahanian/Config-Collector](https://raw.githubusercontent.com/miladtahanian/Config-Collector/refs/heads/main/mixed_iran.txt)                  |   17:13   | 28.04.2026|
| 16|[`16.txt`](githubmirror/16.txt)|                                 [Pawdroid/Free-servers](https://raw.githubusercontent.com/Pawdroid/Free-servers/refs/heads/main/sub)                                |   17:13   | 28.04.2026|
| 17|[`17.txt`](githubmirror/17.txt)|                         [MhdiTaheri/V2rayCollector_Py](https://github.com/MhdiTaheri/V2rayCollector_Py/raw/refs/heads/main/sub/Mix/mix.txt)                         |   17:13   | 28.04.2026|
| 18|[`18.txt`](githubmirror/18.txt)|                                         [free18/v2ray](https://raw.githubusercontent.com/free18/v2ray/refs/heads/main/v.txt)                                        |   17:13   | 28.04.2026|
| 19|[`19.txt`](githubmirror/19.txt)|                                [MhdiTaheri/V2rayCollector](https://github.com/MhdiTaheri/V2rayCollector/raw/refs/heads/main/sub/mix)                                |   17:13   | 28.04.2026|
| 20|[`20.txt`](githubmirror/20.txt)|                                     [Argh94/Proxy-List](https://github.com/Argh94/Proxy-List/raw/refs/heads/main/All_Config.txt)                                    |   17:13   | 28.04.2026|
| 21|[`21.txt`](githubmirror/21.txt)|                                       [shabane/kamaji](https://raw.githubusercontent.com/shabane/kamaji/master/hub/merged.txt)                                      |   17:13   | 28.04.2026|
| 22|[`22.txt`](githubmirror/22.txt)|                      [wuqb2i4f/xray-config-toolkit](https://raw.githubusercontent.com/wuqb2i4f/xray-config-toolkit/main/output/base64/mix-uri)                      |   17:13   | 28.04.2026|
| 23|[`23.txt`](githubmirror/23.txt)|                     [igareck/vpn-configs-for-russia](https://github.com/igareck/vpn-configs-for-russia/raw/refs/heads/main/BLACK_VLESS_RUS.txt)                     |   17:13   | 28.04.2026|
| 24|[`24.txt`](githubmirror/24.txt)|                                      [Mr-Meshky/vify](https://github.com/Mr-Meshky/vify/raw/refs/heads/main/configs/vless.txt)                                      |   17:13   | 28.04.2026|
| 25|[`25.txt`](githubmirror/25.txt)|                          [V2RayRoot/V2RayConfig](https://raw.githubusercontent.com/V2RayRoot/V2RayConfig/refs/heads/main/Config/vless.txt)                          |   17:13   | 28.04.2026|

## Quick Start

```bash
# Clone the repository
git clone https://github.com/pog7x/vpn-configs.git
cd vpn-configs

# Install dependencies
pip install -r requirements.txt

# Set environment variables
export GH_TOKEN="your_github_token"
export REPO_NAME="owner/repo"

# Run
python main.py
```

## Requirements

| Package | Purpose |
|---------|---------|
| [aiohttp](https://pypi.org/project/aiohttp/) | Async HTTP requests |
| [aiofiles](https://pypi.org/project/aiofiles/) | Async file I/O |
| [PyGithub](https://pypi.org/project/PyGithub/) | GitHub API integration |
| [py-markdown-table](https://pypi.org/project/py-markdown-table/) | Markdown table generation |

## Disclaimer

This project is provided for **educational and informational purposes only**. The maintainers do not host, create, or endorse any VPN configurations — all files are mirrored from publicly available open-source repositories. Use at your own risk and in compliance with your local laws.
