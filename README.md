# London-Transportation-modeling

Description: 
This project intend to mathematicaly model behaviour of London travellers, starting from very simple utility functions and iteratively improving models.
Model are tested with con sistent test depending on models characteristics. Data used during this project comes from the biogeme website (TRANSP-OR laboratory at EPFL)(see Section Data Set used to access it and for references). This project is not finished yet, and thus this repisotory contains only a 
tentative code.

Instalation:
The code is presented on a Jupyter Notebook (see dependencies) and should be run like a Jupyter Notebook.
Download the file named "Modeling" and open it with means of Jupyter Notebook from Anaconda (see dependencies). 
Then it is necessary to download all libraries necessary (see dependencies), and to change the import cell, by indicating the path to the Dataset ( see Data used) in the variable "data_file".
A dict called "all_results" created in the first cell, the results obtained are available in this repository.

Dependencies : 

  jupyter                       1.0.0 
  
  notebook                      6.4.8
  
  conda                         4.14.0
  
  pyhton                        3.9.12
  
  biogeme                       3.2.10
  
  pandas                        1.4.2  
  
  numpy                         1.23.3
  
  Support:
  For any questions or help, you can contact : maxime.dunod@epfl.ch
  
  Authors and acknowledgment : 
  This project was possible thanks to the access given by the biogeme team, Michel Bierlaire's class team, and Tim Hillel.
  

Dataset used : 
London Passenger Mode Choice (Hillel, 2018), than can be download from biogeme website : https://biogeme.epfl.ch/#data
Hillel, T., Elshafie, M. Z. E. B. and Jin, Y. (2018), ‘Recreating passenger mode choice-sets for transport simulation: A case study of London, UK’, 171(1), 29–42.
URL: https://www.icevirtuallibrary.com/doi/10.1680/jsmic.17.00018


  
