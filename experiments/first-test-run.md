Selected 10 patients: ['SC400', 'SC401', 'SC402', 'SC403', 'SC404', 'SC405', 'SC406', 'SC407', 'SC408', 'SC409']
  SC4002E0-PSG.edf: X=(2650, 5, 3000), y=(2650,), label_counts={np.int64(0): 1997, np.int64(1): 58, np.int64(2): 250, np.int64(3): 220, np.int64(4): 125}

Patient SC400 sanity check:
  X shape: (2650, 5, 3000)  (expect: n_epochs, 5, 3000)
  y shape: (2650,)
  Label distribution:
    W: 1997 (75.4%)
    N1: 58 (2.2%)
    N2: 250 (9.4%)
    N3: 220 (8.3%)
    REM: 125 (4.7%)
  Majority-class baseline accuracy: 75.4%
  Chance-level (uniform) baseline: 20.0%

========== FOLD 1/10 -- test=SC400 ==========
  Train label distribution: {np.int64(0): 16976, np.int64(1): 706, np.int64(2): 4062, np.int64(3): 1263, np.int64(4): 1469}
  Test label distribution: {np.int64(0): 1997, np.int64(1): 58, np.int64(2): 250, np.int64(3): 220, np.int64(4): 125}
  Epoch 1/30 loss: 1.2769
  Epoch 2/30 loss: 1.2403
  Epoch 3/30 loss: 1.2213
  Epoch 4/30 loss: 1.2027
  Epoch 5/30 loss: 1.1851
  Epoch 6/30 loss: 1.1660
  Epoch 7/30 loss: 1.1541
  Epoch 8/30 loss: 1.1384
  Epoch 9/30 loss: 1.1220
  Epoch 10/30 loss: 1.1110
  Epoch 11/30 loss: 1.0939
  Epoch 12/30 loss: 1.0866
  Epoch 13/30 loss: 1.0728
  Epoch 14/30 loss: 1.0641
  Epoch 15/30 loss: 1.0560
  Epoch 16/30 loss: 1.0474
  Epoch 17/30 loss: 1.0384
  Epoch 18/30 loss: 1.0266
  Epoch 19/30 loss: 1.0213
  Epoch 20/30 loss: 1.0156
  Epoch 21/30 loss: 0.9996
  Epoch 22/30 loss: 0.9940
  Epoch 23/30 loss: 0.9881
  Epoch 24/30 loss: 0.9788
  Epoch 25/30 loss: 0.9714
  Epoch 26/30 loss: 0.9693
  Epoch 27/30 loss: 0.9564
  Epoch 28/30 loss: 0.9487
  Epoch 29/30 loss: 0.9428
  Epoch 30/30 loss: 0.9399

  Results for held-out patient SC400:
  Accuracy: 39.21%
  Per-class metrics:
    W: precision=0.99 recall=0.46 f1=0.63 support=1997
    N1: precision=0.06 recall=0.21 f1=0.09 support=58
    N2: precision=0.13 recall=0.20 f1=0.16 support=250
    N3: precision=0.05 recall=0.22 f1=0.08 support=220
    REM: precision=0.05 recall=0.04 f1=0.05 support=125
  Confusion matrix (rows=true, cols=pred):
[[925  69 152 826  25]
 [  2  12  14  28   2]
 [  4  69  49 108  20]
 [  0  47  82  48  43]
 [  4  16  73  27   5]]

