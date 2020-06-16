# zindi-sansa-informal-settlements-in-south-africa
### Install dependencies
pip install -r requirements.txt

### Expected directory structure
./data directory should contain the following files
-2528C.tif
-2930D.tif
-Train.csv
-Test.csv

### Training the models
Run the notebooks in the following order
0: Preprocessing
0_zindi_sansa_preprocessing

1-7: Training 
1_zindi_sansa_eff5_cmix_F0
2_zindi_sansa_eff5_F0
3_zindi_sansa_eff5_F1
4_zindi_sansa_eff5_F2
5_zindi_sansa_eff5_F3
6_zindi_sansa_eff5_F4
7_zindi_sansa_effnet4

8: Inference
8_zindi_sansa_inference

