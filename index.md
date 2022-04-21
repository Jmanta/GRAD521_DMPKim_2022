#Data Management Plan

# Data description
The Korea National Health and Nutrition Examination Survey (KNHANES) provide a publicly available health dataset. The dataset contains various health data, including socioeconomic status, medical examinations, and nutrition. My research interest is defining the relationship between physical activity behavior and the health outcomes of Korean adults. Specifically, the recent research is focused on investigating the relationship between sedentary behavior and metabolic syndrome.

# Roles and responsibilities
My advisor will be the project investigator (PI) in my research, and I will be the Co-investigator (CI). As a CI of the research, I will be responsible for documenting and implementing Data Management Plan. Since the KNHNAES data is written in Korean, CI will work on downloading KNHANES raw dataset, organizing data, and generating metadata. The KNHANES raw data to be used in this study are general health survey and physical activity examination data from 2014 and 2015, which are four SAS files (sas7bdat). The raw data will be stored on Lab’s external hard disk drive (HDD) and CI’s USB drive.

# Data standards and metadata
The data is categorized into three types: Demographic survey, laboratory examination, and physical activity examination.  Demographic survey data includes survey modeling, socioeconomic, and health behavior information, including sex, age, income, occupation, education, smoking, and alcohol consumption. All information is categorically coded in the spreadsheet. The laboratory examination data is collected from the health examination tests. The laboratory examination data contains the following information: anthropometric measures (height, weight, and waist circumferences), blood samples (triglyceride, HDL-Cholesterol, Fasting glucose), and blood pressure. All information is coded as a numerical variable in the spreadsheet. The physical activity data is measured by an accelerometer. Accelerometer saved participants’ physical activity using counts minute by minute; each participant had 10,080 data points (7 days x 24 hours x 60 minutes). The accelerometer dataset had six variables: day, data sequence, hour, minute, count, and step. All information is saved in the spreadsheet.

# Storge and security
The raw KNHANES data will be stored on Lab’s external hard disk drive (HDD) and CI’s USB drive. The additional protection strategy for the raw data is unnecessary because KNHANES data is published after processing de-identification. Both PI and CI will participate in the data analysis process. The dataset for the analysis including spreadsheet and R script will be stored on PI and CI’s USB drive and Lab’s external HDD.

# Access and data Sharing
The right to distribute and use the generated data is on the PI and CI. Since the research is not funded from external sources, there is no restriction on using KNHANES raw data; however, processed data will restrict re-use and distribution. If the researcher wants to use the processed KNHANES data outside of the lab, the researcher needs permission from the lab coordinator, PI, in this case. Futhermore, R codes are the original contents of each researcher, PI, and CI. Therefore, the use and distribution of R code need permission from the content creator. 

# Archiving and preservation
Our research team will have three copies of the processed data for the analysis: one for the PI, one for the CI, and one for the backup purpose.