========== FOLD 2/10 -- test=SC401 ==========
  Train label distribution: {np.int64(0): 17117, np.int64(1): 655, np.int64(2): 3750, np.int64(3): 1378, np.int64(4): 1424}
  Test label distribution: {np.int64(0): 1856, np.int64(1): 109, np.int64(2): 562, np.int64(3): 105, np.int64(4): 170}
  Epoch 1/30 loss: 1.2995
  Epoch 2/30 loss: 1.2515
  Epoch 3/30 loss: 1.2228
  Epoch 4/30 loss: 1.2032
  Epoch 5/30 loss: 1.1823
  Epoch 6/30 loss: 1.1651
  Epoch 7/30 loss: 1.1517
  Epoch 8/30 loss: 1.1365
  Epoch 9/30 loss: 1.1229
  Epoch 10/30 loss: 1.1055
  Epoch 11/30 loss: 1.0911
  Epoch 12/30 loss: 1.0852
  Epoch 13/30 loss: 1.0696
  Epoch 14/30 loss: 1.0579
  Epoch 15/30 loss: 1.0511
  Epoch 16/30 loss: 1.0419
  Epoch 17/30 loss: 1.0305
  Epoch 18/30 loss: 1.0203
  Epoch 19/30 loss: 1.0016
  Epoch 20/30 loss: 1.0067
  Epoch 21/30 loss: 1.0004
  Epoch 22/30 loss: 0.9775
  Epoch 23/30 loss: 0.9766
  Epoch 24/30 loss: 0.9658
  Epoch 25/30 loss: 0.9611
  Epoch 26/30 loss: 0.9561
  Epoch 27/30 loss: 0.9451
  Epoch 28/30 loss: 0.9350
  Epoch 29/30 loss: 0.9271
  Epoch 30/30 loss: 0.9190

  Results for held-out patient SC401:
  Accuracy: 70.41%
  Per-class metrics:
    W: precision=1.00 recall=0.91 f1=0.95 support=1856
    N1: precision=0.04 recall=0.04 f1=0.04 support=109
    N2: precision=0.56 recall=0.44 f1=0.49 support=562
    N3: precision=0.07 recall=0.39 f1=0.12 support=105
    REM: precision=0.11 recall=0.01 f1=0.01 support=170
  Confusion matrix (rows=true, cols=pred):
[[1680   52   55   63    6]
 [   0    4   27   78    0]
 [   5   23  247  285    2]
 [   0    1   63   41    0]
 [   0   31   53   85    1]]

========== FOLD 3/10 -- test=SC402 ==========
  Train label distribution: {np.int64(0): 17114, np.int64(1): 670, np.int64(2): 3767, np.int64(3): 1388, np.int64(4): 1431}
  Test label distribution: {np.int64(0): 1859, np.int64(1): 94, np.int64(2): 545, np.int64(3): 95, np.int64(4): 163}
  Epoch 1/30 loss: 1.2972
  Epoch 2/30 loss: 1.2562
  Epoch 3/30 loss: 1.2267
  Epoch 4/30 loss: 1.2126
  Epoch 5/30 loss: 1.1949
  Epoch 6/30 loss: 1.1814
  Epoch 7/30 loss: 1.1695
  Epoch 8/30 loss: 1.1500
  Epoch 9/30 loss: 1.1392
  Epoch 10/30 loss: 1.1338
  Epoch 11/30 loss: 1.1186
  Epoch 12/30 loss: 1.1082
  Epoch 13/30 loss: 1.0973
  Epoch 14/30 loss: 1.0853
  Epoch 15/30 loss: 1.0739
  Epoch 16/30 loss: 1.0663
  Epoch 17/30 loss: 1.0664
  Epoch 18/30 loss: 1.0471
  Epoch 19/30 loss: 1.0369
  Epoch 20/30 loss: 1.0301
  Epoch 21/30 loss: 1.0236
  Epoch 22/30 loss: 1.0121
  Epoch 23/30 loss: 1.0075
  Epoch 24/30 loss: 0.9948
  Epoch 25/30 loss: 0.9925
  Epoch 26/30 loss: 0.9785
  Epoch 27/30 loss: 0.9720
  Epoch 28/30 loss: 0.9710
  Epoch 29/30 loss: 0.9692
  Epoch 30/30 loss: 0.9521

  Results for held-out patient SC402:
  Accuracy: 75.98%
  Per-class metrics:
    W: precision=0.99 recall=0.99 f1=0.99 support=1859
    N1: precision=0.17 recall=0.04 f1=0.07 support=94
    N2: precision=0.51 recall=0.38 f1=0.44 support=545
    N3: precision=0.07 recall=0.32 f1=0.12 support=95
    REM: precision=0.25 recall=0.09 f1=0.13 support=163
  Confusion matrix (rows=true, cols=pred):
[[1839    1   11    7    1]
 [  20    4   40   28    2]
 [   3   12  207  296   27]
 [   1    4   49   30   11]
 [   1    2   97   49   14]]

