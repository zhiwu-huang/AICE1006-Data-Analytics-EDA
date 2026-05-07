*AICE1006 EDA Coursework Guideline*

*Updates on 30/04/2025: LaTex template & notes of "Mark Scheme"*

*Updates on 07/05/2025: PDF version of the CW template & Breakdown of "Mark Scheme"*

*Updates on 11/02/2026: new due date for 2025-26*

*Updates on 07/05/2026: Added Q&A in the end of this guide*



# AICE1006-Coursework2: EDA Project

Due date: **Friday 15th May 2026, 16:00**.  
[Handin](https://moodle.ecs.soton.ac.uk/mod/assign/view.php?id=14979)

Required files: **report.pdf + notebook code**

## Overview
In this coursework, each student will choose an Exploratory Data Analysis (EDA) problem to investigate. Students are expected to carry out a series of EDA experiments on their selected dataset, drawing on the knowledge acquired from Lectures 4 to 12. The outcomes and insights must be documented in the form of a written conference paper.


## Details

Each student will propose a project, ideally selecting a dataset, either a publicly available dataset or the dataset generated from Coursework1. Please refer to the links at the end of this document for additional inspiration. The project should showcase the student’s ability to apply their learned methods to address a real-world EDA problem—focusing on a descriptive or interpretative task as part of the individual coursework.

### Deliverable 

**A zip file of the final report and the notebook code** must be submitted to Moodle [Handin](https://moodle.ecs.soton.ac.uk/mod/assign/view.php?id=14979).  
  The report **must** follow the [LaTeX template](https://github.com/zhiwu-huang/AICE1006-Data-Analytics-EDA/blob/main/CW_template.zip) ([PDF](https://github.com/zhiwu-huang/AICE1006-Data-Analytics-EDA/blob/main/CW_template.pdf)). It should not exceed **8 pages**, excluding all references and appendices (if applicable).  

### Notes
* Students are encouraged to leverage the two "Cousework Q&A" sessions to receive feedback from the lecturer.

* Each student can book time to meet with the lecturer (ideally in the published office hours or the unused lecture slots) should they need additional help or guidance.

#### Learning Outcomes

* Solve real-word problems using learned EDA technqiues (topics illustrated in the Lecture on "[EDA Introduction](https://moodle.ecs.soton.ac.uk/pluginfile.php/9308/mod_label/intro/01_Introduction.pdf?time=1741614694442)")
* Demonstrate knowledge and understanding of:
	- Key concepts, tools and approaches for EDA on real-world data sets
	- Theoretical concepts and the motivations behind different EDA approaches

### Mark Scheme

The final coursework report and jupyter notebook code will be marked as a single piece of work using the following criteria (note that **the titles of Secs.1-7** are outlined in the [LaTeX template](https://github.com/zhiwu-huang/AICE1006-Data-Analytics-EDA/blob/main/CW_template.zip), and **a tentative breakdown** of the Mark scheme is available [here](https://github.com/zhiwu-huang/AICE1006-Data-Analytics-EDA/blob/main/CW_Mark_Scheme.pdf) for reference only) :

Criterion                    | Description                                                                                | Marks
-----------------------------|--------------------------------------------------------------------------------------------|-------
Introduction of dataset      | Introduce dataset information (Sec.1)                                                      | 10
Application of techniques    | Show ability to apply EDA techniques and analyse results obtained (Secs.2-6 + Code)        | 60
Conclusion/Reflection        | Reflect on what you have learned on the dataset and the techniques used (Sec.7)		  | 20
Reporting                    | Clear and professional reporting (Overall)                                                 | 10

Standard ECS late submission penalties apply. The [university guidance on writting report](https://library.soton.ac.uk/writinglabreports) would be helpful.

## Useful Links
The following list has some pointers to places where you might get some inspiration for data analytics/mining challenges (one example dataset for your reference: [Red Wine Quality](https://www.kaggle.com/datasets/uciml/red-wine-quality-cortez-et-al-2009)):

* https://www.kaggle.com - source of lots of different data mining competitions.
* http://www.drivendata.org - source of lots of different data mining competitions with an emphasis on saving the world.
* http://multimediaeval.org/datasets/ - a range of data and evaluation criteria for different types of data mining problems involving multimedia and multi-modal data.
* http://www.kdnuggets.com/competitions/past-competitions.html - list of past data mining competitions; data and evaluation criteria is likely to be available for many of these.
* http://webscope.sandbox.yahoo.com - publicly available research datasets from Yahoo!
* http://www.kdd.org/kdd-cup - KDD Cup is an annual data mining competition run by ACM SIG KDD; datasets, evaluation criteria, and info previous winners are available (note that the most recent competitions are actually hosted on kaggle.com).

**Note**: Preferred datasets should consist of tabular data, include a sufficient number of samples (e.g., at least 1,000), and have a reasonable number of columns/variables (10 or more, primarily numerical). Ideally, benchmark datasets, such as those available on [Kaggle](https://www.kaggle.com/datasets?topic=benchmarkDataset), are recommended.  

## Q&A

**Q**: Does the dataset we use need to be able to be loaded directly from the internet via a URL as I assume the notebook won't work if it doesn't have access to the data and that we won't be including the raw csv in our submission?

**A**: If the dataset is small (a few MB), you can submit it with the coursework; otherwise, use a public dataset URL or a OneDrive link where you store the data. The water quality dataset sounds like a good choice, as long as it meets the lecture requirements (e.g., 1000+ samples, 10+ columns, mostly numerical, and reasonably high quality, not overly noisy or poorly measured).

**Q**: The dataset I selected has 2 versions, one is the raw dataset and the other is a cleaned version of the dataset. Should I take the raw dataset and clean it myself or work with the cleaned version?

**A**: The former (cleaning it yourself) looks better if as long as the raw dataset  meets the lecture requirements (e.g., 1000+ samples, 10+ columns, mostly numerical, and reasonably high quality, not overly noisy or poorly measured).

**Q**: In terms of importing the dataset, I plan to use the mlcroissant python package to retrieve it from the web into the notebook. Is it ok to use this package? My worry is that if I download the csv file then when I submit the notebook, you will note have access to the database.

**A**:  Yes, that should be fine as long as the notebook runs properly on my end for reproduction.

**Q**: With the structure of the report being: abstract, intro, data processing, data plotting, feature engineering, PCA, clustering, conclusion, appendix.
Why is feature engineering a separate section after data plotting instead of part of the data processing section. Shouldn't engineered features be used when plotting and exploring the correlation of the data?

**A**: The key is to apply what we covered on feature engineering. Focus on what features you engineer and why. Most plotting can be on the original/raw features. Since PCA and clustering come after feature engineering, you can apply them to both the raw and engineered features for comparison. (Correlation fits more naturally with the PCA discussion, so you can include it there if helpful.)

**Q**: I was wondering if we are allowed to use seaborn for the data analytics coursework in addition to numpy ,sklearn ,matplotlib etc. 

**A**: As mentioned in class, I would prefer you to use Matplotlib and Plotly rather than Seaborn for plotting figures. 


**Q**: I wanted to ask if the EDA coursework submission needs to have the same section titles as is outlined in the Latex template?

**A**: Yes, you are normally expected to use the same section titles. Otherwise, please explain why different titles would make more sense for your report.


If you have any further problems/questions then [email](mailto:Zhiwu.Huang @soton.ac.uk) the lecturer.

## Credit

* The report template is originally from [CVPR 2025](https://cvpr.thecvf.com/Conferences/2025/AuthorGuidelines).

