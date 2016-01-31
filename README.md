#Crude Oil Price (Analysis)
#Updated: January, 31, 2016

What variables drive spikes and dives in the price of crude oil? 
	
With a recent wide deflation of crude oil prices internationally and the price of crude oil hitting decade lows, the oil industry has become a contested area of speculation, and some analysts suggest that the price of oil may go as low as $20 per barrel. Historically this has not been the first time there have been sharp appreciation and depreciation of oil prices during the 1970’s the price of crude oil had doubled while in 1990’s the price of oil was halved. Understanding what drives these oil consumption trends and what variables affect the price of crude oil will help protect companies from such oil shocks. 
The project itself will utilize data sourced from Quandl, a search engine for economic data. The data include the price of crude oil sold by OPEC, Organization of Petroleum Exporting Countries, USD to Rubles Exchange Rate, USD to Canadian Dollars Exchange Rate, and Gold in USD Value. The timeline will range from January 10th, 2010 to January 25th, 2016 and plotted based off weekly data. 
OPEC includes: Algeria, Angola, Ecuador, Iran, Iraq, Kuwait, Libya, Nigeria, Qatar, Saudi Arabia, United Arab Emirates and Venezuela. The OPEC’s database of crude oil prices is essential to this research. OPEC retains 80% of the world’s oil reserves with a majority of the reserves in the Middle East, amounting to around 66% of the OPEC total. The data was collected over several decades, but only recently uploaded online, and the data itself was collected by the economic cartel as all members must report their oil data. 
U.S. crude oil exports/imports is also vital to this research. With a recent lift of a ban preventing oil companies on exporting crude oil to international markets, the importance of U.S. crude oil exportation has a serious impact on the international oil market and has affected how much oil the U.S. imports. In 2013, the U.S. oil industry has produced more crude oil than that of Russian and Saudi Arabian oil producers. The U.S. Energy Information Administration collected the dataset from Bureau of Labor Statistics on oil imports throughout the decades since 1920’s. 
USD to Rubles Exchange Rate and USD to Canadian Dollars Exchange Rate showcase the exchange rate between US Dollars to Russian Rubles and Canadian Dollars. Currency data is important in this crude oil price analysis as it is well documented that currencies of countries with large oil exporting economies have closely related correlations with crude oil prices internationally. The Foreign Exchange Rate Database which is sourced from major banks and dealers, and offers synchronized FX rates for 168 currencies with history to 2000’s. 
Gold priced in USD showcases the price of Gold in US Dollars. The relation Gold has on Crude Oil Prices is well documented. The overall relationship is well documented. Often times commodity investors spread there investments in other high valued commodities to neutralize the risk of investing in other commodities such as oil, which only now like the price of gold has fluctuated highly. 
All the data will be plotted accordingly and a simple linear regression will be run on the data. A boxplot will be then calculated on the OPEC crude oil data to isolate various outliers. Outliers that lie within three to four standard deviations of the mean will than be labeled as an “oil shock.” The outlier data will than be paired with relevant news related events in order to determine a qualitative context of the oil market. All the data sets will also be exponentially smoothed too find a seasonal trend throughout the data sets and a correlation between the OPEC oil prices and USD and Ruble exchange rates. In addition, a correlation will be calculated for OPEC oil prices and U.S. exports/imports. A weighted, moving average of the monthly crude oil prices will be used to project future values and a probability of these outliers will be calculated and projected onto future values. The outcome variable is the OPEC crude oil prices. The main predictor variables are the USD/RUB exchange rates and US oil imports/exports. 
Project 2:
The objective of this project is to analyze three major data sets: USD to Rubles Exchange Rate, and the U.S crude oil production, in relation to crude oil prices. A correlation and regression analysis will be conducted on these data with the crude oil prices. The purpose for these analyses is to find data sets that accurately and precisely indicate the general trend in oil prices. 

Figure A:

Figure B:

Figure C:

Figure D:

The graph in Figure A showcases crude oil prices from 2010 to the year 2014. There is a clear incline in the year 2011, which is during the Arab Spring with the revolutions in Syria, Libya, and Egypt which both countries are major crude oil exporters. In the year 2012, there is also a large crude oil spike in 2012, which during disintegration of Syria and Egypt. 
Figure E: OPEC and USD/RUB Data

