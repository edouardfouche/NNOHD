# Unsupervised Artificial Neural Networks for Outlier Detection in High-Dimensional Data
# Implementation Release and Additional Material


Welcome to the additional material for the paper *Unsupervised Artificial Neural Networks for Outlier Detection in High-Dimensional Data* by Daniel Popovic, Edouard Fouch\'{e}

## Quick Start

## Implementation Release


## Additional Material
This section contains the complete data for the sections of the paper that are only partially filled due to space limitations.

### Evaluated Data Sets
In this section we list the complete set of evaluated data sets.

Data Set | Dimensions | Data Objects | Outliers | Outlier Ratio
--- | --- | --- | --- | ---
Arrhythmia-2 | 259 | 248 | 4 | 1.61%
Arrhythmia-5 | 259 | 256 | 12 | 4.69%
Arrhythmia-10 | 259 | 271 | 27 | 9.96%
Arrhythmia-20 | 259 | 305 | 61 | 20.00%
Arrhythmia-46 | 259 | 450 | 206 | 45.78%
Cardio | 21 | 1,831 | 176 | 9.61%
Ecoli | 7 | 336 | 9 | 2.68%
InternetAds-2 | 1,555 | 1,630 | 32 | 1.96%
InternetAds-5 | 1,555 | 1,682 | 84 | 4.99%
InternetAds-10 | 1,555 | 1,775 | 177 | 9.97%
InternetAds-19 | 1,555 | 1,966 | 368 | 18.72%
ISOLET-2 | 617 | 2,449 | 50 | 2.00%
ISOLET-4 | 617 | 2,499 | 100 | 4.00%
ISOLET-8 | 617 | 2,599 | 200 | 7.70%
ISOLET-14 | 617 | 2,799 | 400 | 14.29%
ISOLET-20 | 617 | 2,999 | 600 | 20.00%
Lympho | 18 | 148 | 6 | 4.05%
MNIST | 100 | 7,603 | 700 | 9.21%
Musk | 166 | 3,062 | 97 | 3.12%
Optdigits | 64 | 5,216 | 150 | 2.88%
P53 | 5,408 | 16,592 | 143 | 0.86%
Pendigits | 16 | 6,870 | 156 | 2.27%
Seismic | 11 | 2,584 | 170 | 6.58%
Thyroid | 6 | 3,772 | 2.4%
Waveform | 21 | 3,509 | 166 | 4.73%
Yeast | 8 | 1,364 | 65 | 4.77%


### Dataset Evaluation

#### ROC AUC for High Dimensional Data Sets

