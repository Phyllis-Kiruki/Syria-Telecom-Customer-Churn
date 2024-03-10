# SYRIA TELECOM CUSTOMER CHURN

This project focuses on analyzing customer churn for Syria Telecom, aiming to understand the factors influencing customer attrition and develop strategies to reduce, how much money is lost. ( This is a binary classification problem.)

## Description

To provide a more detailed description of encoding categorical variables for machine learning projects, it is essential to understand that categorical variables are those that represent categories rather than numerical values.
One Hot Encoding: Represents each category as a binary vector.
Machine learning algorithms require numerical data; hence, encoding categorical variables is crucial for model building.
The SyriaTel Customer Churn dataset provides valuable insights into predicting customer churn for the telecommunications company, SyriaTel. This README aims to provide an overview of the dataset, its context, methodology, results, and future recommendations based on the analysis conducted.
Context of Project
The project focuses on analyzing the churn dataset from the telecom industry to predict customer churn and understand the key factors driving churn for SyriaTel. The dataset includes information on customer behavior, plan details, and churn status.
Data
The dataset contains information on 3333 customers who have held accounts with SyriaTel for less than 243 days.
Features include locational information, plan details (call charges, customer service calls, international plan), and churn status.
The target variable for prediction is the churn column.
Process
Various classification models were tested, including Decision Tree Classifier, Logistic Regression Classifier, KNN Classifier, Random Forest Classifier, and Gradient Boost Classifier.
Models were evaluated based on the recall score metric and confusion matrices to assess performance.
Results
The best model identified was a Gradient Boost model with a recall score of 0.81 on the test data.
This model showed significant improvement over previous models in terms of recall score and false predictions.
Future Investigations and Recommendations
Further investigation is recommended to explore additional characteristics of customers contributing to churn.
Focus on understanding why international plan holders have a high churn rate.
Implement strategies to reduce churn by analyzing customer behavior and improving service quality.
For more detailed analysis and findings, refer to the Jupyter Notebooks provided in the repository. This README provides a comprehensive overview of the SyriaTel Customer Churn dataset analysis conducted to predict customer churn and offer insights into improving customer retention strategies.

<div class='tableauPlaceholder' id='viz1710097356389' style='position: relative'><noscript><a href='#'><img alt='Dashboard 1 ' src='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;Bo&#47;Book1_17100973279380&#47;Dashboard1&#47;1_rss.png' style='border: none' /></a></noscript><object class='tableauViz'  style='display:none;'><param name='host_url' value='https%3A%2F%2Fpublic.tableau.com%2F' /> <param name='embed_code_version' value='3' /> <param name='site_root' value='' /><param name='name' value='Book1_17100973279380&#47;Dashboard1' /><param name='tabs' value='no' /><param name='toolbar' value='yes' /><param name='static_image' value='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;Bo&#47;Book1_17100973279380&#47;Dashboard1&#47;1.png' /> <param name='animate_transition' value='yes' /><param name='display_static_image' value='yes' /><param name='display_spinner' value='yes' /><param name='display_overlay' value='yes' /><param name='display_count' value='yes' /><param name='language' value='en-US' /><param name='filter' value='publish=yes' /></object></div>                <script type='text/javascript'>                    var divElement = document.getElementById('viz1710097356389');                    var vizElement = divElement.getElementsByTagName('object')[0];                    if ( divElement.offsetWidth > 800 ) { vizElement.style.minWidth='420px';vizElement.style.maxWidth='650px';vizElement.style.width='100%';vizElement.style.minHeight='587px';vizElement.style.maxHeight='887px';vizElement.style.height=(divElement.offsetWidth*0.75)+'px';} else if ( divElement.offsetWidth > 500 ) { vizElement.style.minWidth='420px';vizElement.style.maxWidth='650px';vizElement.style.width='100%';vizElement.style.minHeight='587px';vizElement.style.maxHeight='887px';vizElement.style.height=(divElement.offsetWidth*0.75)+'px';} else { vizElement.style.width='100%';vizElement.style.height='727px';}                     var scriptElement = document.createElement('script');                    scriptElement.src = 'https://public.tableau.com/javascripts/api/viz_v1.js';                    vizElement.parentNode.insertBefore(scriptElement, vizElement);                </script>