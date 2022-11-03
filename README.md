# nlptasks

This repository is our approaches for all assignments in the final project for the **DIKU NLP Course** 2022/2023. The authors have the following KU ID's:

* vdh406
* hlq592
* knd313

---

The directory has three main folders:

**Data**. 
This folder contains all the data needed for the tasks. The data was downloaded and divided into pandas dataframes and stored as .csv files.
Throughout the tasks we added more columns to the data frames, such as prediction labels, meta inputs, tokenised columns etc. The folder
also contains preprocessed input, validation and testing data for different languages stored as pytorch tensors. These were used for training multiple bi-lstm models.


**Models**.
Throughout the project we created multiple different models with different structure and trained with different inputs. All of these models were saved to be reused later
to avoid retraining models. 

**Notebooks**.
This folder contains all the code for the different tasks. The name of the notebooks indicate which section it pertains to. Some notebooks can be run from start to finish while others have to be run in google colab or have instructions on how to run the different cells.