Data Set | AE | SOM | RBM | HiCS | LOF | FastABOD | LoOP | OC-SVM | KNN
--- | --- | --- | --- | --- | --- | --- | --- | --- | --- 
Arrhythmia-2 | **80.22** | 76.33 | 49.04 | 50.56 | 76.74 | 76.84 | 75.00 | 77.66 | 71.88
Arrhythmia-5 | 78.16 | **81.49** | 50.36 | 58.81 | 80.46 | 49.51 | 79.99 | *81.47* | 68.72
Arrhythmia-10 | *83.84* | *83.74* | 48.23 | 65.12 | *83.45* | 83.35 | **84.24** | *83.26* | 76.20
Arrhythmia-20 | 71.01 | 71.33 | 49.93 | 50.71 | 70.47 | 71.14 | *71.70* | **72.38** | 67.52
Arrhythmia-46 | **74.93** | *74.79* | 46.99 | 58.96 | *74.41* | *74.17* | *74.10* | *74.13* | 70.72
InternetAds-2 | 43.36 | 66.12 | 46.93 | **99.84** | 71.64 | 76.49 | 77.14 | 64.18 | 81.23
InternetAds-5 | 40.14 | 73.36 | 50.27 | **99.87** | 78.63 | 78.75 | 82.56 | 74.76 | 69.35
InternetAds-10 | 39.38 | 69.42 | 49.75 | **79.25** | 74.71 | 74.41 | 77.73 | 71.25 | 65.21
InternetAds-19 | 36.32 | 69.69 | 50.14 | 47.33 | **74.01** | 72.40 | 69.78 | 62.43 | 59.54
ISOLET-2 | 96.85 | *99.28* | 92.28 | 79.71 | **99.58** | 93.09 | 98.23 | 92.05 | 94.66
ISOLET-4 | 94.72 | *98.49* | 87.24 | 79.79 | **99.34** | 86.44 | 95.08 | 89.75 | 83.89
ISOLET-8 | 95.16 | **98.29** | 87.19 | 78.14 | 83.81 | 75.37 | 68.71 | 89.19 | 82.90
ISOLET-14 | 92.67 | **94.96** | 85.50 | 78.16 | 65.61 | 75.60 | 62.16 | 81.61 | 80.00
ISOLET-20 | **90.16** | 87.13 | 87.19 | 77.82 | 60.04 | 73.28 | 55.00 | 77.06 | 77.40
MNIST | **82.06** | 81.07 | 49.87 | 51.74 | 80.34 | 54.35 | 71.66 | 76.46 | 72.74
Musk | **100.00** | **100.00** | 95.60 | *99.60* | 84.00 | 5.11 | 51.86 | 67.60 | 7.11
P53 | 60.63 | **67.17** | 64.76 | 62.09 | 61.99 | 62.92 | 61.99 | 61.27 | 62.56


#### PR AUC for High Dimensional Data Sets

Data Set | AE | SOM | RBM | HiCS | LOF | FastABOD | LoOP | OC-SVM | KNN
--- | --- | --- | --- | --- | --- | --- | --- | --- | --- 
Arrhythmia-2 | **29.37** | 27.94 | 1.66 | 1.64 | 3.83 | 3.98 | 3.51 | 4.90 | 3.04
Arrhythmia-5 | 30.61 | **36.15** | 5.00 | 4.14 | 30.62 | 29.53 | 29.85 | 30.56 | 22.37
Arrhythmia-10 | **48.54** | *48.24* | 10.31 | 13.84 | 45.36 | 42.49 | 45.55 | 40.55 | 33.24
Arrhythmia-20 | **51.97** | 50.62 | 20.35 | 15.78 | 49.12 | 48.14 | 48.90 | 49.92 | 46.98
Arrhythmia-46 | **75.32** | 74.54 | 44.98 | 44.67 | 74.36 | 72.83 | 71.63 | 73.68 | 71.50
InternetAds-2 | 1.58 | 32.78 | 1.91 | **94.52** | 34.86 | 32.79 | 3.51 | 4.90 | 3.04
InternetAds-5 | 5.12 | 45.86 | 5.21 | **97.67** | 52.56 | 40.25 | 51.12 | 33.54 | 32.87
InternetAds-10 | 7.69 | 47.89 | 10.12 | 41.13 | **51.93** | 35.74 | 46.09 | 29.40 | 35.11
InternetAds-19 | 14.29 | *54.67* | 18.91 | 1.44 | **55.24** | 41.86 | 44.48 | 29.46 | 33.64
ISOLET-2 | 44.45 | 66.93 | 29.51 | 4.47 | **70.95** | 29.54 | 51.78 | 25.65 | 42.91
ISOLET-4 | 49.97 | 69.76 | 33.59 | 9.08 | **74.21** | 24.07 | 47.62 | 47.61 | 23.96
ISOLET-8 | 59.60 | **78.61** | 40.50 | 14.36 | 43.81 | 21.71 | 31.45 | 46.55 | 28.59
ISOLET-14 | 64.48 | **75.40** | 53.84 | 29.06 | 40.03 | 33.68 | 27.15 | 47.53 | 36.62
ISOLET-20 | **64.26** | 63.55 | 40.50 | 36.92 | 34.56 | 37.72 | 25.59 | 48.72 | 41.45
MNIST | 30.13 | 27.40 | 9.26 | 9.99 | **33.95** | 14.05 | 24.74 | 25.49 | 27.96
Musk | **100.00** | **100.00** | 85.58 | 97.46 | 14.68 | 1.65 | 3.71 | 4.54 | 1.91
P53 | 1.04 | *1.29* | 1.20 | 1.25 | 1.06 | 1.13 | 1.06 | 1.06 | **1.30**


