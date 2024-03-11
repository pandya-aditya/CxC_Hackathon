**Flame Forecaster**

**AI-driven Wildfire Prediction Project: Safeguarding Alberta by identifying vulnerabilities and forecasting wildfire severity.**

Inspiration:
Observing the recurring challenges posed by wildfires in Alberta, we were motivated to research and apply our knowledge on data-driven approaches to improve wildfire prediction and management.

What it does:
This project utilizes data analysis and machine learning to predict wildfire severity and area burned in Alberta. We performed an analysis on vulnerable regions and key factors contributing to wildfire occurrences.

How we built it:
We used Pandas and NumPy to process wildfire data, categorizing it by size class and causes. By analyzing factors like total fires and size burned, we identified the most vulnerable FSA regions. After this, we explored wildfire causes and developed prediction models, including linear regression and Random Forest Regression, to forecast the severity and final size of wildfires based on various factors.

Challenges we ran into:
One challenge we encountered was selecting a machine learning algorithm with both high accuracy and interpretability, given the intricacy of the dataset. After experimenting with many different kinds, we implemented a non-linear model using an Extreme Gradient Boosting Regressor, which was a combination of other non-linear models we tested.

Accomplishments that we're proud of:
We're proud of our achievement in accurately identifying vulnerable regions prone to severe wildfires by integrating the complex datasets and applying our own machine learning techniques. We hope our analysis of wildfire causes and their impact on different severity classes provides valuable insights for designing targeted prevention.

What we learned:
We learned the significance of meticulous data preprocessing to ensure accurate and clear visualizations, such as removing bad/empty values from datasets. Additionally, we also learned the pros and cons of different machine learning algorithms, and which could be useful in a given scenario.

What's next for our project:
Moving forward, the project could improve by employing sequential feature selectors for enhanced model accuracy, considering min-max scaling instead of standardization for optimized data scaling, and conducting a more comprehensive feature identification process.

Built with:
python, pandas, numpy, matplotlib, scikit-learn, seaborn, xgboost
