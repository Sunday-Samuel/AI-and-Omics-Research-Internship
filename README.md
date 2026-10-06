#  AI & Omics Research Internship 2025

##  Module I – Class Ib

***Intro to R Programming & Data Preparation***

###  Overview

This session introduced **basic R programming**, data handling, and factor conversion techniques.

###  Key Learning Outcomes

*  Set the working directory for project organisation.
*  Loaded the dataset **`patient_info.csv`**.
*  Checked data structure and data types.
*  Converted `gender` and `diagnosis` into factors (categorical variables).
*  Created a **binary variable** `smoker` (1 = Yes, 0 = No).
*  Saved the cleaned dataset.
*  Stored the work in **`class_Ib.R`**.

---

##  Module I – Class Ic

***Conditional Statements & Automated Data Type Conversion***

###  Overview

This session built upon **Class Ib**, adding conditional logic and automated factor conversion.

###  Key Learning Outcomes

*  Used `if` statements to check **cholesterol levels**.
*  Applied `if...else` statements for **blood pressure status**.
*  Automated categorical column detection and conversion in **`patient_info.csv`** and **`metadata.csv`**.
*  Converted **Yes/No** binary factors (e.g., `smoker`) to numeric codes.
*  Compared **original** vs **modified** dataset structures.
*  Saved the workspace as **`clean_Ic.RData`**.

---

##  Module I – Class II

***Differential Gene Expression (DGE) Analysis with R***

###  Overview

This session introduced **real-world data handling** using **gene expression datasets**.  
The focus was on automating classification of genes as **Upregulated**, **Downregulated**, or **Not Significant**.

###  Key Learning Outcomes

*  Processed multiple files (**`DEGs_Data_1.csv`**, **`DEGs_Data_2.csv`**).
*  Defined a **custom R function** `classify_gene()` to classify genes:
  - `Upregulated` if `logFC > 1` & `padj < 0.05`  
  - `Downregulated` if `logFC < -1` & `padj < 0.05`  
  - `Not_Significant` otherwise
*  Handled missing values (`padj` replaced with 1 if NA).
*  Stored results in an R list and exported **processed CSV files**.
*  Generated summary counts for **Upregulated**, **Downregulated**, and **Not Significant** genes.
*  Stored the work in **`class_II.R`**.
