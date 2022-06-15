# Cornelissen-et-al.

### Representing molecules

#### Requirements :
•	Windows Command line

•	Anaconda : https://docs.conda.io/projects/conda/en/latest/user-guide/install/download.html

•	Jupyter notebook : https://jupyter.org/install

•	Environment : env_Fleur.yaml

•	Script : Drawing_Molecules_and_substructures.ipynb

For easier navigation, save the environment and the script in the same folder. 


#### Install the environment : 
Open the Windows Command line

Go to the folder where the file.yaml is with the Command line  (cd C:\...)

Create the environment (conda env create -n Name –file name.yaml)

Activate environment (conda activate Name)

#### Open jupyter Notebook : 
Once in the environment, open Jupyter Notebook (jupyter notebook)

#### Open the file : 
In the file navigator of Jupyter notebook, select the script.

#### Running the script : 
To represent molecules, the SMILES of the molecule of interest is required. 

To highlight substructure, change the MACCS key description to the one wanted. 

Run each cell by using Shift+Enter.

#### Results : 
The script saves at the end the molecule where the Jupyter Notebook was launched. 

### Environment
#### Must be save as .yaml file
channels:
  - anaconda
  - conda-forge
  - rdkit
  - defaults
  - bioconda
  
dependencies:
  - anaconda::python=3.6.10
  - anaconda::numpy=1.18.1
  - anaconda::h5py=2.10.0
  - anaconda::jupyter=1.0.0
  - conda-forge::tqdm=4.46.0
  - rdkit::rdkit=2020.03.2
  - ipykernel=5.1.0