========== FOLD 4/10 -- test=SC403 ==========
  Train label distribution: {np.int64(0): 17053, np.int64(1): 703, np.int64(2): 3827, np.int64(3): 1426, np.int64(4): 1385}
  Test label distribution: {np.int64(0): 1920, np.int64(1): 61, np.int64(2): 485, np.int64(3): 57, np.int64(4): 209}
  Epoch 1/30 loss: 1.2857
  Epoch 2/30 loss: 1.2508
  Epoch 3/30 loss: 1.2211
  Epoch 4/30 loss: 1.2066
  Epoch 5/30 loss: 1.1871
  Epoch 6/30 loss: 1.1790
  Epoch 7/30 loss: 1.1613
  Epoch 8/30 loss: 1.1428
  Epoch 9/30 loss: 1.1294
  Epoch 10/30 loss: 1.1199
  Epoch 11/30 loss: 1.1063
  Epoch 12/30 loss: 1.0932
  Epoch 13/30 loss: 1.0857
  Epoch 14/30 loss: 1.0680
  Epoch 15/30 loss: 1.0553
  Epoch 16/30 loss: 1.0491
  Epoch 17/30 loss: 1.0394
  Epoch 18/30 loss: 1.0296
  Epoch 19/30 loss: 1.0204
  Epoch 20/30 loss: 1.0071
  Epoch 21/30 loss: 0.9944
  Epoch 22/30 loss: 0.9875
  Epoch 23/30 loss: 0.9822
  Epoch 24/30 loss: 0.9714
  Epoch 25/30 loss: 0.9618
  Epoch 26/30 loss: 0.9641
  Epoch 27/30 loss: 0.9519
  Epoch 28/30 loss: 0.9460
  Epoch 29/30 loss: 0.9411
  Epoch 30/30 loss: 0.9236

  Results for held-out patient SC403:
  Accuracy: 77.38%
  Per-class metrics:
    W: precision=0.91 recall=0.99 f1=0.95 support=1920
    N1: precision=0.00 recall=0.00 f1=0.00 support=61
    N2: precision=0.72 recall=0.27 f1=0.39 support=485
    N3: precision=0.09 recall=0.37 f1=0.15 support=57
    REM: precision=0.29 recall=0.31 f1=0.30 support=209
  Confusion matrix (rows=true, cols=pred):
[[1896    4    6    6    8]
 [  25    0   10   11   15]
 [ 109    5  132  112  127]
 [  17    0   10   21    9]
 [  40    0   26   78   65]]

========== FOLD 5/10 -- test=SC404 ==========
  Train label distribution: {np.int64(0): 17439, np.int64(1): 598, np.int64(2): 3692, np.int64(3): 1430, np.int64(4): 1398}
  Test label distribution: {np.int64(0): 1534, np.int64(1): 166, np.int64(2): 620, np.int64(3): 53, np.int64(4): 196}
  Epoch 1/30 loss: 1.2637
  Epoch 2/30 loss: 1.2117
  Epoch 3/30 loss: 1.1954
  Epoch 4/30 loss: 1.1714
  Epoch 5/30 loss: 1.1551
  Epoch 6/30 loss: 1.1442
  Epoch 7/30 loss: 1.1242
  Epoch 8/30 loss: 1.1170
  Epoch 9/30 loss: 1.1035
  Epoch 10/30 loss: 1.0926
  Epoch 11/30 loss: 1.0783
  Epoch 12/30 loss: 1.0649
  Epoch 13/30 loss: 1.0539
  Epoch 14/30 loss: 1.0436
  Epoch 15/30 loss: 1.0369
  Epoch 16/30 loss: 1.0232
  Epoch 17/30 loss: 1.0161
  Epoch 18/30 loss: 1.0104
  Epoch 19/30 loss: 1.0070
  Epoch 20/30 loss: 0.9836
  Epoch 21/30 loss: 0.9809
  Epoch 22/30 loss: 0.9663
  Epoch 23/30 loss: 0.9601
  Epoch 24/30 loss: 0.9557
  Epoch 25/30 loss: 0.9435
  Epoch 26/30 loss: 0.9431
  Epoch 27/30 loss: 0.9328
  Epoch 28/30 loss: 0.9330
  Epoch 29/30 loss: 0.9146
  Epoch 30/30 loss: 0.9162

  Results for held-out patient SC404:
  Accuracy: 57.65%
  Per-class metrics:
    W: precision=0.85 recall=0.78 f1=0.81 support=1534
    N1: precision=0.11 recall=0.10 f1=0.10 support=166
    N2: precision=0.43 recall=0.30 f1=0.35 support=620
    N3: precision=0.02 recall=0.15 f1=0.04 support=53
    REM: precision=0.29 recall=0.40 f1=0.34 support=196
  Confusion matrix (rows=true, cols=pred):
