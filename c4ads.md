## Nuclear Fuel Cycle Project <br>
<br>
Between January and February 2020, I had an opportunity to partake in a remote internship for The Center for Advanced Studies (C4ADS) with a group of three other Data Science students from Lambda School.  Due to privacy allowances and NDA requirements, I cannot dive into specifics of the project, but here is a broad strokes outline, approved for release.
Based in Washington, D.C.  C4ADS is a nonprofit organization dedicated to providing data-driven analysis and evidence-based reporting on global conflict and transnational security issues.
A build-on project, the Nuclear Fuel Cycle projects’ mission is to find companies that have the potential to be involved in the production of dual use precision materials that can be used in the nuclear fuel cycle. By dual use we mean the manufacturing of products that although might be listed as civilian use only, that could also be used for military purposes. Our job was to pore through these massive datasets to find any companies that are currently manufacturing, or have shown the capability to manufacture, precision engineered products (like centrifuges, for example) that could be utilized in the nuclear fuel cycle.
In the two month internship, we were able adopt new tools and frameworks quickly, build the infrastructure for the next batch of interns, and to achieve the goals as defined by the stakeholder.
The Challenge
We encountered three main problems during the Labs project. 
1.   	Steep Learning Curve:
·       175 GB Data - The dataset is massive
·       AWS - Had to get acclimated to a new platform.  Prior to this, we worked mainly off of Jupyter and Colab notebooks.
·       Apache Spark – Spark was an entirely new framework for us.  Due to the sheer size of the dataset, a cluster-computing framework was the only feasible solution 
·       It’s in Russian – Lastly, the dataset was in Russian. 
2.   	Redundant Features:
·       The dataset that we were working with also had a lot of features (173 originally)
3.   	Modeling Troubles (Out of Memory errors):
·       We would also run into problems with modeling via Spark.  We were able to successfully execute a Logistic Regression model, but had issues with other models.
Solutions & Lessons Learned:
1.   	Rapid upskilling:
·       Created a quick Spark Tutorial for next batch of interns
·       Utilized available resources: Spark – The Definitive Guide & a Udemy course on Spark
2.   	Assisted colleagues with exploring the listed features, and identifying redundant and duplicate columns
3.   	We were able to successfully run a Logistic Regression model using Spark, resulting in new results for C4ADS. 
We wanted to run more complex models like Balanced Random Forest, XGBoost, and RESVM.  We tried a number of different solutions, but to no avail due to memory errors.  Ultimately, during the last week of the internship, we received validation from one of our Data Science instructors that Spark is not the best framework to use for modeling.  It’s great for data exploration, cleaning, and wrangling, but not for modeling.
Internship Outcome:
·       Created the "infrastructure" for the next build-on internship group
·       Reduced the Features (from 173 to 105); removed duplicates, useless, and redundant data
·       Found 319 new potential hits based on a new feature.
Direct Contributions:
·       Led interactions between stakeholder and team
·       Led official presentations on behalf of group’s progress to class and Program Manager
·       Led initiative in Documentation for future internship groups
·       Created Spark tutorial Colab notebook
·       Assisted with Data Cleaning
·       Assisted with Data Modeling
