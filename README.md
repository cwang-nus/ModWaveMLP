# ModWaveMLP: MLP-based Mode Decomposition and Wavelet Denoising Model to Defeat Complex Structures in Traffic Forecasting

Code for our paper: "[ ModWaveMLP: MLP-based Mode Decomposition and Wavelet Denoising Model to Defeat Complex Structures in Traffic Forecasting]".



## 1. Table of Contents

```text
data            ->  metr-la and pems-bay raw data and processed data
Datasets        ->  dataset preprocessing code
Model           ->  model implementation 
```

## 2. Requirements

```bash
pip install -r requirements.txt
```

## 3. Data Preparation

Alterbatively, the datasets can be found as follows:

- METR-LA and PEMS-BAY: These datasets were released by DCRNN[1]. Data can be found in its [GitHub repository](https://github.com/liyaguang/DCRNN).
Please put these two files metr-la.h5 and pems-bay.h5 in the data folder

## 4. Training the ModWaveMLP Model

The hyperparameters of ModWaveMLP can be changed in the Parameters.py

```bash
python run_MoDWaveMLP.py --dataset metr-la --horizon 12 --history_length 12
python run_MoDWaveMLP.py --dataset pems-bay --horizon 12 --history_length 12
```
## If you have any questions and suggestions, please feel free to contact us through this e-mail (kenianqingzheng@qq.com), looking forward to communicating with you!
