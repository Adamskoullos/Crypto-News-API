# Crypto News API

**[Access for free on Rapid API](https://rapidapi.com/adamskoullos@gmail.com/api/crypto-pulse/)**

Articles are aggregated and curated by industry leading [Investing.com](https://www.investing.com/news/cryptocurrency-news). This data is collected every minute then put through our algorithm to add value. The relevant coin tags and icons are added and advertising content is removed leaving clean data that can be easily filtered and sorted using the tags. The icons allow the user to quickly identify articles of interest.

One endpoint, no pagination, just the most relevant price sensitive crypto news over the last 24 hours. A snapshot of what is currently driving sentiment and price.

- **`Disclaimer`**: The API is currently in BETA and running on a free tier, meaning the first time you hit the endpoint you may have to wake the server up.
- **`Trick`**: set your app to hit the endpoint on initial load so by the time the user goes to the news page the server is active and response times will be fast. The data is scraped every minute and saved to the database, all calls pull direct from the database allowing for fast response times.

Example article:

![Screenshot from 2022-02-07 07-11-10](https://user-images.githubusercontent.com/73107656/152741595-b2777947-f943-43bf-ae95-f23d9ce1564a.png)

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
      "icon":"https://cdn.jsdelivr.net/gh/londs/cryptocurrency-icons@lon722a8c63169dcc06e86182bf2c55a76bbc/bitcoin.svg"
    }
  ]
}
```
