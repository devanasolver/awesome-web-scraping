<h1 align="center">Awesome Web Scraping and Data Collection</h1>

<p align="center"><img src="assets/banner.png" alt="Awesome Web Scraping and Data Collection" width="100%"></p>

<p align="center">
<a href="https://awesome.re"><img src="https://awesome.re/badge.svg" alt="Awesome"></a>
<img src="https://img.shields.io/badge/PRs-welcome-brightgreen" alt="PRs welcome">
<img src="https://img.shields.io/badge/license-CC0--1.0-blue" alt="License CC0 1.0">
<a href="https://github.com/devanasolver/awesome-web-scraping/commits/main"><img src="https://img.shields.io/github/last-commit/devanasolver/awesome-web-scraping" alt="Last commit"></a>
</p>

<p align="center">
<a href="https://github.com/devanasolver"><img src="https://img.shields.io/badge/Follow-@devanasolver-181717?style=for-the-badge&logo=github" alt="Follow on GitHub"></a>
<a href="https://github.com/devanasolver/awesome-web-scraping/stargazers"><img src="https://img.shields.io/github/stars/devanasolver/awesome-web-scraping?style=for-the-badge&logo=github&label=Star%20this%20list" alt="Star this list"></a>
<a href="https://buymeacoffee.com/isaac49"><img src="https://img.shields.io/badge/Buy%20me%20a%20coffee-isaac49-ffdd00?style=for-the-badge&logo=buymeacoffee&logoColor=black" alt="Buy me a coffee"></a>
</p>

> Open-source crawlers, scraping frameworks, parsers, browser tools and data extraction with AI. Every entry shows its license.

**Rules of this list:** every repo exists, is public, is not archived, states a license and has had a commit in the last year. One plain sentence each. Star counts and claims are the authors' own, we did not test every tool. Checked 2026-10-18. See [CONTRIBUTING.md](CONTRIBUTING.md).

## Contents