Min.
1st Quantile
Median
Mean
3rd Quantile
Max
68.47
81.04
104.50
98.15
110.50
124.20
27.45
29.34
30.44
30.27
31.15
33.79
 
The graph in Figure B and C showcase USD and Ruble exchange rates. The correlation between the data is -0.5225194 and -0.5203204, which showcases a negative correlation between the data and illustrates a moderate negative relationship. Figure E is a table of all data and statistical calculations. The variable of primary interest is the Crude Oil Prices. The three variables associated with Crude Oil prices are the average, variance, and mode. 
The graph in Figure D showcases the price of gold in U.S. dollars The correlation between the data is 0.6539211, which illustrates a significant moderate positive correlation between the price of oil and gold. 
	

	Figure 1:

	Figure 2:

  Figure 3:

	Figure 4:

	A variable called spikes was calculated by subtracting the current rate or price minus the previous rate or price. The histograms show the distribution of spikes in prices, which often coincide with each other. 
	Figure 1a:

	Figure 1b:

	



Figure 1c:

I would like to implement a weighted, moving average along all the months in order to project them unto future values. The weighted moving average will take in account of the seasonality and cyclical nature of the crude oil prices. In addition, I would like to assign weights to several of the factor variables of USD and Ruble Exchange Rates and USD and Canadian Dollar Exchange Rates and Gold in US dollars based on the correlation level associated with Crude Oil Prices. A weighted, moving average predictor will take these variables and weights into account in order to predict better future values of crude oil prices. 








Bibliography:

Unalmis, Deren, Ibrahim Unalmis, and D. Filiz Unsal. On the Sources and Consequences of Oil Price Shocks: The Role of Storage (2012): 1-41.IMF Working Paper. Web. 24 Jan. 2016. <https://www.imf.org/external/pubs/ft/wp/2012/wp12270.pdf>.


Marcel Fratzscher, Daniel Schneider, and Ine Van Robays. "Oil Prices, Exchange Rates and Asset Prices." SSRN Electronic Journal SSRN Journal (n.d.): 1-47. Https://www.ecb.europa.eu. Web. 14 Jan. 2016. <https://www.ecb.europa.eu/pub/pdf/scpwps/ecbwp1689.pdf>.

Sharples, Ben, and Grant Smith. "How Low Can Oil Go? Goldman Says $20 a Barrel Is a Possibility." Bloomberg.com. Bloomberg, 11 September 2015. Web. 15 Jan. 2016. <http://www.bloomberg.com/news/articles/2015-09-11/-20-oil-possible-for-goldman-as-forecasts-cut-on-growing-glut>.

Katakey, Rakteem. “U.S. Ousts Russia as Top World Oil, Gas Producer in BP Data” Bloomberg.com. Bloomberg, 10 June 2015. Web. 15 Jan. 2016. <http://www.bloomberg.com/news/articles/2015-06-10/u-s-ousts-russia-as-world-s-top-oil-gas-producer-in-bp-report>.

"OPEC: Share of World Crude Oil Reserves." OPEC. N.p., n.d. Web. 15 Jan. 2016. <http://www.opec.org/opec_web/en/data_graphs/330.htm>.

Šimáková, Jana. "The Relationship Between Crude Oil Prices and Exchange Rates." Analysis of the Relationship between Oil and Gold Prices 11.05 (2012): n. pag. Http://www.opf.slu.cz/. Http://www.opf.slu.cz/. Web. 29 Jan. 2016. <http://www.opf.slu.cz/kfi/icfb/proc2011/pdf/58_Simakova.pdf>.


OPEC Crude Oil:
https://www.quandl.com/data/OPEC/ORB-OPEC-Crude-Oil-Price

USD/RUB:
https://www.quandl.com/data/CUR/RUB-Currency-Exchange-Rates-USD-RUB

USD/CAD:
https://www.quandl.com/data/CUR/CAD-Currency-Exchange-Rates-USD-CAD

Gold in USD:
https://www.quandl.com/data/BUNDESBANK/BBK01_WT5511-Gold-Price-USD



Other References:

http://www.bbc.com/news/business-35136831

http://www.r-bloggers.com/a-practical-introduction-to-garch-modeling/

https://statistics.laerd.com/statistical-guides/types-of-variable.php

http://www.nrcan.gc.ca/energy/fuel-prices/4605

https://www.eia.gov/finance/markets/demand-nonoecd.cfm
