# Transfer Learning in Asset Prediction

## User Story

## Table of Contents

1. [Project Links](#Project-Links)
1. [Project Summary](#Project-Summary)
1. [Questions](#Questions)
1. [Instructions](#Instructions)
1. [Project Team](#Project-Team)
1. [Contribution Guidelines](#Contribution-Guidelines)
1. [Contanct](#Contact)
1. [License](#License)

## Project Links

[Repo Link](https://github.com/dannynday/goup2) <br>
![Repo Image](./images/output.png)

## Project Summary
The objective of our project was to test the functionality of transfer learning to create a neural network machine learning model that could be applied to a variety of assets. To test this, we built a model that predicted winning positions on oil stocks, specifically ProShares Ultra Bloomberg Crude Oil (UCO). This model was trained on 43 features, including a variety of techinical indicators. We then saved the model and applied it to the crypto-currency markets, specifically looking some of the world's top exchanges and their native tokens (e.g. FTX/FTT, Binance/BNB, etc.)

## Questions

### What is a trading strategy that in theory should work under any market conditions?
UCO and SCO are two stocks based on the oil market (UCO is ultra long and SCO is ultra short), and they have a near perfect inverse realationship. By using technical indicators like simple moving averages (SMA), we should be able to build a machine learning model that predicts when it is worth taking a long position on either one of these stocks.

### What are the challenges of created a well trained Neural Network for predicting winning positions on UCO? And what are the parameters that are ultimately useful for an effective oil model?

### How does the baseline model created for UCO using sklearn svm compare to the Neural Network model created using deep learing?
Our initial svc model was fairly accurate
![Repo Image](./Resources/Images/uco-testing-report.png)

### Howe effective is it to apply transfer learning to asset position prediction?


## Code and Dependencies
This code is to be run on Google Colab 
`Python 3`

The following Python Libraries were also imported and used

`import pandas as pd`

`import os`

`import requests`

`import numpy as np`

`import datetime as dt`

`from pathlib import Path`

`import pandas_datareader as web`


`import matplotlib.pyplot as plt`

## Instructions


## Project Team

[Ben Eilers](https://github.com/bweilers) <br>
[Wade Burgess](https://github.com/) <br>
[Danny Ndayisenga](https://github.com/) <br>

## Contribution Guidelines:

```
Feel free to contribute to this repo by creating issues or sending an email to any of the contributors in the list below.
```

## Contact

<details>
    <summary>Contact</summary>
    ben.eilers@gmail.com <br>
    @gmail.com <br>
    @yahoo.com <br>

</details>

