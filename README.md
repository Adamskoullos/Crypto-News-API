# Crypto News API

**[Access for free on Rapid API](https://rapidapi.com/adamskoullos@gmail.com/api/crypto-pulse/)**

Articles are aggregated and curated by industry leading [Investing.com](https://www.investing.com/news/cryptocurrency-news). This data is collected every minute then washed through our algorythm to add relevant coin tags which inlcude icons. All advertising content is removed leaving clean data that can be easily filtered and sorted using the tags. The icons allow the user to quickly identify articles of interest.

One endpoint, no pagination, just the most relevant price sensitive crypto news over the last 24 hours. A snapshot of what is currently driving sentiment and price.

Example article:

```json
{
  "title":"Bitcoin’s 50% Correction Is No Big Deal, Says Morgan Stanley"
  "link":"https://www.investing.com/news/cryptocurrency-news/bitcoins-50-correction-is-no-big-deal-says-morgan-stanley-2754528"
  "description":"Bitcoin has experienced 15 corrections since its inception in 2009. The asset’s current decline all the way down from its all time high of $69K is within its..."
  "source":"By DailyCoin"
  "date":"12 hours ago"
  "tags":[
    {
      "symbol":"BTC"
      "name":"Bitcoin"
      "icon":"https://cdn.jsdelivr.net/gh/atomiclabs/cryptocurrency-icons@bea1a9722a8c63169dcc06e86182bf2c55a76bbc/svg/color/btc.svg"
    }
  ]
}
```
