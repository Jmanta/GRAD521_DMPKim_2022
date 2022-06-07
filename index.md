# Data Management Plan

# Data description
The Korea National Health and Nutrition Examination Survey (KNHANES) provide a publicly available health dataset. The dataset contains various health data, including socioeconomic status, medical examinations, and nutrition. My research interest is defining the relationship between physical activity behavior and the health outcomes of Korean adults. Specifically, the recent research is focused on investigating the relationship between sedentary behavior and metabolic syndrome.
The KNHANES raw data to be used in this study are general health survey and physical activity examination data from 2014 and 2015, which are four SAS files (sas7bdat). The raw data is categorized into three types: Demographic survey, laboratory examination, and physical activity examination.  Demographic survey data includes survey modeling, socioeconomic, and health behavior information, including sex, age, income, occupation, education, smoking, and alcohol consumption. All information is categorically coded in the spreadsheet. The laboratory examination data is collected from the health examination tests. The laboratory examination data contains the following information: anthropometric measures (height, weight, and waist circumferences), blood sample tests (triglyceride, HDL-Cholesterol, Fasting glucose), and blood pressure. All information is coded as a numerical variable in the spreadsheet. The physical activity data, measured by an accelerometer, contains six variables: day, data sequence, hour, minute, count, and step. Each participant had 10,080 data points (7 days x 24 hours x 60 minutes). All information is coded in the spreadsheet.

# Roles and responsibilities
The physical Activity Epidemiology and Assessment Laboratory manager will be the principal investigator (PI) in this research, and Jaemyung Kim will serve as the Co-investigator (CI) role. The PI is responsible for the entire research process, and CI will support the PI during the research.
* Data management plan development: PI & CI
* Collecting raw data: CI
* Data processing: PI & CI
* Metadata development: PI & CI
* Data analysis: PI & CI
* Access control: PI
* Archival and Preservation: PI & CI

In the absence of CI, PI and another lab member will serve the CI role. In addition, data archiving and preservation are common roles for the PAEA lab members.

# Data standards and metadata
Data standards for this research will follow the Data Documentation Initiative’s version 2.5 (DDI 2.5) metadata standards. The information which will add to the metadata will base on the DDI 2.5 Codebook, https://ddialliance.org/Specification/DDI-codebook/2.5/XMLSchema/codebook.xsd. CI will use R software to write metadata in XML format.

The metadata will have following information. Since the Korea Disease Control and Prevention Agency (KDCA) published the KNHANES analysis manual which describes every variable information, all metadata except for information on initial data is regarding processed data.
* Research abstract 
  * Research purpose 
  * information on initial data (KNHANES VI-2, 3) 
  * List of major variables
    * type (numeric, character, and date)
* Data collection methodology
  * Downloading method of the KNHANES raw data from KDCA
* Software information
  * Version of R
  * List of R packages used in the research
* File information
  * Format of the data files: rawdata (.sas7bdat & .csv) research data (.csv), and R script (.R)
  * Name of the files
* Variable informations included in the research
  * Total count of variables
  * Variable Codebook: variable names, definition, values, and value description.
* Categoty-level statistics
  * Number of observations
  * Demographic charateristics of population (age, sex, and Metabolic Syndrome prevalence)

# Storage and security
The raw KNHANES data will be stored on Lab’s external hard disk drive (HDD) and CI’s USB drive. The additional protection strategy for the raw data is unnecessary because KNHANES data is published after processing de-identification. The data used in this research is unrestricted data according to the Oregons State University's definition of sensitive and confidential data. PI and CI will participate in the data analysis. The dataset for the analysis, including spreadsheet and R script, will be stored on PI and CI’s USB drive and Lab’s external HDD. 

The processed data will be saved using spreadsheet format (.csv). The name of the data will follow the "KN6_data_yymmdd.csv" format. In the case of R script data, the R script will be saved in R script format (.R), and the name of the file will follow the "KN6_analysis_yymmdd.R" format. The date part of both file names will be used for version control.

# Access and data Sharing
KDCA permits anyone who has research purposes of accessing KNHANES data without restriction. They recommend reporting any creation of research products using KNHAENS data to the KNHANES Webpage. The processed KNHANES data will not be shared with the public but will be available by individual requests. 
The metadata and R scripts, including accelerometer data processing and general analysis R codes, will be published in the research article’s appendix format. Data, including processed KNHANES data and R scripts, will be shared at the moment of publication through GitHub simultaneously. Before the publication, the use and distribution of the R code require permission from the content creator. Since the R code is personal creative work, the R scripts data will have an Attribution-Noncommercial 4.0 (CC BY-NC 4.0) license. Any commercial and profit-driven activity will be restricted using shared data.

# Archiving and preservation
The secondary data, including participant data, metadata, and R script, will store in the Physical Activity Epidemiology and Assessment lab’s external data storage. Among all types of data, addition, metadata, and R script will be reposited on the CI’s GitHub. The repository address will be published in the form of a journal article. Those data will be kept for at least ten years. After this time, the data can be subject to elimination; however, the elimination of the data will be determined by the frequency of reuse, access, and citation. The frequency of access and citation will be captured via GitHub traffic and scholarly repositories such as Google Scholar, PubMed, and Science Direct.
