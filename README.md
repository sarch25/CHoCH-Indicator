# CHoCH Indicator

## Summary

The Change of Character (CHoCH) indicator is a Python-based tool for identifying potential trend reversals/pivots in market structure. It works by analyzing key price movements, including Highs, Lows, Higher Highs (HH), Higher Lows (HL), Lower Highs (LH), and Lower Lows (LL). A CHoCH occurs when:

- In an Uptrend, the price breaks below the most recent Higher Low (HL), signaling a potential shift to a Downtrend.
- In a Downtrend, the price breaks above the most recent Lower High (LH), indicating a possible move to an Uptrend.

This indicator provides traders with insights into market dynamics, allowing them to identify reversals and make informed trading decisions.

#### Features of the CHoCH Indicator:
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

#### This piece of Python code is designed to detect trends based on EMA (Exponential Moving Average) signals. The script iterates through rows of a DataFrame, analyzing a defined number of "backcandles" to determine whether the price remains consistently above or below the EMA line. Based on these conditions, it assigns trend signals (uptrend, downtrend, or neutral) to a new column, EMASignal, in the DataFrame.

![Screenshot 2024-04-08 102438](https://github.com/sarch25/CHoCH-Indicator/assets/130470960/69db915c-37d1-44f2-9cc2-63aae2cd20c6)
#

#### This shows the Python function, isPivot, designed to identify pivot or fractal points in a dataset. The function takes two parameters: the index of a candle and a window size. It evaluates whether the given candle represents a pivot high, pivot low, both, or neither by comparing its high and low values to neighboring candles within the specified window. The function returns a value to classify the pivot type.
![Screenshot 2024-04-08 102455](https://github.com/sarch25/CHoCH-Indicator/assets/130470960/ba881f04-1209-4a3a-9e9a-ee15049100e4)
#

#### This chart visually represents price movements using candlesticks, with key pivot points highlighted by purple dots. The candlesticks illustrate the high and lows over time, indicating market trends and fluctuations. The purple dots correspond to detected pivot points, which are potential turning points in the market structure.
![Screenshot 2024-04-08 102608](https://github.com/sarch25/CHoCH-Indicator/assets/130470960/df31afee-557f-4f55-adc1-764dfcfe7d7b)
#
