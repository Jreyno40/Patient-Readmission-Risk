# ReadmissionRisk
This project deals with a dataset of patients from many hospitals that were readmitted to hospitals. Hospital readmission is a huge problem, and thus preventing and predicting potential readmission is a problem of high value.
<hr>
I've committed two notebooks: 
<ol>
<li>ConvertDiagnosisColumns.ipynb</li>
<li>ReadmissionRisk.ipynb</li>
</ol>
<br>
The full dataset is also included:
<ul>
<li>diabetic_data.csv</li>
<li>IDs_mapping.csv</li>
<li>diagnoses_converted.csv</li>
</ul>
<br>
<hr>
The first notebook (ConvertDiagnosisColumns) utilizes the paper (http://www.hindawi.com/journals/bmri/2014/781670/) linked on UCI page (https://archive.ics.uci.edu/ml/datasets/Diabetes+130-US+hospitals+for+years+1999-2008)
to convert diag_1, diag_2, and diag_3 from ID numbers to string descriptions. It operates on diabetic_data.csv (from the original .zip provided on UCI), then outputs the result to diagnoses_converted.csv. You don't have to run the first notebook. The main notebook (ReadmissionRisk.ipynb) operates directly on the already converted dataset, diagnoses_converted.csv.
