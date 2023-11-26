 <div align="justify">

# Programming for Data Analysis Assignment: Project 1
![Records](image-1.png)
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

 </div>