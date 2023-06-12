# Delivery Data Analysis and Predictive Modeling

## Background
The delivery industry plays a crucial role in the modern economy, ensuring the timely transportation of goods and enhancing customer satisfaction. With the increasing demand for efficient and reliable delivery services, it is essential for companies to gain insights into their delivery operations and identify opportunities for optimization.

The purpose of this project is to provide a sample demonstration of how data analysis and machine learning techniques can be implemented in the logistics industry. It is important to note that this project represents a limited scope and serves as a starting point for further research and development in this field.

While the dataset used for this project spans a 3 days period and includes various attributes related to delivery operations, it is essential to acknowledge that a comprehensive analysis of the logistics industry requires more extensive time, data, and resources. The complexities and nuances of real-world logistics scenarios necessitate a deeper exploration and a larger-scale study to capture a broader range of factors and their interplay.

By conducting this sample project, we aim to showcase the potential benefits and applications of leveraging data in the logistics industry. The exploratory data analysis and machine learning model developed herein provide a glimpse into the insights that can be derived from delivery data and how they can contribute to optimizing operations.

## Files
```
delivery_analysis
├── data
│   ├── data-sample.json
├── models
│   ├── gradient_boost_model.joblib
├── notebook.ipynb
└── Report.html
└── README.md
```

## Report
The report contains all the analysis and explanations we have obtained. It also provides a step-by-step guide on how to develop a Machine Learning model that can be utilized by a delivery service company to enhance their performance.

You can access the report in both HTML and Python Notebook formats. To view the HTML format report, open the `Report.html` file. For the Python Notebook, open the `notebook.ipynb` file.  

## Machine Learning Model
We have developed a machine learning model to predict the success of a delivery. The model is saved in Joblib format and can be found in the models folder.

If you wish to use this model, you can import it using the code snippet provided below:

```
from joblib import load

model = load("models/gradient_boost_model.joblib")
```
