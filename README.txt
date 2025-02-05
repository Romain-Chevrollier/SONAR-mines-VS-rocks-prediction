# SONAR Rocks VS Mines prediction

## Overview

This project is made to make prediction with a dataset from a sonar. The goal being to classify if the object is a rock or a mine.
It uses python with numpy, pandas and sklearn on google collab.

## What i learned

For a simple project such as this one we start by importing the data, then we can analyse and do a preprocessing of the data. 
We will split the data into train test to have some sort of unseen data for the validation. Then we fit the data and we can do prediction.

Stratify parameter : Used to have the same proportion of each labels in each split
Random_state : Used to always get the same split (If random_state different result of the model might change)

## Credits

This project has been made by following this video : "https://www.youtube.com/watch?v=fiz1ORTBGpY&list=PLfFghEzKVmjvuSA67LszN1dZ-Dd_pkus6&ab_channel=Siddhardhan" from Siddhardhan channel.
I also used this website to try more model : "https://medium.com/@andrii.gozhulovskyi/choosing-a-model-for-binary-classification-problem-f211f7a4e263"