# Mckinsey-Challenge-2018
Prediction of Customer Acquisition through Digital Channels
import numpy as np
import pandas as pd
import matplotlib.pyplot as plt
import seaborn as sns
sns.set_style("whitegrid")
%matplotlib inline
mckinsey = pd.read_csv('train.csv')
mckinsey.head()
mckinsey.keys()
mckinsey.info()
mckinsey.describe()
sns.set_palette("GnBu_d")
sns.set_style("whitegrid")
