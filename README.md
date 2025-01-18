# Bone Marrow Transplantation Analysis

## Project Overview
This project utilizes a dataset containing bone marrow transplantation characteristics for pediatric patients from UCI’s Machine Learning Repository. The goal is to build a machine learning pipeline that includes all preprocessing and data cleaning steps, and then select the best classifier to predict patient survival.

## Steps to Create the Machine Learning Model
1. **Importing the Necessary Libraries**: Load essential Python libraries for data manipulation, preprocessing, and model building.
2. **Loading and Exploring the Dataset**: Load the dataset and perform exploratory data analysis to understand the data structure and identify any data quality issues.
3. **Model Building**: Develop and train machine learning models to predict patient survival.
4. **Communicating Results**: Evaluate model performance and communicate the results effectively.

## Dataset Information
The dataset describes pediatric patients with several hematologic diseases, including both malignant and nonmalignant disorders. All patients underwent unmanipulated allogeneic unrelated donor hematopoietic stem cell transplantation. The study aims to identify the most important factors influencing the success or failure of the transplantation procedure.

### Attributes
- **Recipientgender**: Male (1), Female (0)
- **Stemcellsource**: Peripheral blood (1), Bone marrow (0)
- **Donorage**: Age of the donor at the time of hematopoietic stem cells apheresis
- **Donorage35**: Donor age <35 (0), Donor age >=35 (1)
- **IIIV**: Development of acute graft versus host disease stage II, III, or IV (Yes - 1, No - 0)
- **Gendermatch**: Compatibility of the donor and recipient according to their gender (Female to Male - 1, Other - 0)
- **DonorABO**: ABO blood group of the donor (0, 1, A, B=-1, AB=2)
- **RecipientABO**: ABO blood group of the recipient (0, 1, A, B=-1, AB=2)
- **RecipientRh**: Presence of the Rh factor on recipient’s red blood cells ('+' - 1, '-' - 0)
- **ABOmatch**: Compatibility of the donor and recipient according to ABO blood group (matched - 1, mismatched - 0)
- **CMVstatus**: Serological compatibility of the donor and recipient according to cytomegalovirus infection prior to transplantation
- **RecipientCMV**: Presence of cytomegalovirus infection in the recipient prior to transplantation (presence - 1, absence - 0)
- **Disease**: Type of disease (ALL, AML, chronic, nonmalignant, lymphoma)
- **Riskgroup**: High risk (1), Low risk (0)
- **Txpostrelapse**: Second bone marrow transplantation after relapse (No - 0, Yes - 1)
- **Diseasegroup**: Type of disease (malignant - 1, nonmalignant - 0)
- **HLAmatch**: Compatibility of antigens of the main histocompatibility complex according to international criteria
- **HLAmismatch**: HLA matched (0), HLA mismatched (1)
- **Antigen**: Number of antigen differences between donor and recipient
- **Allel**: Number of allele differences between donor and recipient
- **HLAgrI**: Type of HLA difference between donor and recipient
- **Recipientage**: Age of the recipient at the time of transplantation
- **Recipientage10**: Recipient age <10 (0), Recipient age >=10 (1)
- **Recipientageint**: Recipient age intervals
- **Relapse**: Reoccurrence of the disease (No - 0, Yes - 1)
- **aGvHDIIIIV**: Development of acute graft versus host disease stage III or IV (Yes - 0, No - 1)
- **extcGvHD**: Development of extensive chronic graft versus host disease (Yes - 0, No - 1)
- **CD34kgx10d6**: CD34+ cell dose per kg of recipient body weight (10^6/kg)
- **CD3dCD34**: CD3+ cell to CD34+ cell ratio
- **CD3dkgx10d8**: CD3+ cell dose per kg of recipient body weight (10^8/kg)
- **Rbodymass**: Body mass of the recipient at the time of transplantation
- **ANCrecovery**: Time to neutrophils recovery
- **PLTrecovery**: Time to platelet recovery
- **time_to_aGvHD_III_IV**: Time to development of acute graft versus host disease stage III or IV
- **survival_time**: Survival time
- **survival_status**: Survival status

## Usage
1. Clone the repository.
2. Install the required dependencies.
3. Run the Jupyter notebook `bone_marrow.ipynb` to execute the analysis.



## License
This project is licensed under the MIT License.# bone_marrow
In this project, we will be using a dataset containing bone marrow transplantation characteristics for pediatric patients from UCI’s Machine Learning Repository.  We will this dataset to build a pipeline, containing all preprocessing and data cleaning steps, and then selecting the best classifier to predict patient survival.
