# IISC_Internsip
 These are the files for my IISC Internship


# Assignment 1:
## RAG Implementation

### This folder consist of a iPython notebook to explore RAG.
### The Data folder consist of 2 csv files articles referring to news artciles extracted through a API and news referring to scrapped websites using Webscraping libraries.
### The corresponding code for data collection is located innside the Data folder /Data/Source.

#### Steps to Reproduce:
1. git clone https://github.com/JAYANTH-MOHAN/IISC_Internsip.git
2. cd IISC_Internsip
3. cd RAG
4. conda env create -f environment.yml
5. conda activate rag
6. pip install -r req.txt
7. python -m ipykernel install --user --name=rag

   
8. Change the data to the location in your system. Accordingly, change the path name.
9. Finally, run the ipynb (code.ipynb) to validate the results.




## To access jupyter lab in ssh machine 

1. Open a new terminal and run this:  "ssh -N -L 8889:localhost:8889 asrivastava@10.192.27.144"
2. Activate the rag inside jupyterlab when running code.ipynb
