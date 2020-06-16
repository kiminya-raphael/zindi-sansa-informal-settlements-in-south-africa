# zindi-sansa-informal-settlements-in-south-africa
### Install dependencies
pip install -r requirements.txt

### Expected directory structure
./data directory should contain the following files <br/>
- 2528C.tif
- 2930D.tif
- Train.csv
- Test.csv

### Training the models
Run the notebooks in the following order. <br/>

#### 0: Preprocessing
0_zindi_sansa_preprocessing

#### 1-7: Training 
1_zindi_sansa_eff5_cmix_F0<br />
2_zindi_sansa_eff5_F0<br />
3_zindi_sansa_eff5_F1<br />
4_zindi_sansa_eff5_F2<br />
5_zindi_sansa_eff5_F3<br />
6_zindi_sansa_eff5_F4<br />
7_zindi_sansa_effnet4<br />

#### 8: Inference
8_zindi_sansa_inference

