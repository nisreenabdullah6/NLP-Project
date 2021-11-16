{
 "cells": [
  {
   "cell_type": "markdown",
   "metadata": {},
   "source": [
    "## NLP for Amazon Reviews sentiment:\n",
    "> In this project our task was to get a dataset to build an NLP model. We chose to analyze a dataset obtained from a website that collects amazon customers reviews of different products they bought.\n",
    "\n",
    "\n",
    "> -  We used the CountVectorizer tool to convetr the reviews into document-term matrix as unigram.\n",
    "> -  Then, we used Svd to extract and reduce the featutes we will use in the classification. \n",
    "> -  clustering.\n",
    "> -  We used a number of classifiction algorithms to pridect if the reviews will be negative or positive.\n",
    "\n",
    "## Data Collection :\n",
    "\n",
    ">**We chose the Luxury Beauty products dataset for this project:**\n",
    ">- The dataset was obtained from  this website https://nijianmo.github.io/amazon/index.html# \n",
    ">- The dataset contains 34278 reviews (rows) and 12 columns in total.\n",
    "\n",
    "\n",
    ">**Our EDA steps :**\n",
    "\n",
    ">- Dropping all the duplicated values and removing all the uneeded columns such as: reivewers names and IDs.\n",
    ">- Stripped all spaces and unwanted characters form the columns.\n",
    ">- Cleaning the outliers.\n",
    ">- Converting categorical data to numeric ones.\n",
    "\n",
    ">**After cleaning the dataset the remainning rows are 25911.**\n",
    "\n",
    "## EDA graph:\n",
    "\n",
    ">This graph shows the number of reviews for each month during the perioed of 14 years. the dataset we have are during thr period form 2005 to 2018.\n",
    "\n",
    "<img width=\"450\" alt=\"Screen Shot 2021-11-15 at 7 19 52 PM\" src=\"https://github.com/nisreenabdullah6/NLP-Project/blob/main/EDA-4.png\">\n",
    "\n",
    "## cluster graph\n",
    "> This graph shows the distrbution of words in customers reviwes in the dataset, and the number of colors represent the number of clusters.\n",
    "\n",
    "<img width=\"450\" alt=\"Screen Shot 2021-11-15 at 7 19 52 PM\" src=\"https://github.com/nisreenabdullah6/NLP-Project/blob/main/cluster.png\">\n",
    "\n",
    "\n",
    "\n",
    "## Future work:\n",
    "\n",
    ">- Convetrting the reviews into document-term matrix as bigram.\n",
    ">- Using other liberies such as Spacy.\n",
    "\n"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": null,
   "metadata": {},
   "outputs": [],
   "source": []
  }
 ],
 "metadata": {
  "kernelspec": {
   "display_name": "Python 3",
   "language": "python",
   "name": "python3"
  },
  "language_info": {
   "codemirror_mode": {
    "name": "ipython",
    "version": 3
   },
   "file_extension": ".py",
   "mimetype": "text/x-python",
   "name": "python",
   "nbconvert_exporter": "python",
   "pygments_lexer": "ipython3",
   "version": "3.7.4"
  }
 },
 "nbformat": 4,
 "nbformat_minor": 5
}
