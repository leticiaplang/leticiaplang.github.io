## Welcome to my universe

<p align=center> 
  <img src="https://media1.giphy.com/media/26BoEeFJkz2eZUBcQ/giphy.gif?cid=ecf05e47n0ch6qzasfv25butscg06czj8dqk6776kht3hnee&rid=giphy.gif&ct=g" alt="animated" height=300 width=300/>
</p>


My purpouse here is organize all my publications to facilitate objective access 😊


-----
### Drug Classification   
    🏷️ data cleaning, data wrangling, insights for business, classification algorithm
    Business problem: how accurately can we prescribe the correct treatment?
    Solution: it was possible get some insights with the exploratory analysis, but for accuracy 
      the classification algorithm will be a better solution.
    Conclusion:
      - the drug A is prescripted on this sample for people younger than 50 years, with high blood pressure 
      and Na to K lower than 15;
      - the drug B is prescripted on this sample for people older than 50 years, with high blood pressure 
      and Na to K lower than 15;
      - the drug C is prescripted on this sample for people with low blood pressure, high colesterol, 
      and Na to K lower than 15;
      - the drug X is prescripted on this sample for people with normal or low blood pressure and
      Na to K lower than 15;
      - the drug Y is prescripted on this sample for people with Na to k higher than 15;
      - the baseline dummy classifier(45%) loosed for logistic regression model which predict 
      correctly the treatment 89%
    Next steps: collect more data and tune the model
   <a href="https://github.com/leticiaplang/drug_classification" target="_blank"><img src="https://img.shields.io/badge/EN|Github-333333?style=for-the-badge&logo=github&logoColor=white" target="_blank"></a>
---
### Rent Calculator  
    🏷️ data cleaning, data wrangling, feature engineering, regression algorithm, tuning model, deploying model
    Business problem: create a calculator to predict the rent value for client at Florianópolis - Santa Catarina - BR
    Solution: web scrap the site to get all the informations, clean the data and explore that, define the features 
      and the target, test regression models, tune and define the better model to deploy it.
    Conclusion:
      - the baseline was linear regression and other model tested was decision tree, lasso and SVR. None of the models 
      get a good performance and the better result was predict 35% correctly. the dataset is small and the data was 
      collected at summer season, which makes a really high price on the isle.  
    Next steps: tuning the model and dig deeper on statistics metrics to see if the model construction is possible 
      or not with this sample.
   <a href="https://github.com/leticiaplang/rent_calculator" target="_blank"><img src="https://img.shields.io/badge/EN|Github-333333?style=for-the-badge&logo=github&logoColor=white" target="_blank"></a>
---
