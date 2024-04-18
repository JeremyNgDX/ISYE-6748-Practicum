As the raw files are too large to be uploaded directly onto GitHub, the following steps can be taken to run this code
1. Download original csv files, there are 8 in total from https://www.kaggle.com/datasets/jishnukoliyadan/vibration-analysis-on-rotating-shaft.
2. Save all the files in the same folder/directory as the one that you run the Jupyter Notebooks
3. Run notebook "Data-Processing" which adds an index to each of the original csv files and save a copy of it with the suffix "_index" behind the original file name
4. Next, run the Notebooks "Data Pre-processing sample for 0D and 0E" and "Data Pre-processing for 1, 2, 3 and 4D and E". These 2 will clean the data and add on a "Time_Index_Labels" which allow us to portion the dataset easily.
5. After which, run the "Feature_Engineering_Preparation" notebook
6. Lastly, run the "Feature Engineering and modelling FFT" notebook to run the Fast Fourier Transform (FFT) algorithm for training the model