- [Crawling frameworks](#crawling-frameworks)
- [Parsers and extractors](#parsers-and-extractors)
- [Browser-based scraping](#browser-based-scraping)
- [AI and LLM extraction](#ai-and-llm-extraction)
- [Scraping APIs and self-hosted services](#scraping-apis-and-self-hosted-services)
- [Proxies and rotation](#proxies-and-rotation)
- [Datasets and archives](#datasets-and-archives)
- [Change monitoring](#change-monitoring)
- [How to choose](#how-to-choose)
- [Contributing](#contributing)

## Crawling frameworks

Fast crawlers with queues and retries.

- [apify/crawlee](https://github.com/apify/crawlee) ![stars](https://img.shields.io/github/stars/apify/crawlee?style=flat&label=%E2%98%85) - Web scraping and browser automation library for Node.js. _(Apache-2.0)_
- [gocolly/colly](https://github.com/gocolly/colly) ![stars](https://img.shields.io/github/stars/gocolly/colly?style=flat&label=%E2%98%85) - Fast and elegant scraping framework for Go. _(Apache-2.0)_
- [scrapy/scrapy](https://github.com/scrapy/scrapy) ![stars](https://img.shields.io/github/stars/scrapy/scrapy?style=flat&label=%E2%98%85) - Fast Python framework for crawling sites and extracting data. _(BSD-3-Clause)_

## Parsers and extractors

Pull structured data out of HTML and documents.

- [adbar/trafilatura](https://github.com/adbar/trafilatura) ![stars](https://img.shields.io/github/stars/adbar/trafilatura?style=flat&label=%E2%98%85) - Python tool to gather text and metadata from the web. _(Apache-2.0)_
- [camelot-dev/camelot](https://github.com/camelot-dev/camelot) ![stars](https://img.shields.io/github/stars/camelot-dev/camelot?style=flat&label=%E2%98%85) - Extract tables from PDF files. _(MIT)_
- [cheeriojs/cheerio](https://github.com/cheeriojs/cheerio) ![stars](https://img.shields.io/github/stars/cheeriojs/cheerio?style=flat&label=%E2%98%85) - Fast jQuery-like HTML parsing for Node.js. _(MIT)_
- [codelucas/newspaper](https://github.com/codelucas/newspaper) ![stars](https://img.shields.io/github/stars/codelucas/newspaper?style=flat&label=%E2%98%85) - News and article extraction and curation in Python. _(MIT)_
- [jhy/jsoup](https://github.com/jhy/jsoup) ![stars](https://img.shields.io/github/stars/jhy/jsoup?style=flat&label=%E2%98%85) - Java HTML parser with a jQuery-like API. _(MIT)_
- [jsvine/pdfplumber](https://github.com/jsvine/pdfplumber) ![stars](https://img.shields.io/github/stars/jsvine/pdfplumber?style=flat&label=%E2%98%85) - Extract text and tables from PDFs. _(MIT)_
- [lxml/lxml](https://github.com/lxml/lxml) ![stars](https://img.shields.io/github/stars/lxml/lxml?style=flat&label=%E2%98%85) - Python bindings for libxml2 and libxslt. _(BSD-3-Clause)_
- [mozilla/readability](https://github.com/mozilla/readability) ![stars](https://img.shields.io/github/stars/mozilla/readability?style=flat&label=%E2%98%85) - Standalone version of the Firefox Reader View library. _(Apache-2.0)_
- [scrapy/parsel](https://github.com/scrapy/parsel) ![stars](https://img.shields.io/github/stars/scrapy/parsel?style=flat&label=%E2%98%85) - Extract data from HTML and XML with XPath and CSS selectors. _(BSD-3-Clause)_

## Browser-based scraping

Handle JavaScript sites.

- [browserless/browserless](https://github.com/browserless/browserless) ![stars](https://img.shields.io/github/stars/browserless/browserless?style=flat&label=%E2%98%85) - Headless browser service for automation and scraping. _(check repo)_
- [daijro/camoufox](https://github.com/daijro/camoufox) ![stars](https://img.shields.io/github/stars/daijro/camoufox?style=flat&label=%E2%98%85) - Anti-detect browser for scraping, built on Firefox. _(MPL-2.0)_
- [Kaliiiiiiiiii-Vinyzu/patchright](https://github.com/Kaliiiiiiiiii-Vinyzu/patchright) ![stars](https://img.shields.io/github/stars/Kaliiiiiiiiii-Vinyzu/patchright?style=flat&label=%E2%98%85) - Undetected version of Playwright. _(Apache-2.0)_
- [microsoft/playwright](https://github.com/microsoft/playwright) ![stars](https://img.shields.io/github/stars/microsoft/playwright?style=flat&label=%E2%98%85) - Browser automation across Chromium, Firefox and WebKit. _(Apache-2.0)_
- [puppeteer/puppeteer](https://github.com/puppeteer/puppeteer) ![stars](https://img.shields.io/github/stars/puppeteer/puppeteer?style=flat&label=%E2%98%85) - JavaScript API to control Chrome and Firefox. _(Apache-2.0)_
- [SeleniumHQ/selenium](https://github.com/SeleniumHQ/selenium) ![stars](https://img.shields.io/github/stars/SeleniumHQ/selenium?style=flat&label=%E2%98%85) - Browser automation framework and ecosystem. _(Apache-2.0)_

## AI and LLM extraction

Turn pages into clean text or JSON for models.

- [browser-use/browser-use](https://github.com/browser-use/browser-use) ![stars](https://img.shields.io/github/stars/browser-use/browser-use?style=flat&label=%E2%98%85) - Make websites accessible for AI agents. _(MIT)_
- [firecrawl/firecrawl](https://github.com/firecrawl/firecrawl) ![stars](https://img.shields.io/github/stars/firecrawl/firecrawl?style=flat&label=%E2%98%85) - Turn websites into clean markdown or structured data for language models. _(AGPL-3.0)_
- [firecrawl/firecrawl](https://github.com/firecrawl/firecrawl) ![stars](https://img.shields.io/github/stars/firecrawl/firecrawl?style=flat&label=%E2%98%85) - Turn websites into clean data for language models. _(AGPL-3.0)_
- [jina-ai/reader](https://github.com/jina-ai/reader) ![stars](https://img.shields.io/github/stars/jina-ai/reader?style=flat&label=%E2%98%85) - Convert any URL into LLM-friendly text. _(Apache-2.0)_
- [microsoft/markitdown](https://github.com/microsoft/markitdown) ![stars](https://img.shields.io/github/stars/microsoft/markitdown?style=flat&label=%E2%98%85) - Convert files and office documents to Markdown. _(MIT)_
- [ScrapeGraphAI/Scrapegraph-ai](https://github.com/ScrapeGraphAI/Scrapegraph-ai) ![stars](https://img.shields.io/github/stars/ScrapeGraphAI/Scrapegraph-ai?style=flat&label=%E2%98%85) - Python scraper that uses language models and graph logic. _(MIT)_
- [unclecode/crawl4ai](https://github.com/unclecode/crawl4ai) ![stars](https://img.shields.io/github/stars/unclecode/crawl4ai?style=flat&label=%E2%98%85) - Open-source web crawler and scraper made for AI use. _(Apache-2.0)_

## Scraping APIs and self-hosted services

Run your own scraping API.

- [DIYgod/RSSHub](https://github.com/DIYgod/RSSHub) ![stars](https://img.shields.io/github/stars/DIYgod/RSSHub?style=flat&label=%E2%98%85) - Generate RSS feeds from almost anything. _(AGPL-3.0)_
- [FreshRSS/FreshRSS](https://github.com/FreshRSS/FreshRSS) ![stars](https://img.shields.io/github/stars/FreshRSS/FreshRSS?style=flat&label=%E2%98%85) - Self-hosted RSS feed aggregator. _(AGPL-3.0)_
- [huginn/huginn](https://github.com/huginn/huginn) ![stars](https://img.shields.io/github/stars/huginn/huginn?style=flat&label=%E2%98%85) - Build agents that watch the web and act on your behalf. _(MIT)_
- [RSSHub/RSSHub](https://github.com/RSSHub/RSSHub) ![stars](https://img.shields.io/github/stars/RSSHub/RSSHub?style=flat&label=%E2%98%85) - Generate RSS feeds from almost anything. _(AGPL-3.0)_

## Proxies and rotation

Manage IPs and request headers.

- [bogdanfinn/tls-client](https://github.com/bogdanfinn/tls-client) ![stars](https://img.shields.io/github/stars/bogdanfinn/tls-client?style=flat&label=%E2%98%85) - Go HTTP client with browser TLS fingerprints. _(BSD-4-Clause)_
- [encode/httpx](https://github.com/encode/httpx) ![stars](https://img.shields.io/github/stars/encode/httpx?style=flat&label=%E2%98%85) - Fully featured HTTP client for Python. _(BSD-3-Clause)_
- [jhao104/proxy_pool](https://github.com/jhao104/proxy_pool) ![stars](https://img.shields.io/github/stars/jhao104/proxy_pool?style=flat&label=%E2%98%85) - Python crawler proxy IP pool. _(MIT)_
- [lexiforest/curl_cffi](https://github.com/lexiforest/curl_cffi) ![stars](https://img.shields.io/github/stars/lexiforest/curl_cffi?style=flat&label=%E2%98%85) - Python binding for curl-impersonate, with browser TLS fingerprints. _(MIT)_
- [psf/requests](https://github.com/psf/requests) ![stars](https://img.shields.io/github/stars/psf/requests?style=flat&label=%E2%98%85) - Simple HTTP library for Python. _(Apache-2.0)_

## Datasets and archives

Archive pages and keep copies.

- [ArchiveBox/ArchiveBox](https://github.com/ArchiveBox/ArchiveBox) ![stars](https://img.shields.io/github/stars/ArchiveBox/ArchiveBox?style=flat&label=%E2%98%85) - Self-hosted internet archiving, saves pages in many formats. _(MIT)_
- [commoncrawl/cc-pyspark](https://github.com/commoncrawl/cc-pyspark) ![stars](https://img.shields.io/github/stars/commoncrawl/cc-pyspark?style=flat&label=%E2%98%85) - Process Common Crawl data with Apache Spark and Python. _(MIT)_
- [gildas-lormeau/SingleFile](https://github.com/gildas-lormeau/SingleFile) ![stars](https://img.shields.io/github/stars/gildas-lormeau/SingleFile?style=flat&label=%E2%98%85) - Browser extension and CLI to save a complete page as one HTML file. _(AGPL-3.0)_
- [internetarchive/heritrix3](https://github.com/internetarchive/heritrix3) ![stars](https://img.shields.io/github/stars/internetarchive/heritrix3?style=flat&label=%E2%98%85) - Internet Archive's open-source web crawler. _(check repo)_
- [webrecorder/browsertrix-crawler](https://github.com/webrecorder/browsertrix-crawler) ![stars](https://img.shields.io/github/stars/webrecorder/browsertrix-crawler?style=flat&label=%E2%98%85) - Run a high-fidelity browser-based crawler in a single Docker container. _(AGPL-3.0)_
- [webrecorder/pywb](https://github.com/webrecorder/pywb) ![stars](https://img.shields.io/github/stars/webrecorder/pywb?style=flat&label=%E2%98%85) - Python web archiving toolkit for replaying archived sites. _(GPL-3.0)_

## Change monitoring

Watch pages and get alerts.

- [dgtlmoon/changedetection.io](https://github.com/dgtlmoon/changedetection.io) ![stars](https://img.shields.io/github/stars/dgtlmoon/changedetection.io?style=flat&label=%E2%98%85) - Watch web pages for changes and get alerts, self-hosted. _(Apache-2.0)_
- [louislam/uptime-kuma](https://github.com/louislam/uptime-kuma) ![stars](https://img.shields.io/github/stars/louislam/uptime-kuma?style=flat&label=%E2%98%85) - Self-hosted uptime monitoring tool. _(MIT)_

## How to choose

- **Read robots.txt and the site's terms.** Some sites forbid scraping.
- **Be gentle.** Rate limit your requests and cache pages.
- **Personal data is regulated.** Check GDPR and local law before you collect it.
- **Prefer an official API** when one exists.

## Contributing

See [CONTRIBUTING.md](CONTRIBUTING.md). One entry per pull request, plain words, real sources only.

## About

Maintained by [@devanasolver](https://github.com/devanasolver). Listings follow the rules in CONTRIBUTING.

## Sponsor me

If this list is useful, [buy me a coffee](https://buymeacoffee.com/isaac49).
