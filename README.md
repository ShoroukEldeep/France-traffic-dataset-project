# France-traffic-dataset-project
### Final project of feature engineering training
## Table of Contents

1. Introduction <br>
   1.1 Importing Libraries<br><br>
   
2. Data Wrangling <br>
   2.1 Reading Dataset<br>
   2.2 Exploring Data<br>
   2.3 Check Missing Data<br>
   2.4 Cleaning Data<br><br>

3. Statstics<br>
4. Feature Extraction<br>
   4.1 Extract new columns<br>
   4.2 Exploratory Data Analysis<br><br>

5. Work With Categorical Data<br>


## About data
#### DataSet Columns:
- This dataset presents the number of passenger validations per day per station name and per ticket on the rail network.
     * DATE : Date of validation.
     * STATION_NAME : validation's station name.
     * ID_REFA_LDA : Stop identifier in the STIF reference database.
     * TITLE_CATEGORY : Transport tickets( IMAGINE R,NAVIGO, AMETHYSTE, FGT , NOT DEFINED)
     * NB_VALID : The number of passenger validations
     
#### Title_categories Column: 

   * IMAGINE R: combines the annual Imagine R School and Imagine R Student packages reserved for pupils, apprentices           and students which allows to travel at will all year round and in all of Ile-de-France.<br>
   
   * NAVIGO : includes the Navigo Annuel, Navigo Mois and Navigo Semaine packages.<br>
   
   * AMETHYSTE : includes the Amethyst packages: package reserved for seniors or disabled under conditions of means or          status, and residing in the Île-de-France region.<br>
   
   * TST : groups together weekly and monthly reduced fare packages granted to beneficiaries of the Transportation              Solidarity Reduction program, to travel within the selected zones in all the modes of transport in the Île-de-France        region.<br>
   
   * FGT : accounts for the Navigo Gratuité Transport Packages, a package that allows certain receiving social assistance        to travel free of charge throughout the Paris Region.<br>
   
   * OTHER TITLE : accounts for special packages.<br><br>
   
   * NON DEFINED : records validations for which the type of ticket is not defined (anomalies)<br>
     
     NB_VALID : Number of validations. 1 validation = 1 person <br>
     ID REFA LDA : -1 means that the data is not defined
 
