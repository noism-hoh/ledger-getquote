# Example scripts

## getquote-vnd

This script fetches exchange rate of some commodities to Vietnamese Dong from a range of different websites.

Supported commodity types:

| Type           | Source                                                                                   | Fetch method | Multiple commodities available |
|----------------|------------------------------------------------------------------------------------------|--------------|:------------------------------:|
| US dollar      | [SBV's central USD rate](https://www.sbv.gov.vn/TyGia/faces/Aiber.jspx)                  | Web scraping | :x:                            |
| Fiat currency  | [SBV's cross rates for tax evaluation](https://www.sbv.gov.vn/TyGia/faces/Erfciaed.jspx) | Web scraping | :heavy_check_mark:             |
| Tael of gold   | [SJC](http://sjc.com.vn/giavang)                                                         | Web scraping | :x:                            |
| Tael of silver | [Silver Moon Company](http://http://www.bacmattrang.com/)                                | Web scraping | :x:                            |
| Cryptocurrency | [CoinGecko](https://www.coingecko.com/api)                                               | API          | :heavy_check_mark:             |
| Stock or ETF   | [BIDV Securities Company](http://www.bsc.com.vn)                                         | Web scraping | :heavy_check_mark:             |
