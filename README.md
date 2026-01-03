## Social Media Data Analysis Project

This project simulates an end-to-end analysis of social media data (e.g., simulated Tweets) to gain insights into user engagement, specifically focusing on the distribution of "Likes" across different content categories. It demonstrates core data science skills, including data generation, cleaning, exploration, visualization, and statistical analysis using Python's data science toolkit.

---

### Project Overview and Goal

The objective of this project is to analyze a simulated social media dataset to understand trends in likes across different categories and draw conclusions about the most popular and engaging content areas on the platform.

The process involved:

* **Generating** pseudo-random data for dates, categories, and likes.
* **Loading and Exploring** the data using a Pandas DataFrame.
* **Cleaning** the data by handling null/duplicate entries and ensuring correct data types.
* **Analyzing and Visualizing** the data using Seaborn and descriptive statistics.

---

### Prerequisites

To run and follow along with this project, you should have a basic understanding of Python programming and data analysis concepts.

The following Python packages are required:

* **`pandas`**: Used for data manipulation and analysis.


* **`numpy`**: Used for numerical computations.


* **`matplotlib`**: Used for data visualization.


* **`seaborn`**: Used for statistical data visualization.


* **`random`**: Used to generate random numbers for data simulation.



These packages can typically be installed using `pip`:

```bash
!pip install pandas
!pip install matplotlib
!pip install numpy
!pip install seaborn

```

---

### Key Analysis and Results

The analysis of the simulated data revealed clear insights into user engagement.

#### Distribution of Likes (Histogram)

* The histogram of 'Likes' shows a **strong right-skew**.


* This confirms that a large majority of posts receive lower engagement, with only a few posts becoming "viral" outliers.



#### Engagement by Category

* The mean of all Likes across the dataset was **5023.90**.


* Analysis using `groupby().mean()` indicated a variation in engagement across categories, with the highest and lowest average likes as follows:


* **Highest Average Likes:** **Health** (Mean: 5522.26).


* **Lowest Average Likes:** **Culture** (Mean: 4528.80).





| Category | Mean Likes |
| --- | --- |
| Health | 5522.26 |
| Fitness | 5353.09 |
| Music | 5253.36 |
| Travel | 5200.96 |
| Fashion | 5071.05 |
| Family | 4822.17 |
| Food | 4630.46 |
| Culture | 4528.80 |

---

### Future Improvements

To transition this project into a real-world business endeavor, the following improvements are recommended:

* **Integrate Live Data:** Replace the randomly generated data with authentic, live data pulled from a social media API (e.g., Twitter/X or Instagram).


* **Implement AI Sentiment Analysis:** Integrate an AI model to correlate the positive or negative tone of a post with its engagement. This provides a richer, actionable layer of intelligence for marketing teams.
