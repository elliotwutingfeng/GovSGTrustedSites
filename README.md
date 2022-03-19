# Government of Singapore Trusted Sites

![Python](https://img.shields.io/badge/Python-FFD43B?style=for-the-badge&logo=python&logoColor=blue)
![AIOHTTP](https://img.shields.io/badge/AIOHTTP-2C5BB4?style=for-the-badge&logo=aiohttp&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=for-the-badge&logo=github-actions&logoColor=white)

[![GitHub license](https://img.shields.io/badge/LICENSE-BSD--3--CLAUSE-GREEN?style=for-the-badge)](LICENSE)
[![scraper](https://img.shields.io/github/workflow/status/elliotwutingfeng/GovSGTrustedSites/scraper?label=SCRAPER&style=for-the-badge)](https://github.com/elliotwutingfeng/GovSGTrustedSites/actions/workflows/scraper.yml)
<img src="https://img.shields.io/tokei/lines/github/elliotwutingfeng/GovSGTrustedSites?label=Total%20Allowlist%20URLS&style=for-the-badge" alt="Total Allowlist URLs"/>

Machine-readable `.txt` allowlist of trusted site URLs from the [Government of Singapore](https://www.gov.sg/trusted-sites) website, updated once a day.

The URLs in this allowlist are compiled by the **Government of Singapore**.

**Disclaimer:** _This project is not sponsored, endorsed, or otherwise affiliated with the Government of Singapore._

## Allowlist download
You may download the allowlist [here](govsg-trusted-sites.txt?raw=1)

## Requirements

-   Python >= 3.9.10

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

&nbsp;

<sup>These files are provided "AS IS", without warranty of any kind, express or implied, including but not limited to the warranties of merchantability, fitness for a particular purpose and noninfringement. In no event shall the authors or copyright holders be liable for any claim, damages or other liability, arising from, out of or in connection with the files or the use of the files.</sup>

<sub>Any and all trademarks are the property of their respective owners.</sub>
