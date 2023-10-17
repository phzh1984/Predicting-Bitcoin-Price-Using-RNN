# Predicting-Bitcoin-Price-Using-RNN

Overview

This repository contains a project focused on predicting Bitcoin prices using Recurrent Neural Networks (RNNs). The dataset used for this project spans from January 2012 to March 2021 and consists of 1-minute interval data from select cryptocurrency exchanges. The data includes Open, High, Low, Close (OHLC) prices, trading volume in BTC, indicated currency, and the weighted Bitcoin price.

About the Dataset

Context

Bitcoin, created by the anonymous Satoshi Nakamoto in 2009, is the pioneering and most renowned cryptocurrency. It operates as a decentralized digital medium of exchange, with transactions validated and recorded in a public distributed ledger known as the blockchain, eliminating the need for a trusted central authority. The blockchain links transaction blocks through SHA-256 cryptographic hashes, creating an immutable record of all Bitcoin transactions.

Over time, as Bitcoin gained widespread adoption, trading and financial instruments emerged. This dataset encompasses historical Bitcoin market data at 1-minute intervals, sourced from select Bitcoin exchanges where trading activities take place.

Content

The dataset is provided in the bitstampUSD_1-min_data_2012-01-01_to_2021-03-31.csv file. It covers the period from January 2012 to March 2021 and offers minute-by-minute updates of OHLC prices, trading volume in BTC and indicated currency, and the weighted Bitcoin price. Timestamps are presented in Unix time format. In cases where there are no trades or activity during a timestamp, the data fields are filled with NaNs.

Please note that missing timestamps or jumps in the data might be due to exchange downtime, API issues, or other technical data reporting errors. While every effort has been made to remove duplicates and ensure data accuracy, users are encouraged to exercise their own discretion and trust the data at their own risk.
