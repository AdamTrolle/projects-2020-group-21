# Data analysis project: Price cycles in the market for prescription drugs after patent expiry

In this project we will attempt to show the cyclic behaviour in some medical prices after the patent has expired, observed by the study "Priscykler i markedet for receptpligtig medicin efter patentudløb”. It will serve to demonstrate the matter of possible colusion by involving key points from competition theory by Maskin and Tirole (1988). In the empirical analysis we will investigate whether these cycles appears in data for the danish medicine prices in the period 2nd febuary 2015 - 23rd of marts 2020.

The **results** of the project can be seen from running [dataproject.ipynb](dataproject.ipynb).

This **loades one dataset**:

1. meddata.xlsx downloaded from statistikbanken.dk.

**Dependencies:** Apart from a standard Anaconda Python 3 installation, the project requires the following installations:

import numpy as np
import pandas as pd
import datetime
import matplotlib.pyplot as plt
plt.style.use('seaborn-whitegrid')
import ipywidgets as widgets
import seaborn as sns; sns.set()
import dataproject
import pylab