=====Data Process=====
Our data are preprocessed and embedded through data_process.ipynb.
Please download the "訓練資料集_first.zip" from the contest website, unzip it, and rename the folder to "train_data_first". Also, download the "24_ESun_public_y_answer.csv". Put the "train_data_first" folder, the "24_ESun_public_y_answer.csv" file and "data_process.ipynb" in the same directory, then run data_process.ipynb.

The data processed will be store in "./train_data_processed/" and "./public_data_processed/", please create these two folder in the same directory as above.

It will take about 2 hours to process the data.

=====DNN=====
This is the model that generates our best result. 
Please put all files in the same directory, and run DNN.ipynb. 

Unfortunately, we did not set random seed in the script. 
However, we did save the best model and best prediction. 
They are model(best_result).pth and predict(best_result).csv. 

The first line of each block briefly explain the code. 

=====LSTM=====
Please run LSTM.ipynb to generate the predictions. If you want to directly play with model.zip, just run the last part of LSTM.ipynb.

data_process_lstm.ipynb uses another way to deal with all .csv files and make those data readable for LSTM. However, you don't have to run it before running LSTM.ipynb because we've stored the pre-processed data and they are already usable in LSTM.ipynb.
