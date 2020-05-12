# US-Border-Crossing-Analysis

This project is in reference to the <a href = "https://www.kaggle.com/divyansh22/us-border-crossing-data"> dataset </a> in kaggle.

You can refer to my <a href="https://medium.com/p/420fc0abb1c3/edit"> article </a>. 

![](/image%201.jpg) 


## Installations ## 

This project uses **Python 3.x**, so a suitable python version (>=3.6) is advisable.

The project uses the following packages:- 
<ul>
  <li> numpy </li>
  <li> pandas </li>
  <li> matplotlib </li>
  <li> sklearn </li>
  <li> seaborn </li>
</ul>

## Local Machine installation ##
If you do not have a working installation of these packages, the easiest way to install scikit-learn is using `pip`

`pip install <package name >`

or `conda`:

`conda install <package name>`

## Project Motivation ## 

The motivation for doing the project was primarily an interest in undertaking a challenging project in an interesting area of research.
The <a href="https://www.kaggle.com/divyansh22/us-border-crossing-data"> dataset </a> contains different features affecting the Border-Crossing of US. This project is used to analyse each and every feature and predict on the basis of the current values what can be the traffic caused due to Border-Crossing. 

The main questions that arrises while analyzing the dataset are:-

    1. Which is the leading neighbouring country from which a huge number of people cross the border?
    2. What is the most prefered Measure in order to cross the border?
    3. Which ports are more sensit ive areas?
    4. Is there any specific relation with the count of border crossing with the Date?
    5. How well can the Value be predicted? What aspects correlate well to the number of people crossing the border?

## Summary of the Result ##

On analyzing the Border parameter, about 7337300710 (about 77%) of the incidents marked in the dataset consisted of US-Mexico border meaning Mexicans have tended to come in more frequently into the US as compared to the Canadians from January 1996 to February 2020. Out of which Texas having the maximum share.

About 5,629,526,756 people have crossed the US-Mexico and US-Canada border by Personal Vehicles as Passengers which shows people avoid the public transport.

The Border Crossing is a critical situation to deal as the plot suggest the growth varying between 3 billion to 5.5 billion in range between 1996 to 2018. There is some improvement in 2019 with the data falling just short of 1 billion. The sudden fall in 2020 is solely owing to the recent COVID-19 outbreak.



##  File Descriptions ##

There are two working files and an image file in this repository.

The Comma Separated Value (Border-Crossing-Entry-Data.csv) file contains the entire dataset.

The Jupyter notebook (US-Border-Crossing-Data-Analysis.ipynb) file contains the project.

The image(.png) file is used to supplement the Jupyter notebook. (Source : Google images)

## Source code ## 

You can check the latest sources with the command:

`git clone https://github.com/deadshotsb/US-Border-Crossing-Analysis.git`

## How to interact ##

Download/clone the repository and provide the path to the (.csv) file provided in the repository.

In case of harware/Package failure you can try out <a href= "colab.research.google.com"> Google Colab </a>.


## License ##

The project is under <a href="http://www.apache.org/licenses/LICENSE-2.0" > Apache 2.0 License </a> 

The datatset is under <a href="https://www.usa.gov/government-works/"> U.S. Government Works License </a> 