[[1193   73  137   74   57]
 [  48   16   43   26   33]
 [ 119   40  186  183   92]
 [  22    5   10    8    8]
 [  15   13   53   37   78]]

========== FOLD 6/10 -- test=SC405 ==========
  Train label distribution: {np.int64(0): 16715, np.int64(1): 720, np.int64(2): 4095, np.int64(3): 1348, np.int64(4): 1526}
  Test label distribution: {np.int64(0): 2258, np.int64(1): 44, np.int64(2): 217, np.int64(3): 135, np.int64(4): 68}
  Epoch 1/30 loss: 1.2664
  Epoch 2/30 loss: 1.2324
  Epoch 3/30 loss: 1.2120
  Epoch 4/30 loss: 1.1935
  Epoch 5/30 loss: 1.1785
  Epoch 6/30 loss: 1.1610
  Epoch 7/30 loss: 1.1412
  Epoch 8/30 loss: 1.1296
  Epoch 9/30 loss: 1.1153
  Epoch 10/30 loss: 1.1096
  Epoch 11/30 loss: 1.0963
  Epoch 12/30 loss: 1.0879
  Epoch 13/30 loss: 1.0716
  Epoch 14/30 loss: 1.0637
  Epoch 15/30 loss: 1.0535
  Epoch 16/30 loss: 1.0461
  Epoch 17/30 loss: 1.0388
  Epoch 18/30 loss: 1.0244
  Epoch 19/30 loss: 1.0141
  Epoch 20/30 loss: 1.0017
  Epoch 21/30 loss: 0.9995
  Epoch 22/30 loss: 0.9919
  Epoch 23/30 loss: 0.9893
  Epoch 24/30 loss: 0.9723
  Epoch 25/30 loss: 0.9723
  Epoch 26/30 loss: 0.9632
  Epoch 27/30 loss: 0.9625
  Epoch 28/30 loss: 0.9495
  Epoch 29/30 loss: 0.9355
  Epoch 30/30 loss: 0.9367

  Results for held-out patient SC405:
  Accuracy: 51.10%
  Per-class metrics:
    W: precision=0.99 recall=0.54 f1=0.69 support=2258
    N1: precision=0.11 recall=0.16 f1=0.13 support=44
    N2: precision=0.18 recall=0.43 f1=0.26 support=217
    N3: precision=0.05 recall=0.15 f1=0.07 support=135
    REM: precision=0.12 recall=0.91 f1=0.21 support=68
  Confusion matrix (rows=true, cols=pred):
[[1209   43  341  376  289]
 [   1    7   20    5   11]
 [   4    8   93   16   96]
 [   7    6   45   20   57]
 [   1    0    5    0   62]]

========== FOLD 7/10 -- test=SC406 ==========
  Train label distribution: {np.int64(0): 16904, np.int64(1): 708, np.int64(2): 3905, np.int64(3): 1347, np.int64(4): 1492}
  Test label distribution: {np.int64(0): 2069, np.int64(1): 56, np.int64(2): 407, np.int64(3): 136, np.int64(4): 102}
  Epoch 1/30 loss: 1.2878
  Epoch 2/30 loss: 1.2486
  Epoch 3/30 loss: 1.2283
  Epoch 4/30 loss: 1.2013
  Epoch 5/30 loss: 1.1824
  Epoch 6/30 loss: 1.1702
  Epoch 7/30 loss: 1.1539
  Epoch 8/30 loss: 1.1422
  Epoch 9/30 loss: 1.1265
  Epoch 10/30 loss: 1.1176
  Epoch 11/30 loss: 1.1059
  Epoch 12/30 loss: 1.0958
  Epoch 13/30 loss: 1.0736
  Epoch 14/30 loss: 1.0666
  Epoch 15/30 loss: 1.0558
  Epoch 16/30 loss: 1.0482
  Epoch 17/30 loss: 1.0338
  Epoch 18/30 loss: 1.0336
  Epoch 19/30 loss: 1.0198
  Epoch 20/30 loss: 1.0078
  Epoch 21/30 loss: 0.9980
  Epoch 22/30 loss: 0.9980
  Epoch 23/30 loss: 0.9856
  Epoch 24/30 loss: 0.9835
  Epoch 25/30 loss: 0.9709
  Epoch 26/30 loss: 0.9636
  Epoch 27/30 loss: 0.9582
  Epoch 28/30 loss: 0.9412
  Epoch 29/30 loss: 0.9446
  Epoch 30/30 loss: 0.9280

  Results for held-out patient SC406:
  Accuracy: 70.97%
  Per-class metrics:
    W: precision=0.97 recall=0.90 f1=0.93 support=2069
    N1: precision=0.08 recall=0.20 f1=0.12 support=56
    N2: precision=0.30 recall=0.09 f1=0.14 support=407
    N3: precision=0.09 recall=0.01 f1=0.01 support=136
    REM: precision=0.10 recall=0.55 f1=0.16 support=102
  Confusion matrix (rows=true, cols=pred):
