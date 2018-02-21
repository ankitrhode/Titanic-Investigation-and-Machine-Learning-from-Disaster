# Titanic-Investigation-and-Machine-Learning-from-Disaster
![TITANIC ](https://thumbs-prod.si-cdn.com/pyUNghb1qo8BXTCLvRYKNZi3uRw=/800x600/filters:no_upscale()/https://public-media.smithsonianmag.com/filer/ae/fc/aefc1fc2-e241-4a17-b73b-9ad6518427cb/stower_titanic.jpg)

* **Goal of this Notebook:** 
  - Investigation - whether passenger's features correlate with survival?
  - Analysis of *Titanic dataset*.
  - Finding the best working classifier for *Titanic dataset*.
  
* **This Notebook will show basic examples of:**
  * Investigation - whether passenger's features correlate with survival?
    * Importing libraries
    * Importing data with *Pandas*
    * Feature engineering
    * Determine passenger's features to test against survival¶
    
  * Analysis of *Titanic dataset*
    * Plot/graph variables and mathematically exploration
    
  * Machine Learing on Titanic dataset
    * Importing machine learning libraries
    * Data cleaning
    * Feature extraction
    * Classification algorithms
    * Visualization
 
* **Dependencies**
  * **Numpy:** It provides a high-performance multidimensional array and basic tools to compute with and manipulate these arrays.
  * **Pandas:** For data manipulation and analysis.
  * **SciKit-Learn:** Python machine learning library which features various classification, regression and clustering algorithms.
  * **Matplotlib:** Python Plotting.
  * **Seaborn:** Python's Statistical Data Visualization Library.
  * **Scipy:** It provides a large number of functions that operate on numpy arrays and are useful for different types of scientific and engineering applications.
  
* **Overview of Titanic dataset**
  * **survival:** Survival; 0 = No, 1 = Yes
  * **pclass:** Ticket class, a proxy for socio-economic status (SES); 1 = 1st (Upper), 2 = 2nd (Middle), 3 = 3rd (Lower)
  * **sex:** Sex of passenger
  * **Age:** Age in years
  * **sibsp:** # of siblings / spouses aboard the Titanic
  * **parch:** # of parents / children aboard the Titanic
  * **ticket:** Ticket number
  * **fare:** Passenger fare
  * **cabin:** Cabin number
  * **embarked:** Port of Embarkation; C = Cherbourg, Q = Queenstown, S = Southampton
  
 
* **Conclusions**
  * **Investigation:** Which passenger characteristics correlate with survival?
    * Passenger gender correlates with survival: Females were more likely to survive than males.
    * Passenger class correlates with survival: The higher the passenger's class, the more likely that he or she survived.
    
  * **Machine Learning on Titanic dataset**
    * GradientBoostingClassifier can be used to find insights on the Titanic dataset.
