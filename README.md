# OpenSourceGIS - Exercise 6: Open Route Service and Ohsome API

In this exercise, you will learn how to use the Open Route Serice and Ohsome APIs using Python. Therefore, we need to set up the right python environment.  

## Setting up the Python environment

1. Open the "Anaconda Prompt" from the Windows Menu. 
2. Navigat to the folder "env" of this repository. 
3. Create a new virtual environment: 

  `conda env create -f ors_environment.yml`
  
  If you are asked to provide Admin credentials, just click 'No'.
  
4. Activate the new virtual environment:

  `activate ors`
  
  If you successfully activated your new environment command prompt should look something like this with the name of the activate environment (ors) in brackets in front of your current path: 
  
`(ors) M:\git\OpenSourceGIS_06\env>`

5. Install the openrouteservice and geopy packages

  `conda install openrouteservice geopy`
  
## Starting the jupyter notebook 

1. Make Firefox or Chrome your default Web Browser: For instructions on how to do that, see [here](https://support.microsoft.com/en-ca/help/4028606/windows-10-change-your-default-browser).
2. Start the Jupyter notebook server:

  `jupyter notebook`
  
Your browser should be opened automatically directing you to localhost:8888
