# Dataset-split-for-BSWNet
Detailed description of the dataset split for BSWNet. This dataset split is used to train the model in the paper: **BSWNet: An Underwater Acoustic Target Recognition System with Band splitting and Sub-band Weighting**

## ShipsEar

To ensure data balance, a 5-class subset from [ShipsEar](https://underwaternoise.atlanttic.uvigo.es/) is utilized as the experimental dataset. We randomly picked 20% recordings in each class for validation and 10% recordings to form a test set. If the number of recordings in a class is less than 10, we use the same data for validation and test.

The detailed split is as follows:

|Category|Training set| Valid set| Test set|
| --- | --- | --- | --- |
| Fishboat | Fishboat_73.wav <br> Fishboat_75.wav <br> Fishboat_76.wav| Fishboat_74.wav | Fishboat_74.wav |
| Motorboat | Motorboat_21.wav <br> Motorboat_27.wav <br> Motorboat_33.wav <br> Motorboat_39.wav <br> Motorboat_50.wav <br> Motorboat_52.wav <br> Motorboat_72.wav <br> Motorboat_77.wav <br> Motorboat_79.wav | Motorboat_51.wav <br> Motorboat_70.wav  | Motorboat_26.wav <br> Motorboat_45.wav |
| Natural Noise | Naturalnoise_81.wav <br> Naturalnoise_83.wav <br> Naturalnoise_84.wav <br> Naturalnoise_85.wav <br> Naturalnoise_87.wav <br> Naturalnoise_88.wav <br> Naturalnoise_90.wav <br> Naturalnoise_92.wav | Naturalnoise_82.wav <br> Naturalnoise_86.wav | Naturalnoise_91.wav |
| Passengers | Passengers_10.wav <br> Passengers_11.wav <br> Passengers_13.wav <br> Passengers_14.wav <br> Passengers_17.wav <br> Passengers_32.wav <br> Passengers_35.wav <br> Passengers_36.wav <br> Passengers_40.wav <br> Passengers_42.wav <br> Passengers_43.wav <br> Passengers_55.wav <br> Passengers_59.wav <br> Passengers_60.wav <br> Passengers_62.wav <br> Passengers_63.wav <br> Passengers_64.wav <br> Passengers_65.wav | Passengers_12.wav <br> Passengers_34.wav <br> Passengers_38.wav <br> Passengers_41.wav <br> Passengers_54.wav | Passengers_61.wav <br> Passengers_67.wav <br> Passengers_8.wav |
| RORO | RORO_18.wav <br> RORO_20.wav <br> RORO_58.wav <br> RORO_78.wav | RORO_19.wav | RORO_19.wav |

