=====Data Process=====
Our data are preprocessed and embedded through data_process.ipynb.
Please download the "訓練資料集_first.zip" from the contest website, unzip it, and rename the folder to "train_data_first". Also, download the "24_ESun_public_y_answer.csv". Put the "train_data_first" folder, the "24_ESun_public_y_answer.csv" file and "data_process.ipynb" in the same directory, then run data_process.ipynb.

=====DNN=====
This is the model that generates our best result. 
Please put all files in the same directory, and run DNN.ipynb. 

Unfortunately, we did not set random seed in the script. 
However, we did save the best model and best prediction. 
They are model(best_result).pth and predict(best_result).csv. 

The first line of each block briefly explain the code. 
=============
