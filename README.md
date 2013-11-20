kaggle_AMS_2013_14_solar
========================

kaggle-AMS 2013-14 Solar Energy

How to run:
1. Set up a folder with the following structure:
    ----[this folder]
      |---- /train
      |  |---- [all training ncdf4 files]
      |
      |---- /test
      |  |---- [all test ncdf4 files]
      |
      |---- train.csv
      |---- sampleSubmission.csv
      |---- model.R
2. cd to [this folder]
3. execute the command: R -f model.R

Output:
sub_final.csv in [this folder]
