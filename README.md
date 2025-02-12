# MNCDA  

## Introduction  
The project  is an implementation of a multi-scale neighbors and diverse relationships encoding and node feature correlation learning method for inferring disease-related circRNAs (MNCDA). 

---

## Catalogs  
- **/data**: Contains the dataset used in our method.
- **/code**: Contains the code implementation of MNCDA algorithm.
- **dataloader.ipynb**: Processes the circRNA and disease similarities, associations, features, and adjacency matrices.
- **MNCDA.ipynb**: Defines the model and trains the model.
- **MNCDA_CaseStudy.ipynb**: Experiments for case study.

---

## Environment  
The MNCDA code has been implemented and tested in the following development environment: 

- Python == 3.9.7
- Matplotlib == 3.9.4
- PyTorch == 1.8.0
- NumPy == 1.26.4
- Scikit-learn == 1.6.1
- Scipy == 1.13.1

---

## Dataset  
- **circRNA_names.npy**: Contains the names of 834 circRNAs.  
- **disease_names.npy**: Contains the names of 138 diseases.  
- **miRNA_names.npy**: Contains the names of 555 miRNAs.  
- **disease_disease.npy**: Includes the similarities among the diseases.
- **circRNA_disease.npy**: Includes the associations between the circRNAs and diseases.
- **circRNA_miRNA.npy**: Includes the associations between the circRNAs and miRNAs.
- **Supplementary Table ST1.xlsx**: Lists the top 30 candidate circRNAs for each disease.

---

## How to Run the Code  
1. **Data preprocessing**: Constructs the adjacency matrices, features, and other inputs for training the model.  
    
    ```bash
    dataloader.ipynb
    ```
    
2. **Train and test the model**.  
    
    ```bash
    MNCDA.ipynb
    ```

**Run this notebook**: simply run all the cells in these notebook.
