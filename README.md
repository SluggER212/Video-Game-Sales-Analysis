# Video-Game-Sales-Analysis

# Introduction:
The main aim of this project is to explore the world of video game sales using Python library Pandas, Matplotlib, and Seaborn which are used for data visualization. The dataset analyzed is "vgsales.csv", which includes information about various video games, their sales records from different regions, genres, and platforms.
#Data Exploration:
The analysis begins with loading the dataset into a Pandas DataFrame and examining its structure. The first few rows of the dataset are displayed using df.head(), and missing values are checked using df.isnull().sum(). Also the summary statistics of the numerical columns then are generated using df.describe() that give an idea about the central tendency, dispersion, and shape of a distribution of each numerical feature.

![1](https://github.com/SluggER212/Video-Game-Sales-Analysis/assets/126152029/882e0653-ddd8-4aed-9c0b-0ec8cc0fb25e)

![2](https://github.com/SluggER212/Video-Game-Sales-Analysis/assets/126152029/fe7385c2-9213-469b-a8bb-ffef94987614)

#Top 10 Games by Global Sales:

The study reveals the top 10 video games according to their all time maximum global sales. This is achieved by grouping the data by game name and then finding the maximum global sales for each game.

![3](https://github.com/SluggER212/Video-Game-Sales-Analysis/assets/126152029/88fa1a53-c705-4ad3-86ed-05cb4f91954d)

#Yearly Sales Trends:
The analysis then digs into the sales trends across the years. The number of games sold each year is shown with 2009 selling the highest overall.
#Games by genre:

![4](https://github.com/SluggER212/Video-Game-Sales-Analysis/assets/126152029/394190ac-6744-4677-bf9d-6da19429c8a5)

#Correlation Analysis:
The correlation matrix is explored to understand the relationships between sales figures in different regions (North America, Europe, Japan, and Other regions).

![5](https://github.com/SluggER212/Video-Game-Sales-Analysis/assets/126152029/190b5f99-e9d3-4cf8-82f3-262ebf682900)

#Regional Contribution to Global Sales:

![6](https://github.com/SluggER212/Video-Game-Sales-Analysis/assets/126152029/0552674c-94e0-44b6-8fe1-c027c464eaad)

#Global Sales Trend Over Time:

![7](https://github.com/SluggER212/Video-Game-Sales-Analysis/assets/126152029/b45e1212-76de-4cea-90f4-0602eced9700)

#Top Publishers by Global Sales:

![8](https://github.com/SluggER212/Video-Game-Sales-Analysis/assets/126152029/557b5d1b-54c3-4e95-b442-b05ad48a2d81)

#Conclusion:
Through this case study, we gain valuable insights into the video game industry's sales dynamics. It highlights the top-performing games, yearly trends, genre distribution, regional contributions, and the key players in the market. Such analyses can aid industry professionals, researchers, and enthusiasts in making informed decisions and understanding the evolving landscape of the video game market.

