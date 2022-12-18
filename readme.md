# ICAIF 2022 Data Augmentation for Portfolio Construction
This github respository is for our ICAIF 2022 paper "Theoretically Motivated Data Augmentation and Regularization for Portfolio Construction
," see the full version of our paper on arxiv:
https://arxiv.org/abs/2106.04114

# Data
To obtain the S&P500 data we used, change the directory to `./data` and use the following command:
```
wget http://cat.phys.s.u-tokyo.ac.jp/~zliu/data/finance/sp500.csv
```

# A case study of the proposed method
The following figures shows portfolio constructed by our neural network model of MSFT (Microsoft) during the 2020 stock market crash (see https://en.wikipedia.org/wiki/2020_stock_market_crash). The vertical dashed line shows the data of the market crash.

The price of the stock:

<img src="figures/case_study_portfolio.png" alt="cifar10" width="250"/>


The constructed portfolio:

<img src="figures/case_study_price.png" alt="cifar10" width="250"/>

As we see, the model avoids the crash quite well.

# TODO
- A jupyter notebook for demonstration
- A gridsearch code for reproducing the benchmark results

