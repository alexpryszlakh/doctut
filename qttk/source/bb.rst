qttk.DataFrame.compute_bb()
===========================

**DataFrame.compute_bb** (eod_data,moving_avg_window=21,std_window=21,volume_window=50,multiplier=0)


This Module Outputs a Stacked Graph Featuring:
------------------------------------------------
| * Bollinger Bands with candlestick close prices
| * Volume
| * %b
| * Bandwidth

Parameters:
^^^^^^^^^^^
| **eod_data** : pandas.DataFrame
|     * *This is the dataset that is used as an input for the function*
| **moving_avg_window** : int, default 21
| **std_window** : int, default 21
| **volume_window** : int, Optional 50
| **multiplier** : int, default 2

Function ::
^^^^^^^^
def compute_macd(eod_data: pd.DataFrame)
