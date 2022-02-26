# Crypto News API

![Screenshot from 2022-02-14 07-32-04](https://user-images.githubusercontent.com/73107656/153819614-93a00176-3d34-40f1-862f-9a17f9f74941.png)

**[Access for free on Rapid API](https://rapidapi.com/adamskoullos-amoQpTtXMJ5/api/crypto-pulse/)**

**[Live Demo Page](https://crypto-news-demo.netlify.app/)**

Source articles are aggregated and curated by industry leading [Investing.com](https://www.investing.com/news/cryptocurrency-news). This data is mined every minute, advertising content is removed, coin tags are added and articles are created and saved to the database. All requests pull direct from the database allowing for fast response times.

One endpoint, no pagination, just the most relevant price sensitive crypto news over the last 24 hours. A snapshot of what is currently driving sentiment and price.

- **`Disclaimer`**: The API is currently in BETA and running on a free tier, meaning the first time you hit the endpoint you may have to wake the server up.
- **`Trick`**: set your app to hit the endpoint on initial load so by the time the user goes to the news page the server is active and response times will be fast.

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
      "icon":"https://cdn.jsdelivr.net/gh/londs/cryptocurrency-icons@lon722a8c63169dcc06e86182bf2c55a76bbc/bitcoin.svg"
    }
  ]
}
```
