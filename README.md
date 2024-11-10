# Government of Singapore Trusted Sites

![Python](https://img.shields.io/badge/Python-FFD43B?style=for-the-badge&logo=python&logoColor=blue)
![AIOHTTP](https://img.shields.io/badge/AIOHTTP-2C5BB4?style=for-the-badge&logo=aiohttp&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=for-the-badge&logo=github-actions&logoColor=white)

[![License](https://img.shields.io/badge/LICENSE-BSD--3--CLAUSE-GREEN?style=for-the-badge)](LICENSE)
[![scraper](https://img.shields.io/github/actions/workflow/status/elliotwutingfeng/GovSGTrustedSites/scraper.yml?branch=main&label=SCRAPER&style=for-the-badge)](https://github.com/elliotwutingfeng/GovSGTrustedSites/actions/workflows/scraper.yml)
<img src="https://tokei-rs.onrender.com/b1/github/elliotwutingfeng/GovSGTrustedSites?label=Total%20Allowlist%20URLS&style=for-the-badge" alt="Total Allowlist URLs"/>

Machine-readable `.txt` allowlist of trusted site URLs from the [Government of Singapore](https://www.gov.sg/trusted-sites) website.

**Disclaimer:** _This project is not sponsored, endorsed, or otherwise affiliated with the Government of Singapore._

## Allowlist download

| File | Download |
|:-:|:-:|
| allowlist.txt | [:floppy_disk:](allowlist.txt?raw=true) |

## Requirements

-   Python 3.12+

## Setup instructions

`git clone` and `cd` into the project directory, then run the following

```bash
python3 -m venv venv
venv/bin/python3 -m pip install --upgrade pip
venv/bin/python3 -m pip install -r requirements.txt
```

## Usage

```bash
venv/bin/python3 scraper.py
```