[[1861   28   45    9  126]
 [   7   11    5    0   33]
 [  54   66   37    1  249]
 [   0   16    5    1  114]
 [   0   13   33    0   56]]

========== FOLD 8/10 -- test=SC407 ==========
  Train label distribution: {np.int64(0): 17055, np.int64(1): 675, np.int64(2): 3909, np.int64(3): 1321, np.int64(4): 1396}
  Test label distribution: {np.int64(0): 1918, np.int64(1): 89, np.int64(2): 403, np.int64(3): 162, np.int64(4): 198}
  Epoch 1/30 loss: 1.2962
  Epoch 2/30 loss: 1.2458
  Epoch 3/30 loss: 1.2253
  Epoch 4/30 loss: 1.2108
  Epoch 5/30 loss: 1.1911
  Epoch 6/30 loss: 1.1806
  Epoch 7/30 loss: 1.1630
  Epoch 8/30 loss: 1.1417
  Epoch 9/30 loss: 1.1253
  Epoch 10/30 loss: 1.1235
  Epoch 11/30 loss: 1.1079
  Epoch 12/30 loss: 1.0939
  Epoch 13/30 loss: 1.0891
  Epoch 14/30 loss: 1.0746
  Epoch 15/30 loss: 1.0667
  Epoch 16/30 loss: 1.0574
  Epoch 17/30 loss: 1.0449
  Epoch 18/30 loss: 1.0413
  Epoch 19/30 loss: 1.0276
  Epoch 20/30 loss: 1.0196
  Epoch 21/30 loss: 1.0155
  Epoch 22/30 loss: 1.0038
  Epoch 23/30 loss: 0.9908
  Epoch 24/30 loss: 0.9829
  Epoch 25/30 loss: 0.9866
  Epoch 26/30 loss: 0.9714
  Epoch 27/30 loss: 0.9522
  Epoch 28/30 loss: 0.9598
  Epoch 29/30 loss: 0.9541
  Epoch 30/30 loss: 0.9399

  Results for held-out patient SC407:
  Accuracy: 74.87%
  Per-class metrics:
    W: precision=0.99 recall=0.98 f1=0.98 support=1918
    N1: precision=0.12 recall=0.73 f1=0.21 support=89
    N2: precision=0.49 recall=0.23 f1=0.31 support=403
    N3: precision=0.03 recall=0.01 f1=0.02 support=162
    REM: precision=0.41 recall=0.18 f1=0.25 support=198
  Confusion matrix (rows=true, cols=pred):
[[1880   35    3    0    0]
 [   1   65    9    5    9]
 [   9  260   92   12   30]
 [   4   80   65    2   11]
 [  13   84   20   46   35]]

