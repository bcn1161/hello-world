# Election on Twitter
For the purpose of analysis, we collected a month of tweets on Twitter using candidates' names as keywords. The data was collected from March 15 to April 15, and for the purpose of presentation, we used a sample of 5000 tweets per day. Data was cleaned and classified by candidate, discussion topic, and party identification.    
The visualization is completed by javascript libraries such as d3, dc, and crossfilter, which allows users to navigate easily by Twitter users' geographic location, candidates, parties and topics discussed in tweets, date, hour, and day of week, and also tweets' sentiment. Sentiment analysis(positve, neutral and negative) is visualized by bubble overlay chart.  
We also developed a tentative prediction model to study the potential correlation between polls and Twitter metrics. Stepwise algorithm and LASSO were used in the process of model selection. Overall, we found a significant correlation between polls, Twitter sentiment, and the volume of tweets before each election. While it by no means signifies a causal relationship between election results and Twitter activity, the correlation is worth examining and potentially indicates how online enthusiasm may be translated to real politic events.
