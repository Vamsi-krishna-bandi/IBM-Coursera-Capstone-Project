# IBM-Coursera-Capstone-Project
Space X capstone project to predict the success or failure of the first stage landing of Falcon 9 vehicle using classification model

![image](https://github.com/Vamsi-krishna-bandi/IBM-Coursera-Capstone-Project/assets/167190561/9c267f3a-672c-472c-b98c-b1111c230245)
**Objective**
  SpaceX promotes Falcon 9 rocket launches on its website at a price of 62 million dollars, significantly lower than the upwards of 165 million dollars charged by other providers. Much of this cost-saving stems from SpaceX's ability to reuse the first stage. Therefore, assessing the likelihood of the first stage landing allows for a precise determination of launch costs. So, To determine the outcome of first stage landing of Falcon 9 we have to develop a classification model to predict the outcome.

**Tools Used**
  Python - Numpy, Pandas, SQLite3, BeautifulSoup, Matplotlib, Plotly, Dash,
  Scikit Learn - K Nearest Neighbors, Decision Tree Classifier, Support Vector Machine, Logistic Regression
  Github

**Summary**
	SpaceX promotes Falcon 9 rocket launches on its website at a price of 62 million dollars, significantly lower than the upwards of 165 million dollars charged by other providers. Much of this cost-saving stems from SpaceX's ability to reuse the first stage. Therefore, assessing the likelihood of the first stage landing allows for a precise determination of launch costs. This insight proves valuable for competing companies considering bidding against SpaceX for a rocket launch.
	I conducted comprehensive data collection, wrangling, and exploratory data analysis to derive insights. Subsequently, I employed various classification models for data modeling, ultimately selecting the Decision Tree classifier due to its 83.3% accuracy and superior predictability compared to other models. Now, we can accurately ascertain whether the first stage of the Falcon 9 rocket lands successfully.

**Solution**
  To address the problem at hand, data has been gathered from two key sources: the SPACE X API and various web sources. After conducting extensive data wrangling and exploratory analysis, several insights have been uncovered such as

• The launch site which is having higher success ratio. 
• Payloads which experience higher success rates. 
• Orbits that exhibit higher success rates along with payload mass. 
• Success rates trend over the years.

  Following this analysis, various classification models were employed for data modeling. Among these models, Logistic Regression, Support Vector Machines, and Decision Tree Classifier demonstrated a higher accuracy of 0.833. However, the Decision Tree model stands out by predicting fewer False Positives compared to the others. This characteristic makes it more accurate in predicting unsuccessful landings, a crucial aspect of our objective. By the Decision Tree Classifier, we can forecast the outcome of the first stage landing of Falcon 9 with an accuracy of 83.3%. Such predictive capability serves to assist businesses in determining launch costs, as the safe landing of the first stage allows for substantial cost reduction through reuse.

**Approach**
  In this project, I gathered data from both an API and web sources, ensuring its correctness and formatting using the requests library and BeautifulSoup. Subsequently, I conducted data wrangling and exploratory data analysis, employing various analytical graphs and statistical summaries through matplotlib and pandas. For geo-special analysis and interactive visualization, I utilized folium and dash, deriving insights from the data.

  Following the analysis, I selected features pertinent to Falcon 9 first stage landing. The data underwent normalization and preparation for modeling. I trained various classification models, fine-tuning hyperparameters using Grid Search CV, and conducted testing. Each model underwent evaluation using scores and confusion matrices, employing the best parameters.

  Ultimately, the Decision Tree Classifier exhibited superior accuracy and predictability, with fewer false positives compared to others. Hence, I selected this model for predicting the success or failure of the first-stage landing, achieving an accuracy of 83.33%.