========== FOLD 9/10 -- test=SC408 ==========
  Train label distribution: {np.int64(0): 17150, np.int64(1): 696, np.int64(2): 4050, np.int64(3): 1133, np.int64(4): 1463}
  Test label distribution: {np.int64(0): 1823, np.int64(1): 68, np.int64(2): 262, np.int64(3): 350, np.int64(4): 131}
  Epoch 1/30 loss: 1.2846
  Epoch 2/30 loss: 1.2422
  Epoch 3/30 loss: 1.2176
  Epoch 4/30 loss: 1.1983
  Epoch 5/30 loss: 1.1830
  Epoch 6/30 loss: 1.1710
  Epoch 7/30 loss: 1.1544
  Epoch 8/30 loss: 1.1359
  Epoch 9/30 loss: 1.1301
  Epoch 10/30 loss: 1.1169
  Epoch 11/30 loss: 1.1078
  Epoch 12/30 loss: 1.0994
  Epoch 13/30 loss: 1.0866
  Epoch 14/30 loss: 1.0884
  Epoch 15/30 loss: 1.0706
  Epoch 16/30 loss: 1.0636
  Epoch 17/30 loss: 1.0579
  Epoch 18/30 loss: 1.0457
  Epoch 19/30 loss: 1.0425
  Epoch 20/30 loss: 1.0319
  Epoch 21/30 loss: 1.0238
  Epoch 22/30 loss: 1.0144
  Epoch 23/30 loss: 1.0070
  Epoch 24/30 loss: 1.0012
  Epoch 25/30 loss: 0.9895
  Epoch 26/30 loss: 0.9852
  Epoch 27/30 loss: 0.9771
  Epoch 28/30 loss: 0.9653
  Epoch 29/30 loss: 0.9582
  Epoch 30/30 loss: 0.9497

  Results for held-out patient SC408:
  Accuracy: 59.15%
  Per-class metrics:
    W: precision=0.96 recall=0.76 f1=0.85 support=1823
    N1: precision=0.00 recall=0.00 f1=0.00 support=68
    N2: precision=0.05 recall=0.01 f1=0.01 support=262
    N3: precision=0.35 recall=0.29 f1=0.32 support=350
    REM: precision=0.08 recall=0.47 f1=0.14 support=131
  Confusion matrix (rows=true, cols=pred):
[[1393   38   35   73  284]
 [  17    0    0    7   44]
 [   0   17    2   78  165]
 [  38   34    3  102  173]
 [   1   36    0   33   61]]

========== FOLD 10/10 -- test=SC409 ==========
  Train label distribution: {np.int64(0): 17234, np.int64(1): 745, np.int64(2): 3751, np.int64(3): 1313, np.int64(4): 1362}
  Test label distribution: {np.int64(0): 1739, np.int64(1): 19, np.int64(2): 561, np.int64(3): 170, np.int64(4): 232}
  Epoch 1/30 loss: 1.2814
  Epoch 2/30 loss: 1.2412
  Epoch 3/30 loss: 1.2215
  Epoch 4/30 loss: 1.2090
  Epoch 5/30 loss: 1.1901
  Epoch 6/30 loss: 1.1752
  Epoch 7/30 loss: 1.1645
  Epoch 8/30 loss: 1.1539
  Epoch 9/30 loss: 1.1379
  Epoch 10/30 loss: 1.1285
  Epoch 11/30 loss: 1.1099
  Epoch 12/30 loss: 1.1024
  Epoch 13/30 loss: 1.0940
  Epoch 14/30 loss: 1.0814
  Epoch 15/30 loss: 1.0723
  Epoch 16/30 loss: 1.0601
  Epoch 17/30 loss: 1.0573
  Epoch 18/30 loss: 1.0408
  Epoch 19/30 loss: 1.0334
  Epoch 20/30 loss: 1.0274
  Epoch 21/30 loss: 1.0211
  Epoch 22/30 loss: 1.0116
  Epoch 23/30 loss: 1.0023
  Epoch 24/30 loss: 0.9889
  Epoch 25/30 loss: 0.9854
  Epoch 26/30 loss: 0.9804
  Epoch 27/30 loss: 0.9711
  Epoch 28/30 loss: 0.9622
  Epoch 29/30 loss: 0.9481
  Epoch 30/30 loss: 0.9445

  Results for held-out patient SC409:
  Accuracy: 72.33%
  Per-class metrics:
    W: precision=0.93 recall=0.91 f1=0.92 support=1739
    N1: precision=0.01 recall=0.05 f1=0.01 support=19
    N2: precision=0.54 recall=0.47 f1=0.50 support=561
    N3: precision=0.55 recall=0.14 f1=0.22 support=170
    REM: precision=0.25 recall=0.39 f1=0.31 support=232
  Confusion matrix (rows=true, cols=pred):
[[1589   32   67    7   44]
 [   5    1   10    0    3]
 [  45   57  263    8  188]
 [  69   14   30   24   33]
 [   3   20  113    5   91]]

========== FINAL LOPO SUMMARY ==========
Mean accuracy across 10 folds: 64.91%
  Mean F1 [W]: 0.871
  Mean F1 [N1]: 0.077
  Mean F1 [N2]: 0.306
  Mean F1 [N3]: 0.115
  Mean F1 [REM]: 0.190