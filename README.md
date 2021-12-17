# AMLS_21-22_SN21166038
This is the assignment repository for module, Applied Machine Learning Systems.

Folder/file structures are important to successfully run the five machine learning model files. Especially take care with two image256 folders.
The machine learning model files should be run in Jupyternotebook. Some common libraries, like numpy, pandas, tensorflow, sklearn should be ready before executine those five model files (file extension is .ipynb)

There are some other files or folders in this repository. They are practice files when doing this assignment. Please ignore those files.

All the necessary files for this assignment are in "FinalSubmission" folder; It includes:
  1. KNN model for Task A
  2. SVM model for Task A
  3. KNN model for Task B
  4. SVM model for Task B
  5. CNN model for Task B
  6. dataset folder               is the original data set
  
        image subfolder           contains 3000 original MRI images
        
        image256 subfolder        contains 3000 resolution reduced MRI images; Necessary to run all five models in JupyterNotebook!!!
        
        label.csv                 is image label file
        
  7. test-2 folder                is the new released data set
  
        image subfolder           contains 200 new MRI images
        
        image256 subfolder        contains 200 new resolution reduced MRI images; Necessary to run all five models in JupyterNotebook!!!
        
        label.csv                 is image label file

***********************************************************************************************************************************************
Tasks
The machine learning tasks include:
A. Binary task
Build a classifier to identify whether there is a tumor in the MRI images.
B. Multiclass task
Build a classifier to identify the type of tumor in each MRI image (meningioma tu-
mor, glioma tumor, pituitary tumor or no tumor).
You should design separate models for each task and report training errors, validation er- rors, and hyper-parameter tuning procedures. You are allowed to use the same model/methodology for different tasks, but you must explain the reason behind your own choices. If you tried several models for one task, feel free to show them in your code and compare the results in the report. Among all the models you may try for both tasks, you should implement at least one non-deep learning model (e.g. For task A: one SVM model and one deep learning model; for task B: one deep learning model).
***********************************************************************************************************************************************
