# Welcome to Iron-Lens: the Computer Vision Exercise!

## Getting Started
The directory for this exercise can be found in ~/cv_exercise.  
There, you will find three sub-directories: 
- exercise
- deadbool
- protests_images

As the name suggests, the `exercise` directory contains everything you'll need to complete the exercise.   
This includes the jupyter notebook you'll use to train and evaluate your code, models, and additional tutorials.  
The `deadbool` and `protests_images` directories contain the data you'll need to complete the exercise. 


### Defining Your Environment
To save you the pain of creating your own environment, we've set up an Anaconda environment with everything that 
you'll need to complete the exercise.  

If you haven't already created a virtual environment for this workshop, do the following:

1. Run the command `conda env create -f cv\environment_cv.yml`
2. Run the command `conda activate psagot-2020-cv`

If you already have an environment named `psagot-2020-cv`, do the following:

1. Run the command `conda activate psagot-2020-cv`.
2. Run the command `conda env update -f cv\environment_cv.yml --prune`

Now run the following:

1. Run the command `python cv\check.py` and make sure its ran without any errors and `yay` has been printed
2. Ino order to exit, run the command `conda deactivate`


### Completing the Exercise
Refer to the notebook `run_me.ipynb` and start building your solution!  
In computer vision, it is important to get a feel for your data. We therefore provide you with a simple notebook,
`visualize_images.ipynb` that randomly visualizes images in a given directory.   


### Additional Notes
- If, when trying to import `mtcnn`, you receive the following error: 
``` ImportError: libGL.so.1: cannot open shared object file: No such file or directory ```  
  run the following command:  
  ``` sudo apt install libgl1-mesa-glx ```
- Often times, data isn't perfect, and images may be corrupted. Pay attention to this as you complete the exercise. 
