# Insurance-Prediction
A Python Program to model the life expectancy of an individual and analyze the sustainability of an insurance policy provided to the individual using linear regression. EDA is performed on the dataset which consists of the person’s lifestyle. Box Cox Transformation and Structural equation modeling is performed on the target variable, SEM examines linear causal relationships among variables and simultaneously accounts for measurement error. 
# Insurance Prediction

<p align="justify">
This jupyter notebook is a data visualization project for visualizing the insurance / charges for a particular person, and checking whether is their any bias in the tesing or not. This was purely done in https://colab.research.google.com/ a tool for python notebooks. Structural equation modelling a trending data visualizing method is being utlized here using necessary libraries. 
</p>

# About the dataset

The dataset is taken from kaggle.com

![Columns details](https://github.com/SiddhuSiddharth/Insurance-prediction/blob/999b6cf95a974e22c22594dde5a34722d0e27eeb/Images-readme/Dataset1.png)

This is a view of the columns of the dataset. Which is taken directly from the notebook itself.
* Column 0 which is the **age** column has values ranging from 0 to 100
* Column 1 which is the **sex** column has values male and female that is the gender of the particular subject
* Column 2 which is the **bmi** column has float values which helps to determine how well the subject has maintained their health based on their bmi values which is calculated using $\dfrac{weight}{height^2}$ in kgs and ms respectively.
* Column 3 which is the **children** has values ranging from 0 to 5. It represents the no. of children the particular subject has. This is a family related trait.
* Column 4 which is the **smoker** tells whether the person smokes or not. This is vital for determining their current health, and how much bias should we show on his insurance / charges
* Column 5 which is the **region** in the city where the particular subject lives in is denoted using 4 dual-cardinal directions: SW, NW, NE, SE. We can also use this to determine factors like regional bias or regional habits. Lets say like for example people in SW region smoke a lot or not de to their lifestyle.
* Column 6 which is the **charges** of the subject, allocated by the insurance company. We do not know what factors they used to predict and allocate the charges value for. So we are going to predict using our own models and check conditions like bias, and in general analyse the dataset.

Here is a brief of the dataset.

![Breifing](https://github.com/SiddhuSiddharth/Insurance-prediction/blob/999b6cf95a974e22c22594dde5a34722d0e27eeb/Images-readme/Dataset2.png)

# Models used

Models used are:

* **Linear regression:** A simple regression model helps as a stepping stone and gives a brief on whether there are any anomolities.
* **Structural equation modelling optimization:** This is a structural visualization of the attributes and what they lead to, or what can be determined from them.
* **Cox Box normalization:** This helps visualize the plot thus making a more pleasing view of the data and helps us to perform mathematical calculations much easier.
* **Heatmaps:** Heatmaps helps us view the realtion between all the numerical datasets individually. This can also give us an idea whether we should use regression on them or not.
* **Violin plots:** These are an alternate to box plots but they are little bit better visualization purposes as they show the distribution amongst the non-outlier observations.

# References

There are a couple references for us that helped us to prepare the notebook.

> References
> 
> https://www.kaggle.com
> 
> https://towardsdatascience.com/
> 
> https://pypi.org/
> 
> https://semopy.com


