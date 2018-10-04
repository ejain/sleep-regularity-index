# Sleep Regularity Index

This project contains [a Jupyter notebook](sri.ipynb) with code for calculating a 
[Sleep Regularity Index (SRI)](https://www.nature.com/articles/s41598-018-32402-5) from a series of sleep records 
consisting of timestamps and durations (e.g. exported from [Fitbit](https://www.fitbit.com/) via 
[Zenobase](https://zenobase.com/)). 

The calculated SRI values range from 0 (no overlap in sleep and wake times from one day to another) to 100 (the same 
sleep times every day). This method handles multiple intervals of sleep per day.


## Limitations

- There's no way to distinguish between missing data and "not sleeping".
- There's no special accommodation for daylight savings or timezone changes.
