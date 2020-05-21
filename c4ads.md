## Nuclear Fuel Cycle Project <br>
<br>
Between January and February 2020, I had an opportunity to partake in a remote internship for The Center for Advanced Studies (C4ADS) with a group of three other Data Science students from Lambda School.  Due to privacy allowances and NDA requirements, I cannot dive into specifics of the project, but here is a broad strokes outline, approved for release.<br>
<br>
Based in Washington, D.C.  C4ADS is a nonprofit organization dedicated to providing data-driven analysis and evidence-based reporting on global conflict and transnational security issues.<br>
<br>
A build-on project, the Nuclear Fuel Cycle projects’ mission is to find companies that have the potential to be involved in the production of dual use precision materials that can be used in the nuclear fuel cycle. By dual use we mean the manufacturing of products that although might be listed as civilian use only, that could also be used for military purposes. Our job was to pore through these massive datasets to find any companies that are currently manufacturing, or have shown the capability to manufacture, precision engineered products (like centrifuges, for example) that could be utilized in the nuclear fuel cycle.<br>
<br>
In the two month internship, we were able adopt new tools and frameworks quickly, build the infrastructure for the next batch of interns, and to achieve the goals as defined by the stakeholder.<br>

## The Challenge <br>
<br>
We encountered three main problems during the Labs project. <br>
1.   	Steep Learning Curve:<br>
- 175 GB Data - The dataset is massive<br>
- AWS - Had to get acclimated to a new platform.  Prior to this, we worked mainly off of Jupyter and Colab notebooks.<br>
- Apache Spark – Spark was an entirely new framework for us.  Due to the sheer size of the dataset, a cluster-computing framework was the only feasible solution <br>
- It’s in Russian – Lastly, the dataset was in Russian. <br>
2.   	Redundant Features:<br>
·       The dataset that we were working with also had a lot of features (173 originally)<br>
3.   	Modeling Troubles (Out of Memory errors):<br>
·       We would also run into problems with modeling via Spark.  We were able to successfully execute a Logistic Regression model, but had issues with other models.<br>
## Solutions & Lessons Learned:<br>
1.   	Rapid upskilling:<br>
·       Created a quick Spark Tutorial for next batch of interns<br>
·       Utilized available resources: Spark – The Definitive Guide & a Udemy course on Spark<br>
2.   	Assisted colleagues with exploring the listed features, and identifying redundant and duplicate columns<br>
3.   	We were able to successfully run a Logistic Regression model using Spark, resulting in new results for C4ADS. <br>
We wanted to run more complex models like Balanced Random Forest, XGBoost, and RESVM.  We tried a number of different solutions, but to no avail due to memory errors.  Ultimately, during the last week of the internship, we received validation from one of our Data Science instructors that Spark is not the best framework to use for modeling.  It’s great for data exploration, cleaning, and wrangling, but not for modeling.<br>
Internship Outcome:<br>
·       Created the "infrastructure" for the next build-on internship group<br>
·       Reduced the Features (from 173 to 105); removed duplicates, useless, and redundant data<br>
·       Found 319 new potential hits based on a new feature.<br>
Direct Contributions:<br>
·       Led interactions between stakeholder and team<br>
·       Led official presentations on behalf of group’s progress to class and Program Manager<br>
·       Led initiative in Documentation for future internship groups<br>
·       Created Spark tutorial Colab notebook<br>
·       Assisted with Data Cleaning<br>
·       Assisted with Data Modeling<br>
