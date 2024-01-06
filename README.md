 <div align="justify">

# Programming for Data Analysis Assignment: Project 1
![Alt text](img/Records.png)
## Record Price Prediction Model

### Overview
This project aims to provide a theoretical guide for record collectors to determine the price of a record based on various factors. The analysis focuses on a sample of 100 commonly sought-after records between 2015 and 2020. The underlying trends shaping the price are explored using four key parameters: Vinyl Scarcity, Record Condition, Genre, and Auction Results.
### Dataset Creation
To establish a reliable basis for prediction, a dataset was created with random auction results using **numpy.random** package. The dataset was then manipulated using **Pandas** to incorporate the key parameters. This comprehensive dataset is essential for training and evaluating the predictive model.
### Parameters
1. **Vinyl Scarcity**
Vinyl scarcity refers to the availability of a particular record in the market. Records that are rare or hard to find tend to have higher values. The scarcity of vinyl is a crucial factor in determining the price trend.
2. **Record Condition**
The condition of a record significantly influences its value. Mint condition records are generally more valuable than those with wear and tear. The analysis considers the impact of different condition levels on the pricing trends.
3. **Genre**
The genre of a record plays a vital role in its market demand. Certain genres may experience fluctuations in popularity, affecting the overall price trends. The project examines how genre influences the pricing dynamics of the selected records.
4. **Auction Results**
Auction results provide real-world insights into the market value of records. By analyzing auction data between 2015 and 2020, the model aims to capture the trends and patterns in record pricing.
### Methodology
This project has been developed using **Python** and its powerful tools and, in particular, **Jupyter Notebook** with its interactive data exploration and analysis features. The *random.numpy* package is employed for generating random auction results, while **Pandas** is used for data manipulation and cleaning. Matplotlib is the tool of choice for visualizing the trends in auction results from 2015 to 2019.
### Usage
* Ensure Python is Installed:
Make sure you have Python installed on your machine.
* Clone the Repository:
Clone the repository to your local machine:  

`git clone https://github.com/AndreaCignoni/PfDA_Project_1.git`
* Install Required Libraries:
Install the necessary libraries using the following command:
<pre>

pip install numpy
pip install pandas
pip install matplotlib

</pre>
* Open the Jupyter Notebook file (`PfDA_Project_1.ipynb`) to interactively explore the analysis and visualize the trends.
### Results
The notebook provides a comprehensive overview of the trends observed in the auction results for the selected records. Visualizations generated using *Matplotlib* offer insights into how the market demand progresses as a *plot line* across the time span considered.
### Future Work
This project lays the foundation for predicting record prices. Future work may involve implementing machine learning models to make more accurate predictions based on the identified parameters. Additionally, expanding the dataset and incorporating external factors could enhance the model's predictive capabilities.
Feel free to explore the *Jupyter Notebook* to delve into the details of the analysis and gain a deeper understanding of the factors influencing record prices.

***

## *References*

1. **[Pandas User Guide](https://pandas.pydata.org/pandas-docs/stable/user_guide/10min.html)**
   - Official documentation for *Pandas*. A comprehensive guide for working with data frames and series in Python.

2. **[W3Schools - Random Module](https://www.w3schools.com/python/module_random.asp)**
   - W3School tutorial on the Python Random module. Learn how to generate random numbers and perform randomization in Python.

3. **[Matplotlib Quick Start Guide](https://matplotlib.org/stable/users/explain/quick_start.html)**
   - Quick start guide from *Matplotlib*. Essential information to get started with creating visualizations in Python.

4. **[Java Exercise - Nested Tuples](https://www.javaexercise.com/python/python-nested-tuples)**
   - Tutorial on *nested tuples* in Python. Understanding the concept of *nested tuples* and their applications.

5. **[Real Python - Python Dictionaries](https://realpython.com/python-dicts/)**
   - Real Python's guide to *Python dictionaries*. Explore the fundamentals and advanced usage of *dictionaries* in Python.

6. **[I/O FOOD - Guide to Using Empty Lists in Python](https://ioflood.com/blog/python-empty-list-guide-to-using-empty-lists-in-python/)**
   - *I/O FOOD*'s comprehensive guide on using empty lists in Python. Learn best practices and use cases for empty lists.

7. **[Pandas User Guide](https://pandas.pydata.org/pandas-docs/stable/user_guide/10min.html)**
   - Revisit the *Pandas User Guide* for quick reference and in-depth understanding of Pandas functionalities.

8. **[GeeksforGeeks - Unpacking a Tuple in Python](https://www.geeksforgeeks.org/unpacking-a-tuple-in-python/)**
   - *GeeksforGeeks* tutorial on unpacking a tuple in Python. Uncover the techniques and benefits of tuple unpacking.

9. **[Codecademy - Pandas DataFrame Loc](https://www.codecademy.com/resources/docs/pandas/dataframe/loc)**
   - *Codecademy*'s resource on *Pandas DataFrame Loc*. Learn how to access and manipulate data using the *loc* method.

10. **[Built In - Adding a Column in Pandas](https://builtin.com/data-science/pandas-add-column)**
    - Built In's guide on adding a column in *Pandas*. Understand different methods to add columns to a *Pandas DataFrame*.

***

### End
 </div>