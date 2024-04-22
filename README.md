# CSE-572-Project

# Data Location
Please clone and unzip the following for the data and npy files.
https://drive.google.com/file/d/1J5ity1V7hbDbp3PmzmxBWVQfe6H8LH9P/view?usp=sharing


Data Preprocessing and 5-fold crossvalidation testing of models require more ram than free tier of Colab offers.

[Baseline model with no pre-processing](0_nopreprocessing.ipynb)

[Data PreProcessing](1_data_preprocessing.ipynb)

[Diffrent Data Models](2_data_models.ipynb)

[Parameter Tuning CatBoost and LGBM](3_parameter_tuning.ipynb)

[Parameter Tuning Keras](3.1_parameter_tuning_keras.ipynb)

[Tuned Model Results](<4_final_model copy.ipynb>)

[Model analysis for Best Model](5_model_analysis.ipynb)


Colab for final results here:
[https://colab.research.google.com/drive/1ONzc62HA0PUMslJeZIPK0v4tAnVIfrM6?usp=sharing](https://colab.research.google.com/drive/1QK96xC11zFe4yfMS0JHHmUxm_52O1aKj?usp=sharing)

Please note: the Colab only uses the processed data and does 5-fold cross validation and runs the LGBM model with tuned parameters.Also it runs the Deeplearning models.

We cannot have everything in the colab as it reaches out of memory when pre-processing.
