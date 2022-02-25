# Government of Singapore Trusted Sites

![Python](https://img.shields.io/badge/Python-FFD43B?style=for-the-badge&logo=python&logoColor=blue)
![AIOHTTP](https://img.shields.io/badge/AIOHTTP-2C5BB4?style=for-the-badge&logo=aiohttp&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=for-the-badge&logo=github-actions&logoColor=white)

[![GitHub license](https://img.shields.io/badge/LICENSE-BSD--3--CLAUSE-GREEN?style=for-the-badge)](LICENSE)

Generate a machine-readable `.txt` allowlist of trusted site URLs from the [Government of Singapore](https://www.gov.sg/trusted-sites) website.

**Disclaimer:** _This project is not sponsored, endorsed, or otherwise affiliated with the Government of Singapore._

## Requirements

-   Python >= 3.9.13

## Setup instructions

`git clone` and `cd` into the project directory, then run the following

```bash
pip3 install -r requirements.txt
```

## Usage

```bash
python3 scraper.py
```

## Libraries/Frameworks used

-   [BeautifulSoup4](https://beautiful-soup-4.readthedocs.io)
-   [AIOHTTP](https://docs.aiohttp.org/en/stable)
