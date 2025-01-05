# CHoCH Indicator

## Summary

The Change of Character (CHoCH) indicator is a Python-based tool for identifying potential trend reversals/pivots in market structure. It works by analyzing key price movements, including Highs, Lows, Higher Highs (HH), Higher Lows (HL), Lower Highs (LH), and Lower Lows (LL). A CHoCH occurs when:

- In an Uptrend, the price breaks below the most recent Higher Low (HL), signaling a potential shift to a Downtrend.
- In a Downtrend, the price breaks above the most recent Lower High (LH), indicating a possible move to an Uptrend.

This indicator provides traders with insights into market dynamics, allowing them to identify reversals and make informed trading decisions.

Features of the CHoCH Indicator:
- Dynamic Analysis: Tracks price changes across previous candles to detect shifts in market structure.
- Trend Signals via EMA: Utilizes Exponential Moving Average (EMA) signals to classify trends as uptrend, downtrend, or neutral by checking price consistency above or below the EMA.
- Pivot Identification: Implements a custom Python function (isPivot) to detect pivot (fractal) points, classifying candles as pivot highs, lows, or both based on neighboring price data.

![Screenshot 2024-04-08 102608](https://github.com/sarch25/CHoCH-Indicator/assets/130470960/df31afee-557f-4f55-adc1-764dfcfe7d7b)

### Skills Learned

- Developing custom technical analysis indicators in Python
- Integrating indicators into trading strategies for enhanced decision-making in Python
- Utilizing libraries for data analysis, visualization, and scientific computing in financial applications
  
### Tools Used

- Pandas and NumPy for data manipulation and analysis
- Pandas TA for technical analysis indicators
- Plotly for visualization of trading signals
- SciPy for scientific computing tasks

## Images


![Screenshot 2024-04-08 102727](https://github.com/sarch25/CHoCH-Indicator/assets/130470960/324ef9ce-ee5f-4882-96eb-ae5ab8a22def)

![Screenshot 2024-04-08 102701](https://github.com/sarch25/CHoCH-Indicator/assets/130470960/a4c87cfc-7c15-44b0-84e7-b846442ed8b8)

![Screenshot 2024-04-08 102637](https://github.com/sarch25/CHoCH-Indicator/assets/130470960/11250b8e-a4f7-44b2-8ae0-0fc55d1351cb)

![Screenshot 2024-04-08 102608](https://github.com/sarch25/CHoCH-Indicator/assets/130470960/df31afee-557f-4f55-adc1-764dfcfe7d7b)

![Screenshot 2024-04-08 102515](https://github.com/sarch25/CHoCH-Indicator/assets/130470960/cf96d356-b4a6-4d3a-8f3e-153be9e6b148)
#

### This screenshot shows a Python function, isPivot, designed to identify pivot or fractal points in a dataset. The function takes two parameters: the index of a candle and a window size. It evaluates whether the given candle represents a pivot high, pivot low, both, or neither by comparing its high and low values to neighboring candles within the specified window. The function returns a value to classify the pivot type, making it useful for technical analysis in trading strategies.
![Screenshot 2024-04-08 102455](https://github.com/sarch25/CHoCH-Indicator/assets/130470960/ba881f04-1209-4a3a-9e9a-ee15049100e4)
#

#### This screenshot displays a Python code snippet designed to detect trends based on EMA (Exponential Moving Average) signals. The script iterates through rows of a DataFrame, analyzing a defined number of "backcandles" to determine whether the price remains consistently above or below the EMA line. Based on these conditions, it assigns trend signals (uptrend, downtrend, or neutral) to a new column, EMASignal, in the DataFrame.

![Screenshot 2024-04-08 102438](https://github.com/sarch25/CHoCH-Indicator/assets/130470960/69db915c-37d1-44f2-9cc2-63aae2cd20c6)
#
![Screenshot 2024-04-08 102419](https://github.com/sarch25/CHoCH-Indicator/assets/130470960/d6746769-db7a-4dec-a6fd-e4c0a99cb08e)





Every screenshot should have some text explaining what the screenshot is about.
