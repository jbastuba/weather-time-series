# weather-time-series

dataset: https://huggingface.co/datasets/ETDataset/ett

from huggingface:

Dataset Summary
The electric power distribution problem is the distribution of electricity to different areas depending on its sequential usage. But predicting the future demand of a specific area is difficult, as it varies with weekdays, holidays, seasons, weather, temperatures, etc. However, no existing method can perform a long-term prediction based on super long-term real-world data with high precision. Any false predictions may damage the electrical transformer. So currently, without an efficient method to predict future electric usage, managers have to make decisions based on the empirical number, which is much higher than the real-world demands. It causes unnecessary waste of electric and equipment depreciation. On the other hand, the oil temperatures can reflect the condition of the Transformer. One of the most efficient strategies is to predict how the electrical transformers' oil temperature is safe and avoid unnecessary waste. As a result, to address this problem, the authors and Beijing Guowang Fuda Science & Technology Development Company have provided 2-years worth of data.

Specifically, the dataset combines short-term periodical patterns, long-term periodical patterns, long-term trends, and many irregular patterns. The dataset are obtained from 2 Electricity Transformers at 2 stations and come in an 1H (hourly) or 15T (15-minute) frequency containing 2 year * 365 days * 24 hours * (4 for 15T) times = 17,520 (70,080 for 15T) data points.

Will create an LSTM model and 1D CNN and compare results between
