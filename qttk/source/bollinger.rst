Bollinger Bands
***************
A Bollinger Band® is a technical analysis tool defined by a set of trendlines
plotted two standard deviations positively and negatively) away from a simple
moving average (SMA) of a security's price, but which can be adjusted to user
preferences.

This Module outputs a stacked graph featuring:
----------------------------------------------
| *Bollinger Bands with candlestick close prices
| *Volume
| *%b
| *Bandwidth


Necessary imports ::
------------------
import os
import matplotlib.dates as mdates
import matplotlib.pyplot as plt
import pandas as pd

Function ::
---------
def compute_bb(eod_data: pd.DataFrame,
               moving_avg_window: int = 21,
               std_window: int = 21,
               volume_window: Optional[int] = 50,
               multiplier: int = 2) -> pd.DataFrame:
