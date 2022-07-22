# New-Moving-Average-Model

The New Moving Average Model is an extension of the existing theory of 50 SMA crossing the 200 SMA, also called the Golden Cross. The model considers three parameters while determining whether to signal Buy on the stock or not. These three parameters are checked for all the Nifty 500 index stocks. The three parameters are - 

- 50 SMA crossing the 200 SMA on the Upside (Golden Cross pattern) as well as the CMP of the stock being above both the 50 SMA & 200 SMA.
- Stock making a new 52-week high in the previous 6 months approximately.
- The Rolling 200 SMA calculated on intervals of 20 days being consistently increasing, that is the 200 SMA is consistently increasing.

When all these conditions are satisfied, the model returns Buy signals for the respective stocks in the Output sheet.

Also, you can instantaneously check the 200 SMA & 50 SMA of any stock by checking the 275th & 277th row of the Calculations sheet. The rolling 200 SMA values can be found in the rows from 285 to 288.

Note - The Model works only in Excel 365. The data is automatically refreshed everytime the user opens the workbook.
