# This repository contains all the problems I had to use the intellectual methods for with code structure and ML modelling
Task 1: Wrong-transport-scheme-for-CDEK
OpenSource code for CDEK
This code's input is an Excel list with typical data with parcels from warehouse A to warehouse B, and the output is the list of parcels were sorted wrongly (destination office from A != B)
Even if it is easy, this code gives CDEK 1.5h/week per sorting centre to monitor the wrong transport schemes and adjust it on time. Economy is about 122'000 rubles/week.
As the input we upload the file from the inner WMS programm to get the whole pool of parcels from A to B within a week. Then run the code in Colab and download the .xlsx file with only the wrong sorting schemes and UID codes of parcels were misshipped.

Task 2: film genre classification via multiple ML to AI approaches
OpenSource code for Kaggle competition on the jrobischon/wikipedia-movie-plots dataset
The task was to correctly predict genre of the film based on the plot. To avoid noise, we used top-4 genres with ~11k positions dataset
Decision forests, LSTM and SVC model were used with adjusted parameters and various preprocessing libraries
The best outcome of this work was that we've doubled the genre labels to predict (from baseline of 2 genres to 4 in our case) while decreased accuracy from 61 to 58 percent accordingly. 61% is the gold medal winner on the original task in Kaggle.
