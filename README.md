# Crypto Market Analysis (past 365 days)
Analysis project on the cryptocurrency market trends by analysing on-chain and market data for BTC and other major altcoins using python and Tableau. 

[Colab Link](https://colab.research.google.com/drive/1CaKjT2y6CpQAkV6Bs9eywe1iHCDfz6A3?usp=sharing)

[Tableau Link](https://public.tableau.com/views/CryptoMarketCycleAnalysis/Dashboard1?:language=en-US&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link)

This project has been powered by [CoinGecko API](https://www.coingecko.com/en/api)

---
# Analysing Market Cycle for cryptocurrencies based on the past 365 days (updated as of 25-09-25)

This analysis inlcudes Bitcoin (BTC), Ethereum (ETH), and the top 10 altcoins (based on market cap) as of 21-09-2025.

Assets Covered:

BTC, ETH (benchmarks)

Altcoins: XRP, BNB, SOL, DOGE, ADA, TRX, LINK, HYPE, AVAX, SUI

---
# Metrics used in this analysis

Pulled from API:
1. Price
2. Market Cap
3. Total Volume (24 Hrs)

Derived from data:
1. 7-Day rolling returns
2. 7-Day weighted rolling returns
3. % of market cap
4. Total volume
5. % of total volume
   
<img width="903" height="788" alt="image" src="https://github.com/user-attachments/assets/c882dcba-dcda-4d06-ab08-1259618c4ccb" />
<img width="987" height="788" alt="image" src="https://github.com/user-attachments/assets/5673f943-4fa3-4c75-80ef-28714a1cd039" />
<img width="985" height="782" alt="image" src="https://github.com/user-attachments/assets/22bf25cb-0906-43f1-aa4b-6d15eaee8fd3" />

---
# Summary of Insights

**1. Altcoins (and ETH) are significantly more volatile than BTC**

While ETH has been viewed as a more conservative coin, we can see from the 7-D rolling returns that its volatility can be compared to the altcoin bucket.  
Trading volume spikes up when we see strong returns from ETH and altcoins, due to strong public sentiment of an "altcoin season"  
The alt season can also be observed with the dip in BTC dominance.  
**For any exchanges, this period is critical for fee-generating opportunities. Spotting this early allows marketing teams to promote trending altcoins, and to potentially run short term campaigns to quickly capitalise on these short periods.**

**2. BTC continues to grow even during alt seasons**

While BTC does not move as much during alt seasons, there is still upwards growth during this period.  
Given how there is likely an influx of newcomers during who might not be willing to jump right into altcoins, **it is still worthwhile for exchanges to promote BTC promotions**  
This might give newcomers more incentive to use a particular exchange, before moving on to altcoins, and eventually back to BTC once alt season is over.


---
# Additional Thoughts/Remarks
For this analysis, stablecoins were not included as their value is pegged to fiat and do not follow market cycles the same way. A future analysis could be done to explore where money moves during a risk-off sentiment.  

This analysis can be further explored with more data. Such as:
1. Past 5 years (or more) historical data - The analysis might be biased given the generally strong year crypto has had in general. This analysis might not hold true during "crypto winter" periods.
2. Social media sentiment data - Tie in with the capitalisation on alt season, social media sentiment could be a strong indicator.
3. Volume per region - Given how different exchanges operates in different regions, exchanges might need to have regional data to determine if the trend is accurately reflected for their target audience. This also gives them an opportunity to explore the potential in other markets.
4. Remaining altcoins - While the assets in this analysis is likely over 80% of the total crypto market cap, the addition of the remaining altcoins will allow exchanges to better determine their listing strategies. 




