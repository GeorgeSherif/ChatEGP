### Arabic Newspaper Sentiment Analysis
This repository contains 3 models for 3 different approaches. The three approaches are as follows:
  1) Using preprocessing on the dataset --> Model With Preprocessing.ipynb
  2) Using raw dataset --> Model Without Preprocessing.ipynb
  3) Using Data Augmentation on our dataset --> Model With Data Augmentation.ipynb
 
Each model run for 16 epoch and the best epoch is chosen for the next phase.
The next phase consist of translating the Arabic dataset into English, and then testing the best epoch chosen before to check the accuracy. These steps can be
founded in both files called "Testing After Preprocessing.ipynb", and "Testing Without Preprocessing & Testing With Data Augmentation.ipynb".

In the remaining files, side tasks such as preprocessing the English dataset can be found in "preprocessing.ipynb", and the data augmentation can be found in "paraphrasewithBertAgain.ipynb"

The last file is the "Results.ipynb", which combines the results of all previous approaches and draw some diagrams to visualize the results.