#### Visualization

##### ROC AUC and PR AUC for Arrhythmia-2

![](https://github.com/DanielP77/NNOHD/blob/master/images/ROC_PR_Arrhythmia-2.png "ROC AUC and PR AUC for Arrhythmia-2")


### Parameter Evaluation
In this section 


#### Parameter Evaluation for Autoencoder (AE)

Parameter ![](https://github.com/DanielP77/NNOHD/blob/master/images/epsilon.png "Epsilon") | Epochs ![](https://github.com/DanielP77/NNOHD/blob/master/images/n_e.png "n^e") | ![](https://github.com/DanielP77/NNOHD/blob/master/images/D_epsilon_n_e.png "D_{Epsilon,n^e}")
---|---|---
0.4 | 10 | 0.
0.4 | 20 | 0.
0.4 | 100 | 0.
0.4 | 1,000 | 0.
0.5 | 10 | 0.0519
0.5 | 20 | *0.0405*
0.5 | 100 | 0.0527
0.5 | 1,000 | 0.0820
0.6 | 10 | *0.0478*
0.6 | 20 | *0.0411*
0.6 | 100 | *0.0476*
0.6 | 1,000 | 0.0844
0.7 | 10 | *0.0501*
0.7 | 20 | *0.0412*
0.7 | 100 | 0.0527
0.7 | 1,000 | 0.0788
0.8 | 10 | *0.0409*
0.8 | 20 | **0.0403**
0.8 | 100 | 0.0512
0.8 | 1,000 | 0.0827
0.9 | 10 | *0.0424*
0.9 | 20 | *0.0412*
0.9 | 100 | 0.0539
0.9 | 1,000 | 0.0828


#### Parameter Evaluation for Restricted Boltzmann Machine (RBM)

Parameter ![](https://github.com/DanielP77/NNOHD/blob/master/images/delta.png "Delta") | Parameter ![](https://github.com/DanielP77/NNOHD/blob/master/images/gamma.png "Gamma") | Epochs ![](https://github.com/DanielP77/NNOHD/blob/master/images/n_e.png "n^e") | ![](https://github.com/DanielP77/NNOHD/blob/master/images/D_delta_gamma_n_e.png "D_{delta,gamma,n^e}")
---|---|---|---
0.1 | 0.1 | 10 | 0.2318
0.1 | 0.1 | 20 | 0.2067
0.1 | 0.1 | 100 | 0.1700
0.1 | 0.1 | 1,000 | 0.1507
0.1 | 0.2 | 10 | 0.1221
0.1 | 0.2 | 20 | 0.0985
0.1 | 0.2 | 100 | 0.0994
0.1 | 0.2 | 1,000 | 0.2349
0.1 | 0.3 | 10 | 0.2038
0.1 | 0.3 | 20 | 0.1925
0.1 | 0.3 | 100 | 0.1453
0.1 | 0.3 | 1,000 | 0.1192
0.1 | 0.4 | 10 | 0.0971
0.1 | 0.4 | 20 | 0.1142
0.1 | 0.4 | 100 | 0.2313
0.1 | 0.4 | 1,000 | 0.2086
0.1 | 0.5 | 10 | 0.1857
0.1 | 0.5 | 20 | 0.1641
0.1 | 0.5 | 100 | 0.1136
0.1 | 0.5 | 1,000 | 0.0903
0.1 | 0.6 | 10 | 0.0920
0.1 | 0.6 | 20 | 0.0928
0.1 | 0.6 | 100 | 0.2010
0.1 | 0.6 | 1,000 | 0.1900
0.1 | 0.7 | 10 | 0.1587
0.1 | 0.7 | 20 | 0.1375
0.1 | 0.7 | 100 | 0.1000
0.1 | 0.7 | 1,000 | 0.0740
0.1 | 0.8 | 10 | 0.0778
0.1 | 0.8 | 20 | 0.2408
0.1 | 0.8 | 100 | 0.1873
0.1 | 0.8 | 1,000 | 0.1576
0.1 | 0.9 | 10 | 0.1426
0.1 | 0.9 | 20 | 0.1121
0.1 | 0.9 | 100 | 0.0764
0.1 | 0.9 | 1,000 | 0.0756
0.2 | 0.1 | 10 | 0.2412
0.2 | 0.1 | 20 | 0.2058
0.2 | 0.1 | 100 | 0.1660
0.2 | 0.1 | 1,000 | 0.1460
0.2 | 0.2 | 10 | 0.1305
0.2 | 0.2 | 20 | 0.1202
0.2 | 0.2 | 100 | 0.0955
0.2 | 0.2 | 1,000 | 0.2266
0.2 | 0.3 | 10 | 0.1975
0.2 | 0.3 | 20 | 0.1832
0.2 | 0.3 | 100 | 0.1439
0.2 | 0.3 | 1,000 | 0.1142
0.2 | 0.4 | 10 | 0.1031
0.2 | 0.4 | 20 | 0.0913
0.2 | 0.4 | 100 | 0.2398
0.2 | 0.4 | 1,000 | 0.2001
0.2 | 0.5 | 10 | 0.1883
0.2 | 0.5 | 20 | 0.1628
0.2 | 0.5 | 100 | 0.1143
0.2 | 0.5 | 1,000 | 0.1070
0.2 | 0.6 | 10 | 0.0751
0.2 | 0.6 | 20 | 0.0881
0.2 | 0.6 | 100 | 0.2084
0.2 | 0.6 | 1,000 | 0.1852
0.2 | 0.7 | 10 | 0.1508
0.2 | 0.7 | 20 | 0.1400
0.2 | 0.7 | 100 | 0.0953
0.2 | 0.7 | 1,000 | 0.0764
0.2 | 0.8 | 10 | 0.0923
0.2 | 0.8 | 20 | 0.2278
0.2 | 0.8 | 100 | 0.1755
0.2 | 0.8 | 1,000 | 0.1612
0.2 | 0.9 | 10 | 0.1429
0.2 | 0.9 | 20 | 0.1281
0.2 | 0.9 | 100 | 0.0822
0.2 | 0.9 | 1,000 | *0.0638*
0.3 | 0.1 | 10 | 0.2381
0.3 | 0.1 | 20 | 0.2174
0.3 | 0.1 | 100 | 0.1635
0.3 | 0.1 | 1,000 | 0.1473
0.3 | 0.2 | 10 | 0.1232
0.3 | 0.2 | 20 | 0.1111
0.3 | 0.2 | 100 | 0.0986
0.3 | 0.2 | 1,000 | 0.2351
0.3 | 0.3 | 10 | 0.2138
0.3 | 0.3 | 20 | 0.1846
0.3 | 0.3 | 100 | 0.1429
0.3 | 0.3 | 1,000 | 0.1249
0.3 | 0.4 | 10 | 0.0985
0.3 | 0.4 | 20 | 0.1104
0.3 | 0.4 | 100 | 0.2335
0.3 | 0.4 | 1,000 | 0.2191
0.3 | 0.5 | 10 | 0.1916
0.3 | 0.5 | 20 | 0.1622
0.3 | 0.5 | 100 | 0.1214
0.3 | 0.5 | 1,000 | 0.0978
0.3 | 0.6 | 10 | 0.0786
0.3 | 0.6 | 20 | *0.0657*
0.3 | 0.6 | 100 | 0.2042
0.3 | 0.6 | 1,000 | 0.1806
0.3 | 0.7 | 10 | 0.1547
0.3 | 0.7 | 20 | 0.1338
0.3 | 0.7 | 100 | 0.0894
0.3 | 0.7 | 1,000 | 0.0781
0.3 | 0.8 | 10 | 0.0839
0.3 | 0.8 | 20 | 0.2311
0.3 | 0.8 | 100 | 0.1837
0.3 | 0.8 | 1,000 | 0.1461
0.3 | 0.9 | 10 | 0.1375
0.3 | 0.9 | 20 | 0.1237
0.3 | 0.9 | 100 | 0.0844
0.3 | 0.9 | 1,000 | 0.0736
0.4 | 0.1 | 10 | 0.2188
0.4 | 0.1 | 20 | 0.2109
0.4 | 0.1 | 100 | 0.1754
0.4 | 0.1 | 1,000 | 0.1455
0.4 | 0.2 | 10 | 0.1344
0.4 | 0.2 | 20 | 0.1146
0.4 | 0.2 | 100 | 0.0997
0.4 | 0.2 | 1,000 | 0.2355
0.4 | 0.3 | 10 | 0.2075
0.4 | 0.3 | 20 | 0.1836
0.4 | 0.3 | 100 | 0.1391
0.4 | 0.3 | 1,000 | 0.1193
0.4 | 0.4 | 10 | 0.1073
0.4 | 0.4 | 20 | 0.1049
0.4 | 0.4 | 100 | 0.2301
0.4 | 0.4 | 1,000 | 0.2083
0.4 | 0.5 | 10 | 0.1914
0.4 | 0.5 | 20 | 0.1555
0.4 | 0.5 | 100 | 0.1074
0.4 | 0.5 | 1,000 | 0.0930
0.4 | 0.6 | 10 | 0.0995
0.4 | 0.6 | 20 | 0.0852
0.4 | 0.6 | 100 | 0.2117
0.4 | 0.6 | 1,000 | 0.1779
0.4 | 0.7 | 10 | 0.1607
0.4 | 0.7 | 20 | 0.1287
0.4 | 0.7 | 100 | 0.0874
0.4 | 0.7 | 1,000 | 0.0886
0.4 | 0.8 | 10 | 0.0781
0.4 | 0.8 | 20 | 0.2340
0.4 | 0.8 | 100 | 0.1793
0.4 | 0.8 | 1,000 | 0.1592
0.4 | 0.9 | 10 | 0.1420
0.4 | 0.9 | 20 | 0.1240
0.4 | 0.9 | 100 | 0.1061
0.4 | 0.9 | 1,000 | 0.0759
0.5 | 0.1 | 10 | 0.2396
0.5 | 0.1 | 20 | 0.2065
0.5 | 0.1 | 100 | 0.1644
0.5 | 0.1 | 1,000 | 0.1414
0.5 | 0.2 | 10 | 0.1308
0.5 | 0.2 | 20 | 0.1139
0.5 | 0.2 | 100 | 0.0935
0.5 | 0.2 | 1,000 | 0.2268
0.5 | 0.3 | 10 | 0.2150
0.5 | 0.3 | 20 | 0.1950
0.5 | 0.3 | 100 | 0.1395
0.5 | 0.3 | 1,000 | 0.1150
0.5 | 0.4 | 10 | 0.1029
0.5 | 0.4 | 20 | 0.1019
0.5 | 0.4 | 100 | 0.2335
0.5 | 0.4 | 1,000 | 0.2097
0.5 | 0.5 | 10 | 0.1811
0.5 | 0.5 | 20 | 0.1583
0.5 | 0.5 | 100 | 0.1071
0.5 | 0.5 | 1,000 | 0.1072
0.5 | 0.6 | 10 | 0.0834
0.5 | 0.6 | 20 | 0.0865
0.5 | 0.6 | 100 | 0.2110
0.5 | 0.6 | 1,000 | 0.1754
0.5 | 0.7 | 10 | 0.1629
0.5 | 0.7 | 20 | 0.1280
0.5 | 0.7 | 100 | 0.0971
0.5 | 0.7 | 1,000 | 0.0797
0.5 | 0.8 | 10 | 0.0784
0.5 | 0.8 | 20 | 0.2378
0.5 | 0.8 | 100 | 0.1833
0.5 | 0.8 | 1,000 | 0.1388
0.5 | 0.9 | 10 | 0.1331
0.5 | 0.9 | 20 | 0.1081
0.5 | 0.9 | 100 | 0.0901
0.5 | 0.9 | 1,000 | *0.0675*
0.6 | 0.1 | 10 | 0.2311
0.6 | 0.1 | 20 | 0.2155
0.6 | 0.1 | 100 | 0.1667
0.6 | 0.1 | 1,000 | 0.1556
0.6 | 0.2 | 10 | 0.1351
0.6 | 0.2 | 20 | 0.1135
0.6 | 0.2 | 100 | 0.1056
0.6 | 0.2 | 1,000 | 0.2303
0.6 | 0.3 | 10 | 0.2089
0.6 | 0.3 | 20 | 0.1915
0.6 | 0.3 | 100 | 0.1509
0.6 | 0.3 | 1,000 | 0.1183
0.6 | 0.4 | 10 | 0.1070
0.6 | 0.4 | 20 | 0.0856
0.6 | 0.4 | 100 | 0.2253
0.6 | 0.4 | 1,000 | 0.2090
0.6 | 0.5 | 10 | 0.1864
0.6 | 0.5 | 20 | 0.1631
0.6 | 0.5 | 100 | 0.1118
0.6 | 0.5 | 1,000 | 0.0971
0.6 | 0.6 | 10 | 0.0778
0.6 | 0.6 | 20 | 0.0817
0.6 | 0.6 | 100 | 0.2173
0.6 | 0.6 | 1,000 | 0.1775
0.6 | 0.7 | 10 | 0.1501
0.6 | 0.7 | 20 | 0.1241
0.6 | 0.7 | 100 | 0.0870
0.6 | 0.7 | 1,000 | 0.0797
0.6 | 0.8 | 10 | 0.0847
0.6 | 0.8 | 20 | 0.2358
0.6 | 0.8 | 100 | 0.1839
0.6 | 0.8 | 1,000 | 0.1587
0.6 | 0.9 | 10 | 0.1371
0.6 | 0.9 | 20 | 0.1132
0.6 | 0.9 | 100 | 0.0997
0.6 | 0.9 | 1,000 | 0.0863
0.7 | 0.1 | 10 | 0.2339
0.7 | 0.1 | 20 | 0.2093
0.7 | 0.1 | 100 | 0.1595
0.7 | 0.1 | 1,000 | 0.1483
0.7 | 0.2 | 10 | 0.1348
0.7 | 0.2 | 20 | 0.1075
0.7 | 0.2 | 100 | 0.0890
0.7 | 0.2 | 1,000 | 0.2187
0.7 | 0.3 | 10 | 0.2239
0.7 | 0.3 | 20 | 0.1798
0.7 | 0.3 | 100 | 0.1406
0.7 | 0.3 | 1,000 | 0.1169
0.7 | 0.4 | 10 | 0.0912
0.7 | 0.4 | 20 | 0.0944
0.7 | 0.4 | 100 | 0.2441
0.7 | 0.4 | 1,000 | 0.2151
0.7 | 0.5 | 10 | 0.1833
0.7 | 0.5 | 20 | 0.1663
0.7 | 0.5 | 100 | 0.1179
0.7 | 0.5 | 1,000 | 0.0972
0.7 | 0.6 | 10 | 0.0904
0.7 | 0.6 | 20 | 0.0869
0.7 | 0.6 | 100 | 0.2039
0.7 | 0.6 | 1,000 | 0.1943
0.7 | 0.7 | 10 | 0.1590
0.7 | 0.7 | 20 | 0.1289
0.7 | 0.7 | 100 | 0.0913
0.7 | 0.7 | 1,000 | 0.0811
0.7 | 0.8 | 10 | 0.0893
0.7 | 0.8 | 20 | 0.2375
0.7 | 0.8 | 100 | 0.1887
0.7 | 0.8 | 1,000 | 0.1484
0.7 | 0.9 | 10 | 0.1430
0.7 | 0.9 | 20 | 0.1059
0.7 | 0.9 | 100 | 0.0782
0.7 | 0.9 | 1,000 | 0.0755
0.8 | 0.1 | 10 | 0.2353
0.8 | 0.1 | 20 | 0.2178
0.8 | 0.1 | 100 | 0.1627
0.8 | 0.1 | 1,000 | 0.1498
0.8 | 0.2 | 10 | 0.1203
0.8 | 0.2 | 20 | 0.1233
0.8 | 0.2 | 100 | 0.0925
0.8 | 0.2 | 1,000 | 0.2357
0.8 | 0.3 | 10 | 0.2109
0.8 | 0.3 | 20 | 0.1863
0.8 | 0.3 | 100 | 0.1432
0.8 | 0.3 | 1,000 | 0.1246
0.8 | 0.4 | 10 | 0.1082
0.8 | 0.4 | 20 | 0.1023
0.8 | 0.4 | 100 | 0.2293
0.8 | 0.4 | 1,000 | 0.2125
0.8 | 0.5 | 10 | 0.1751
0.8 | 0.5 | 20 | 0.1630
0.8 | 0.5 | 100 | 0.1205
0.8 | 0.5 | 1,000 | 0.0936
0.8 | 0.6 | 10 | 0.0884
0.8 | 0.6 | 20 | 0.0804
0.8 | 0.6 | 100 | 0.2186
0.8 | 0.6 | 1,000 | 0.1776
0.8 | 0.7 | 10 | 0.1602
0.8 | 0.7 | 20 | 0.1250
0.8 | 0.7 | 100 | 0.0953
0.8 | 0.7 | 1,000 | 0.0816
0.8 | 0.8 | 10 | 0.0778
0.8 | 0.8 | 20 | 0.2266
0.8 | 0.8 | 100 | 0.1781
0.8 | 0.8 | 1,000 | 0.1522
0.8 | 0.9 | 10 | 0.1370
0.8 | 0.9 | 20 | 0.1122
0.8 | 0.9 | 100 | **0.0597**
0.8 | 0.9 | 1,000 | 0.0732
0.9 | 0.1 | 10 | 0.2355
0.9 | 0.1 | 20 | 0.2089
0.9 | 0.1 | 100 | 0.1710
0.9 | 0.1 | 1,000 | 0.1554
0.9 | 0.2 | 10 | 0.1355
0.9 | 0.2 | 20 | 0.1155
0.9 | 0.2 | 100 | 0.1068
0.9 | 0.2 | 1,000 | 0.2370
0.9 | 0.3 | 10 | 0.2120
0.9 | 0.3 | 20 | 0.1828
0.9 | 0.3 | 100 | 0.1432
0.9 | 0.3 | 1,000 | 0.1210
0.9 | 0.4 | 10 | 0.1080
0.9 | 0.4 | 20 | 0.0945
0.9 | 0.4 | 100 | 0.2296
0.9 | 0.4 | 1,000 | 0.2073
0.9 | 0.5 | 10 | 0.1874
0.9 | 0.5 | 20 | 0.1612
0.9 | 0.5 | 100 | 0.1059
0.9 | 0.5 | 1,000 | 0.0900
0.9 | 0.6 | 10 | 0.0940
0.9 | 0.6 | 20 | 0.0753
0.9 | 0.6 | 100 | 0.2092
0.9 | 0.6 | 1,000 | 0.1892
0.9 | 0.7 | 10 | 0.1628
0.9 | 0.7 | 20 | 0.1460
0.9 | 0.7 | 100 | 0.0971
0.9 | 0.7 | 1,000 | 0.0915
0.9 | 0.8 | 10 | 0.0786
0.9 | 0.8 | 20 | 0.2337
0.9 | 0.8 | 100 | 0.1866
0.9 | 0.8 | 1,000 | 0.1683
0.9 | 0.9 | 10 | 0.1431
0.9 | 0.9 | 20 | 0.1117
0.9 | 0.9 | 100 | 0.0765
0.9 | 0.9 | 1,000 | 0.0800


#### Parameter Evaluation for Self-Organising Map (SOM)

Parameter ![](https://github.com/DanielP77/NNOHD/blob/master/images/n.png "n") | Epochs ![](https://github.com/DanielP77/NNOHD/blob/master/images/n_e.png "n^e") | ![](https://github.com/DanielP77/NNOHD/blob/master/images/D_n_n_e.png "D_{n,n^e}")
---|---|---
1 | 10 | 0.0496
1 | 20 | 0.0649
1 | 100 | 0.0496
1 | 1,000 | 0.0496
2 | 10 | **0.0221**
2 | 20 | 0.0330
2 | 100 | *0.0223*
2 | 1,000 | *0.0223*
3 | 10 | *0.0315*
3 | 20 | 0.0466
3 | 100 | 0.0332
3 | 1,000 | 0.0330
4 | 10 | 0.0399
4 | 20 | 0.0509
4 | 100 | 0.0543
4 | 1,000 | 0.0554
5 | 10 | 0.0768
5 | 20 | 0.0932
5 | 100 | 0.0850
5 | 1,000 | 0.0859
6 | 10 | 0.0866
6 | 20 | 0.0906
6 | 100 | 0.0901
6 | 1,000 | 0.0890
7 | 10 | 0.1040
7 | 20 | 0.1186
7 | 100 | 0.1117
7 | 1,000 | 0.1132
8 | 10 | 0.0995
8 | 20 | 0.1103
8 | 100 | 0.1107
8 | 1,000 | 0.1073
9 | 10 | 0.1144
9 | 20 | 0.1207
9 | 100 | 0.1095
9 | 1,000 | 0.1103
10 | 10 | 0.1314
10 | 20 | 0.1425
10 | 100 | 0.1166
10 | 1,000 | 0.1144
11 | 10 | 0.1807
11 | 20 | 0.1724
11 | 100 | 0.1596
11 | 1,000 | 0.1642
12 | 10 | 0.1815
12 | 20 | 0.1771
12 | 100 | 0.1742
12 | 1,000 | 0.1667
13 | 10 | 0.1935
13 | 20 | 0.1919
13 | 100 | 0.1784
13 | 1,000 | 0.1826
14 | 10 | 0.1967
14 | 20 | 0.1898
14 | 100 | 0.1885
14 | 1,000 | 0.1969
15 | 10 | 0.2003
15 | 20 | 0.1965
15 | 100 | 0.2023
15 | 1,000 | 0.2083
16 | 10 | 0.2192
16 | 20 | 0.2230
16 | 100 | 0.2111
16 | 1,000 | 0.2175
17 | 10 | 0.2241
17 | 20 | 0.2218
17 | 100 | 0.2176
17 | 1,000 | 0.2075
18 | 10 | 0.2269
18 | 20 | 0.2271
18 | 100 | 0.2136
18 | 1,000 | 0.2234
19 | 10 | 0.2483
19 | 20 | 0.2331
19 | 100 | 0.2493
19 | 1,000 | 0.2291
20 | 10 | 0.2339
20 | 20 | 0.2227
20 | 100 | 0.2348
20 | 1,000 | 0.2346

