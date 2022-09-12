# Prediction of Sea Ice Extent in Northern Hemisphere

![annual_sea_ice_extent](/images/my_animation5.gif)
## Introduction
We live in the age of man-made climate change. This affects the ecological systems on Earth. The Arctic sea ice extent is one of the most important indicators of climate change. In order to understand the future climate better, it is necessary to analyse the historical data of sea ice extent. With the help of data science models, it is possible to understand the current trend and to simulate the future scenarios. In our simulations, we have calculated and visualised a scenario for an ice-free Arctic summer.

## Data
The used data can be found on https://nsidc.org/ splitted in different datasets depending on the topic you wants to focus on, e.g. a dataset for the whole northern hemisphere on a daily or monthly basis or another dataset showing the seaice-extent of each region in the northern hemisphere

## Requirements:

- pyenv with Python: 3.9.4

### Setup

Use the requirements file in this repo to create a new environment.

```BASH
make setup

#or

pyenv local 3.9.4
python -m venv .venv
source .venv/bin/activate
pip install --upgrade pip
pip install -r requirements_dev.txt
```
