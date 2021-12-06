# psy260-data-cleaning

Data cleaning code for the PSY260 module at the University of Sunderland.

To clean your data, please complete the following:

1. Navigate to [RStudio Cloud](https://login.rstudio.cloud/) and login with your account. If you don't have an account, make one and then login.
2. On the top right, click New Project and New Project From Git Repository.
3. Paste in the following URL: https://github.com/gpwilliams/psy260-data-cleaning

You have now copied the code used to clean your data to your account.

Next, you need to upload your data to RStudio Cloud. 

1. Navigate to [https://pavlovia.org/](https://pavlovia.org/) and login with your student account.
2. Navigate to your Experiment from the Dashboard. 
3. In the settings heading click Download results.

You have now downloaded your data from Pavlovia. Next, you need to upload your Pavlovia data to RStudio Cloud.

1. In RStudio Cloud click Upload (bottom right menu) and change the target directory by clicking Browse... and choosing 01_pavlovia_data as your folder. Click Choose.
2. Browse to your computer for your data. This should be in your download folder.
3. Select the folder of files (or single file) you just downloaded from Pavlovia.
4. Select OK to upload the files to the 01_pavlovia_data folder.

You now have your Pavlovia data uploaded. Next, you need to upload your Qualtrics data to RStudio Cloud.

1. Navigate to [https://sunduni.eu.qualtrics.com](https://sunduni.eu.qualtrics.com) and login with your student account.
2. Click on your project where people begin the experiment (e.g. PSY260_Experiment_Start).
3. Click on the Data& Analysis tab.
4. Click Export and Import and then Export Data...
5. Choose CSV and keep the settings as default.
6. Click Download.
7. Rename your data file to exp_start.csv.

You have now downloaded your Qualtrics data to your computer and prepared it for upload. You must now upload this to RStudio Cloud.

1. In RStudio Cloud click Upload (bottom right menu) and change the target directory by clicking Browse... and choosing 02_qualtrics_data as your folder. Click Choose.
2. Browse to your computer for your data. This should be in your download folder.
3. Select the file you just downloaded and renamed from Qualtrics.
4. Select OK to upload the files to the 02_qualtrics_data folder.

Finally, in RStudio Cloud please open the file labelled script.Rmd and press the button at the top labelled Run. Choose Run All.

If you followed these steps correctly you should now have your data stored in long format (for analysis in R) and wide format (for analysis in SPSS, JASP, or Jamovi) in the folder labelled 03_final_data. Click on this folder and tick the boxes for the file(s) you'd like to download. Click More and then Export Files. Finally, click Download. Your files are now available in your Downloads folder for analysis.

If you have any difficulties, please contact your workshop tutor.
