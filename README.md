# biostat823-covid19-analysis-project

## Team Members
Gong Han (Data Science, Duke University)

Junrong Lin (Biostatistics, Duke University)

Lucy Lin (Biostatistics, Duke University)

Jenny Zhuo (Biostatistics, Duke University)

## The objective of the Project & Target Audience
Build a dashboard showing the recent situation of COVID-19:
   - the first page: visualizing the total number of vaccinations by state and by brand; 
   - the second page: visualizing the estimated number of deaths due to COVID-19 within the next few weeks by state; 
   - the third page: providing results and interpretation of machine learning models on predicting whether a COVID-19 positive patient will be discharged or deceased based on their characteristics.

This dashboard provides an overview of several essential aspects of the current COVID-19 situation: vaccinations, new cases, and deaths. Page one and two can be helpful to the consumers who are interested in knowing the estimated new cases for the next few weeks, learning about the trend of new cases, and detecting possible correlation between vaccinations and new cases. Meanwhile, page three is informative to the consumers who are curious about which factors may contribute more to the deaths of COVID-19 positive patients. Therefore, this dashboard makes the above information more simple and intuitive to find and understand.

## Data Set
The dataset we use come from the several sources:
   - Vaccination data: [click here](https://data.cdc.gov/Vaccinations/COVID-19-Vaccinations-in-the-United-States-Jurisdi/unsk-b7fc)
   - ML model for predicting death or discharge: [click here](https://wiki.cancerimagingarchive.net/pages/viewpage.action?pageId=89096912#89096912bcab02c187174a288dbcbf95d26179e8)
   - Death Cases Forecasting Data: [click here](https://www.cdc.gov/coronavirus/2019-ncov/science/forecasting/forecasting-us.html)

## Data science plan
   - Exploratory data analysis includes dealing with the imbalanced data and missing data     
     (1) create the base dataset by deleting all the missing values directly      
     (2) create the imputed dataset by imputing all the categorical variables by their modes      
     (3) create the balanced dataset by oversampling the minority class     
     (4) create the dataset with both imputation and oversampling      
   - Visualize the distribution of vaccinations using `plotly`        
   - Visualize the estimated new cases using `plotly`      
   - Visualize the classification accuracy and results of different models using `plotly`      
   - Interpret the best model for each dataset mentioned above by using `shap`      
   - Deploy the dashboard on the website         
 
 ## Roles, responsibilities and timed milestones
 By October 20th
   - Form the team and discuss the potential topics and datasets (All)
  
 By November 10th
   - Data preprocessing and exploratory data analysis (Yili, Jenny)
   - Create visualization dashboard for the distribution of vaccinations (Han)
 
 By November 24th
   - Create visualization dashboard for the forecast of new cases (Han)
   - Create visualization dashboard for the model performances and model interpretation (Yili, Jenny)
   - Deploy the dashboard on website (Junrong)
   - Finalize the repository (All)

