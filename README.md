
The YaleNeuroConnect dataset is available in two online locations: 

The dataset is available through two repositories: the open-source data archive OpenNeuro website (doi:10.18112/openneuro.ds007286.v1.0.3) and the NIMH Data Archive website (https://nda.nih.gov/edit_collection.html?id=3276). In addition, the processing pipeline used to generate the functional connectivity matrices and mean time courses are included on the YaleNeuroConnect GitHub page (https://github.com/YaleMRRC/YaleNeuroConnect). 

The data can be freely accessed via the OpenNeuro website. 

Access through the NIMH website requires an application, as outlined in the data usage section below, as well as on the YaleNeuroConnect GitHub page. 

1.	OpenNeuro website
-	Structural MRI (under each participant’s id -> ses-01 -> anat)
-	Functional MRI (under each participant’s id -> ses-01 -> func)
-	Functional connectomes atlas Shen268 
(under derivatives -> MC_Shen 268 -> each participant’s id -> ses-01)
-	Functional connectomes atlas Shen368 
(under derivatives -> MC_Shen 368 -> each participant’s id -> ses-01)
-	Mean ROI time courses atlas Shen268 
(under derivatives -> roimean_Shen 268 -> each participant’s id -> ses-01)
-	Mean ROI time courses atlas Shen368 
(under derivatives -> roimean_Shen 368 -> each participant’s id -> ses-01)
-	MATLAB code for running that task fMRI runs (under derivatives -> task_code.zip)
-	Behavioral measures* (under phenotype)
-	Clinical measures* (under phenotype)
-	Demographic measures* (under phenotype)
-	Diagnostic categories* (under phenotype)
-	Timing of the movie clips* (under derivatives) 

*: the accompanying json files describe the files’ columns/variables. 

2.	NIMH website (https://nda.nih.gov/edit_collection.html?id=3276): 
-	Structural MRI 
-	Functional MRI 
-	Behavioral measures
-	Clinical measures

Data Usage: 
  Usage Notes:

Raw neuroimaging data, behavioral and clinical scores, functional connectivity matrices, mean functional time courses, diagnostic categories, and quality assurance metrics are freely available for download from the OpenNeuro website. 

The raw neuroimaging data as well as the behavioral and clinical scores are available for download from the NIMH NDA website following an application process. 
To access the NDA system create an account at https://nda.nih.gov/. To learn more about the requirements for requesting access, visit https://nda.nih.gov/nda/access-data-info and https://nda.nih.gov/nda/tutorials/electronic-data-access-request. Importantly, the lead recipient’s access to the dataset must have a principal investigator (PI) role linked to their eRA Commons account, and the NDA account must be affiliated with an NIH-recognized research institution. Access to the dataset is typically received within 10 business days.
Once access is permitted, download the data following these instructions. Please install the NDA Download Manager as described at https://nda.nih.gov/nda/nda-tools.

1.1. Visit the NDA Query Tool.
 
  1.2. Find the data in the NDA Query Tool.
 
     1.2.1 Visit Data from Labs.
 
     1.2.2 Enter "id:3276" in the text search field.
 
  1.3. Select your Collection, add the data to your "Workspace", then your "Filter Cart."
 
  1.4. Once your filter cart is done updating, click "Create Data Package/ Add Data to Study."
 
  1.5. You will then be brought to the Data Packaging page. Click the orange "Create Data Package" button and follow the prompts to create your data package.
 
  1.6. Wait for the package to be created. You can check the status of your package via your Data Packages dashboard.
  Please note: This may take a few hours. 
 
  1.7. Once your package is ready to be downloaded, open the NDA Download Manager Tool and download your data.

Please note that the data was formatted to comply with NDA standards. Subject IDs may appear in multiple rows, often due to NDA formatting requirements. Only the final occurrence should be considered. 

________________________________________________________________________________________________
Data Use Agreement: 

If I am granted access to the database:
1.	I will not attempt to identify any individual referenced in YaleNeuroConnect restricted data.
2.	I will exercise all reasonable and prudent care to avoid disclosure of the identity of any individual referenced in YaleNeuroConnect restricted data in any publication or other communication.
3.	I will not share access to YaleNeuroConnect restricted data with anyone else.
4.	I will exercise all reasonable and prudent care to maintain the physical and electronic security of YaleNeuroConnect restricted data.
5.	If I find information within YaleNeuroConnect restricted data that I believe might permit identification of any individual or institution, I will report the location of this information promptly by email to todd.constable@yale.edu, citing the location of the specific information in question.
6.	I have requested access to YaleNeuroConnect restricted data for the sole purpose of lawful use in scientific research, and I will use my privilege of access, if it is granted, for this purpose and no other.
7.	This agreement may be terminated by either party at any time, but my obligations with respect to YaleNeuroConnect data shall continue after termination. 
8.	I will cite the YaleNeuroConnect manuscript (manuscript information to be added once the manuscript is published) if I publish a study using the dataset. 


Adapted from PhysioNet Credentialed Health Data Use Agreement 1.5.0. (https://physionet.org/content/mimiciii/view-dua/1.4/) 











