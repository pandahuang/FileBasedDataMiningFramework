# FileBasedDataMiningFramework
This is a framework for file-based data mining jobs.

Frame:
  1.Data Management.
  2.Data Processing and Preprocessing.
  3.Model of Machine Learning and Data Mining.
  4.Analysis function of Source Data and Model Verification.
  5.Visualization of Source Data and Analysis Result.
  6.Pipeline function for transform data between different core modules.
  
Usage:
  1.Put your data files under customerized directoried in Data Management and Add the file names to the DataManager
  2.Put your data processing function under Processing as well as your Preprcessing jobs. Get file name from DataManager.
  3.Put you ML and DM models under Models and Make sure all of your models can be trained by calling get_XXX_model() function.
  4.Put your analysis scripts under Analysis. Find data path in DataManager and Get Result of model from Model.
  5.Put you plot function under Visaulization, which also visualizes the statistics of source data by Analysis.
  6.Use Pipeline to exchange data or file names between different modules.
