# phase-1-project.
# Aircraft Acquisition strategy

## Executive summary
Brief overview of the business problems and objectives

## Business Understanding
**problem statement**;The company has neither history nor experience in Aviation industry,determing which aircraft will have lowest to none risk to begin this new business ventures at affordable cost and successful entry to the market
**key stakeholders**: internal {company stakeholders,potential investors};External{goverment policies,competition(other airline businesses),customers
**Responsibility**: Business Analysis,key stakeholders
**success criteria**:successful entry to the aviation industry with completion of regularities and selection of low risk aircraft
**Resources**: Budget, information on aircraft safety, Industry Reports,expert consultations
**Risks**:potential financial losses,safety incidents

### Project plans & Goals
use provided **dataSet** and available information inlets to have a general overview of lifetime of aviation
Industry(requirements,advantage,disadvantage)
identifying main cause of accidents which aircraft is more prone to?,are the accidents due to human interventions?are the aircraft well maintained?.

## DATA ANALYSIS
### Part 1: data understanding
-The best outline for the project was tabled by **kaggle**, the initial finding was provided by another group of data analysts
-The finding of this project has been provided in **csv(comma separated values)format** and are stored in **data file** under the**Aviation_Data.csv**which besically outlines a range of aircraft & airlines accidents
-The csv file is then read into a dataframe to allow extraction of information we want to get insights
-The **dataframe** has **(90348=rows,31=columns)**
-columns= unique field names
rows= have the unique figures of each column
-The **dataFrame** has both instances of **continous&categirical data**this becames kwown after running (**df.info**)
continous data = **float**(Qantitive)(measurable values representing a range of information)
categorical data = **objects**(Qualitative)(not inform of numbers) 

### Part 2 data cleaning
-After getting to understand our data ,we have to go further to get what is needed & why for our project.
-The importance of this , is to get into the market with **clear,extensive and relevant knowledge** to get into the market
-1) We identified if there was missing row in our dataframe,which in our understanding there was none
2)Then identifying the total {in%) of values missing in all columns.This provides a basis on each column and provide key insigh to this project
-3)deciding on a passmark of {60%} which of the columns are not relevant to our study;
"longitude","latitude","location"-tableau provides detailed axis points
"schedule" - has more than 85% missing values
"Air.carrier" - has more than 80% missing values
"FAR Description"-necessary airlaine regulation that are incomplete and change from time to time 
next we drop all the rows with missing values
### part 3: Data Aggregation
-this all relevant data to form a basis of our research 
**Amateur.Built = directly diving into market may prove to be strenous and might also discourage shareholders or potential investors.So this leads to the decision to seek cheaper alternatives,thus we will calibrating are the cheater airplanes (ameteur.built)safer**
**weather condition & Aircraft damage = *how spread is human error?the minimal amount exposes human.this will provide the basis creteria for hiring potential employees once in the market.
**make & model = this gives general oversight on which route to take when purchasing safe hire.
**aircraft category =helps us understand  before starting the business ventures which of our aircraft category is most prone to accidents**
**country = helps understand no. of accidents and how spread out they are.This analysis will also explain how other competitions are.

### part 4.Data visualizations
This is done to prove our findings
**barplot=country=this heips us see where their is a succesful safety market and gauge other competitions on how they are fairing on in the market**henceforth japan provides a safer yet very competitive market,meanwhile haiti offers a dangerous yet open market.
**piechart-Amateur.Built-this helps us see results of cheaper options and see if it actually fairs on better than the expensive
airlines .This will help management make decision that might be better**
**linegraphs-provides a clear insight on how many aircraft damages were actually natural,they give emphasis of not taking necessary flight precautions due to weather**
**scatterplots-airplanes-gives a clear view of the risk analysis of the most common used commodity in the aviation industry.This gives the shareholders a chance figure out other alternatives**
https://public.tableau.com/app/profile/anthony.kamot/viz/Book3_17273347900030/Sheet4?publish=yes
#### RECOMMENDATIONS.
For purpose of flight I will recomment  (public aircraft , ferry and aeria observation)have lowest number of accidents.
Planes with amateur build experience less accidents
Planes with (UNK , LR & Electric) engine type are safest.
Japan provides safer and most competitive market.

