# ETF_replication
The objective of this project is to replicate the XLE index using optimal portfolio selection of the largest assets in the index by reducing the Tracking Error.

XLE is an energy sector index composed of the largest US companies including Exxon Mobil and Chevron. ANRJ MSCI is its European equivalent and is made up of companies such as Shell and Total.

We will replicate the index using two different methods, firstly using the least squares method with positive coefficients(I), and secondly using correlation measures between the price of the index and our ten assets(II).

Each time we will try to partially replicate the XLE index using the top ten stocks of the XLE index in the first step, then we will try to track the index using assets of the European ETF ANRJ MSCI. This second replication will allow us to better evaluate which method seems to be the most optimal given the Tracking Error. To compare with a professional ETF we will compare the Tracking Error established for our ETF with that of the IYE ETF, which is supposed to track the XLE index.

We will use the end of 2019 yahoo finance data to build our ETFs. We will also use end-2020 data to assess the suitability of the ETFs by comparing the prices of the ETFs and the index for the year following the year in which the ETF was constructed.
