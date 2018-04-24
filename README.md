# Twitter-Emotion-Classify-CSCE-588
Predict emotions amger, fear, joy, sadness of tweets using LSTM, BiLSTM
Annotations:
Anger -1 
Fear - 2
Joy - 3
Sadness - 4

Dataset: Semeval Task 2018: Affects in Twitter

File description:

1. twitter_emotion_classify_titli.py: full source code

2. sample_output.txt: Sample output from one execution. The hyperparameters should be changed and the code should be reexecured to observe                       their effect in the output.

3. Figures show the variation result of predicted from the actual. Figures ending with single digit show the pointwise result variation of LSTM model and figures ending with double digit show the pointwise result variation of BiLSTM model. We have 2000 test samples, therefore lenght of the labels vector is 2000. Obviously the variation vector is 2000 digit long. To show the result less clumsy, the result is divided five non-overlapping subsets of 400 element each. 

Figure_1.png : shows first 0 - 400 elements of variation vector for LSTM model

Figure_2.png : shows next 400 - 800 elements of variation vector for LSTM model

Figure_3.png : shows next 800 - 1200 elements of variation vector for LSTM model

Figure_4.png : shows next 1200 - 1600 elements of variation vector for LSTM model

Figure_5.png : shows next 1600 - 2000 elements of variation vector for LSTM model

Similarly, 

Figure_11.png : shows first 0 - 400 elements of variation vector for BiLSTM model

Figure_22.png : shows next 400 - 800 elements of variation vector for BiLSTM model

Figure_33.png : shows next 800 - 1200 elements of variation vector for BiLSTM model

Figure_44.png : shows next 1200 - 1600 elements of variation vector for BiLSTM model

Figure_55.png : shows next 1600 - 2000 elements of variation vector for BiLSTM model

