---
title: "Importing Alternative Sources in NVivo 14/15 for Mac"
layout: "home"
description: ""
permalink: "/"  #! Remove this if not the homepage
---

# Importing Alternative Sources in NVivo 14/15 for Mac

NVivo can handle many types of files, such as text, audio, videos, images, etc. You would import these from the Data menu, by choosing the appropriate option. However, this tutorial will show you a common source of data that you might want to code in NVivo that is a bit more complicated to import.

Survey Data
-----------

A common data type that you might want to use NVivo to analyze is survey data. NVivo can import survey data in directly if you have your survey data stored in a spreadsheet, where each row is a survey respondent’s answers and each column is a question.

Note: This activity assumes you are familiar with case classifications and cases in NVivo. If case classifications and cases in NVivo is new to you, you can learn more in our [Introduction to NVivo 14/15 tutorial](https://mdl.library.utoronto.ca/technology/tutorials/introduction-nvivo-14-mac)!

1\. To start, let's **download a small sample of survey data** called the[Millennial Sentiment Interview Transcript Dataset](https://www.kaggle.com/parmarmanojkumar/msitd?select=Interview_Database.xlsx). This data set is hosted on Kaggle, which is an public data platform. To download this data you’ll first have to **register for a free account** (or sign in if you already have one). **Click Register** at the top right of the website.

<img src='{{ '/assets/images/NVIVO14_MAC_Survey%20Data_1a.png' | relative_url }}' alt='Kaggle page with Millennial Sentiment Interview Transcript Dataset. Register button in the top right highlighted.' title='' width='794' height='510' />  
 

 

After you’ve signed in, **click Download** and save it somewhere you can find it, such as the Desktop.  
  
<img src='{{ '/assets/images/NVIVO14_MAC_Survey%20Data_1b.png' | relative_url }}' alt='Kaggle page with Millennial Sentiment Interview Transcript Dataset. Download button highlighted.' title='' width='794' height='476' />

2\. Go to NVivo. From the left menu, under Data, **click on the Files folder**. Then under the Import tab, **select Dataset**.

<img src='{{ '/assets/images/NVIVO14_MAC_Survey%20Data_2.png' | relative_url }}' alt='The Data menu is highlighted, along with Files, which is selected. Under the Import tab, Dataset is selected and highlighted. ' title='' width='794' height='157' />

3\. Browse to the folder where the **Millennial Sentiment Interview Transcript Dataset** (file Interview\_Database.xlsx) was saved. **Select the file, and then click on Open.**

<img src='{{ '/assets/images/NVIVO14_MAC_Survey%20Data_3.png' | relative_url }}' alt='Import browser with the file "Interview_Database.xlsx" selected and the "Open" button highlighted.  ' title='' width='729' height='465' />

4\. NVivo’s Dataset Import Wizard will open up to help you import your data. First as there are two sheets in the Excel file, it is asking which one to use. The default “Data” sheet is fine. It will also present you with a preview of the data. **Click on Next.**

<img src='{{ '/assets/images/NVIVO14_MAC_Survey%20Data_4.png' | relative_url }}' alt='Import Dataset Assistant step 2 with Next highlighted. ' title='' width='772' height='567' />

5\. Next it checks the data format. Our first row is our column headers, so we can keep the default. We don’t have any dates in our survey, so again we can keep the default, but if you are working with dates, then take a look at this option. **Click on Next.** 
<img src='{{ '/assets/images/NVIVO14_MAC_Survey%20Data_5.png' | relative_url }}' alt='Import Dataset Assistant step 3 with Next highlighted. ' title='' width='771' height='568' />

6\. This screen presents you with how NVivo has interpreted the different columns in the dataset – that some have codable content, for example. **Keep the defaults on the next screen and click on Next.**

<img src='{{ '/assets/images/NVIVO14_MAC_Survey%20Data_6.png' | relative_url }}' alt='Import Dataset Assistant step 4 with Next highlighted. ' title='' width='772' height='570' />

7\. Then **click Import** to complete importing in our data. You will see a progress screen.

<img src='{{ '/assets/images/NVIVO14_MAC_Survey%20Data_7.png' | relative_url }}' alt='Import Dataset Assistant step 5 with Import highlighted. ' title='' width='773' height='572' />

8\. NVivo will open up the data when finished, as a spreadsheet display.

<img src='{{ '/assets/images/NVIVO14_MAC_Survey%20Data_8.png' | relative_url }}' alt='The imported "Interview_Database" file as a spreadsheet opened in NVivo.' title='' width='794' height='447' />

9\. Next we can create codes for each open\-ended question automatically. Then it’ll group all the responses to a particular question together in a code. To do so, **hold down the Control key and click on the newly imported dataset** in the list of files. **Select Auto Code and then Dataset…**

<img src='{{ '/assets/images/NVIVO14_MAC_Survey%20Data_9.png' | relative_url }}' alt='The files folder highlighted and opened with the context menu for "Interview_Database" opened. The Auto Code option highlighted a its menu open with Dataset... highlighted. ' title='' width='756' height='500' />

10\. Using the Auto Code Dataset Assistant, **select Code at codes for selected columns**. Then **click on Next.**

<img src='{{ '/assets/images/NVIVO14_MAC_Survey%20Data_10.png' | relative_url }}' alt='Auto Code Dataset Assistant step 1 with the Code at codes for selected columns option selected and highlighted, and with Next highlighted.' title='' width='772' height='570' />

11\. NVivo auto detects the columns that are open\-ended and lists them in Selected Columns. **We can keep the defaults and select Next.**

<img src='{{ '/assets/images/NVIVO14_MAC_Survey%20Data_11.png' | relative_url }}' alt='Auto Code Dataset Assistant step 2 with Next highlighted.' title='' width='773' height='571' />

12\. It asks if we want to put these new codes under a parent code or create a new parent code based on the name of the dataset. **We can keep the defaults and select Auto Code.**

<img src='{{ '/assets/images/NVIVO14_MAC_Survey%20Data_12.png' | relative_url }}' alt='Auto Code Dataset Assistant step 3 with the Auto Code button highlighted.' title='' width='771' height='571' />

13\. Once completed, from the left menu, you can **click on Codes and expand the Interview\_Database code** to see all the auto generated codes. **Double click on one** to see all the answers to that particular question in the survey.

<img src='{{ '/assets/images/NVIVO14_MAC_Survey%20Data_13.png' | relative_url }}' alt='The Codes folder opened with "Interview_Database" expanded and one of the Codes opened.' title='' width='2760' height='1378' />

14\. We can also use NVivo to auto create cases, one case for each survey respondent. To do so, from the left menu, **go back to the Files folder**. **Hold down the Control key and click on the newly imported dataset** once again. **Select Auto Code and then Dataset…**

<img src='{{ '/assets/images/NVIVO14_MAC_Survey%20Data_14.png' | relative_url }}' alt='The files folder highlighted and opened with the context menu for "Interview_Database" opened. The Auto Code option highlighted a its menu open with Dataset... highlighted. ' title='' width='692' height='498' />

15\. This time, **select Code to cases for each value in a column** and then **select Next.**

<img src='{{ '/assets/images/NVIVO14_MAC_Survey%20Data_15.png' | relative_url }}' alt='Auto Code Dataset Assistant step 1 with the Code to cases for each value in a column option selected and highlighted, and with Next highlighted.' title='' width='773' height='570' />

16\. For Choose the column that contains the case names, **select Sr No.** to select the ID numbers we can use to identify survey respondents. Then **select Next.**

<img src='{{ '/assets/images/NVIVO14_MAC_Survey%20Data_16.png' | relative_url }}' alt='Auto Code Dataset Assistant step 2 with Sr No. selected from the drop-down menu and Next highlighted.' title='' width='772' height='568' />

17\. Next it will suggest coding all the open\-ended responses by these newly created cases. **We can keep the defaults, so select Next.**

<img src='{{ '/assets/images/NVIVO14_MAC_Survey%20Data_17.png' | relative_url }}' alt='Auto Code Dataset Assistant step 3 with Next highlighted.' title='' width='772' height='570' />

18\. Select **Classify cases from classifying columns.** The defaults below this will create a new case classification using the closed\-ended variables in your dataset as attributes, such as Industry, etc. Then **select Auto Code.**

<img src='{{ '/assets/images/NVIVO14_MAC_Survey%20Data_18.png' | relative_url }}' alt='Auto Code Dataset Assistant step 4 with Classify cases from classifying columns highlighted and selected, and the Auto Code button highlighted.' title='' width='774' height='572' />

19\. From the left menu, **go to Cases**, and **expand Interview\_Database** to see a list of all the cases created (one for each survey respondent). **Double click on one of them** to see all the responses to the survey that respondent provided.

<img src='{{ '/assets/images/NVIVO14_MAC_Survey%20Data_19.png' | relative_url }}' alt='The Cases folder opened with "Interview_Database" expanded and one of the Codes opened.' title='' width='794' height='512' />

20\. From the left menu, go to **Case Classifications,** and **double click on Interview\_Database**. Select **Classification Sheet** just above the data to see a spreadsheet of the attributes for each case.

<img src='{{ '/assets/images/NVIVO14_MAC_Survey%20Data_20.png' | relative_url }}' alt='The Case Classification folder opened with "Interview_Database" open and the Classification Sheet tab selected. .' title='' width='2548' height='1068' />

20\. To summarize, when importing the survey dataset, NVivo will help us create a case for the survey respondent. For each closed\-ended question that it detects, it will capture that information about the survey respondent as case attributes. It will import each open\-ended question as spreadsheet content that can be coded, and automatically code each question’s response with a new code for that question. You can now continue to code the open\-ended question responses to further analyze the survey data, or run queries to gain insight into the data.

Resources to Learn More
-----------------------

Visit our[Introduction to NVivo 14/15 for Mac](https://mdl.library.utoronto.ca/technology/tutorials/introduction-nvivo-1415-mac)page for more information and tutorials on NVivo 14/15!

Check out [this NVivo help page](https://help-nv.qsrinternational.com/15/mac/Content/files/files.htm) to explore all the file types you can import into an NVivo project.

Technique: [Qualitative Data Analysis](/technique/qualitative-data-analysis) \| Tools: [NVivo](/tools/nvivo)**Date Created:** 2023\-11\-20**Updated:** 2026\-01\-20
