# Netflix Data Analysis
 ![image](https://github.com/anugyaram/Netflix_Dashboard/assets/51700491/5b347bad-0d86-43e3-8ea5-4d7f16bb13a6)

## Introduction:
Netflix, a global entertainment giant, boasts 158 million paid memberships across 190 countries, offering a vast array of content, including TV series, documentaries, and feature films. Originating from a DVD rental service in 1997, Netflix's meteoric rise now sees over 8,000 titles captivating a user base of 200 million subscribers as of mid-2020.

This visualization project explores Netflix's expansive dataset, focusing on geographic distribution, temporal trends, and content popularity, unveiling insights into its unparalleled success and cultural impact since entering the streaming market in 2007.

## Data Source:
The dataset used in this project is taken from Kaggle: [click here](https://www.kaggle.com/datasets/shivamb/netflix-shows?resource=download)

## Data Description:
Our data universe comprises 12 columns, revealing the essence of movies and TV shows:
1.	Show ID: Unique identifier
2.	Type: Movie or TV show
3.	Title: Name of the show
4.	Director: Name of the directors
5.	Cast: Name of the lead cast
6.	Country: Countries where the show is released
7.	Date: Date of show release
8.	Release Year: The year the show was added to Netflix
9.	Rating: Show rating
10.	Duration: Duration of the show in minutes
11.	Description: Brief overview of the show
12.	Genre: Category to which the show belongs

## Data Cleaning & Transformation:
To optimize the data visualization process, a thorough cleansing was performed. Superfluous blank columns and rows were systematically eliminated through filtration. The segmentation of countries into distinct cells was implemented, enhancing Power BI's ability to efficiently detect and process country-specific data, resulting in more accurate and meaningful outputs.

![image](https://github.com/anugyaram/Netflix_Dashboard/assets/51700491/99bbb532-5d99-4edc-9165-bbe71b7646e2)

## Data Analysis
### 1.	Timeline Distribution
This interactive dashboard illustrates Netflix's remarkable growth over the years. It features an area chart and filters for easy exploration. Showtime soared, with movies up by an astounding 59,600%, and TV shows by an impressive 30,200% from 2008 to 2021. Since 2015, movies experienced a dazzling 1,143.75% spike. Netflix's global expansion post-2015 led to availability in 190+ countries by 2016. However, the post-2019 pandemic period marked a downturn in both movies and TV shows.

![image](https://github.com/anugyaram/Netflix_Dashboard/assets/51700491/418e1225-71ec-449a-8e65-e52f71e5c8e2)
 
### 2.	Global Shows Distribution
This dashboard focuses on Netflix's global impact, utilizing a Map chart to showcase content distribution across countries. The United States emerged as a movie hub, contributing 29.62% of total Movie content. Movies dominate with a higher count (5,685) than TV shows (2,282), emphasizing their supremacy. On average, each country boasts a richer library of Movies (72.88) compared to TV Shows (39.34), reflecting the global preference for cinematic content.

![image](https://github.com/anugyaram/Netflix_Dashboard/assets/51700491/8084ac6f-4b6b-4c60-a43a-a813c7a32d32)
 
### 3.	Netflix Showcase India
This comprehensive dashboard provides a detailed analysis of Netflix's presence in India, showcasing the distribution of Movies and TV Shows, their temporal evolution, rating distribution, and a comprehensive table. 

The pie chart highlights movies' dominance at 91.96%, totaling 927 shows compared to TV shows' 81. 

The area chart illustrates a substantial increase of 672.73% in movies and 7.14% in TV shows from 2016 to 2021. The data also reveals varying trends in movies added to Netflix annually, with a notable surge from 2016 to 2018, followed by a subsequent decline. In contrast, TV shows exhibit relatively consistent numbers over the same period.

The bar chart highlights that TV-14-rated (unsuitable for children under 14 years) movies constitute a significant portion at 53.47%. Additionally, the average count indicates a preference for movies (92.70) over TV shows (13.50).

![image](https://github.com/anugyaram/Netflix_Dashboard/assets/51700491/0753341d-ca44-4120-a1d5-52a6f94950dc)
 
## Summary
The Netflix data lake stores vast information, and my analysis focused on user patterns and content trends across countries.

In 2019, Netflix witnessed a spike in content additions, with the United States and India leading. However, 2020 saw a notable drop in new additions. Despite a historical focus on movies, Netflix's recent emphasis on TV shows is evident.

The United States dominates Netflix content, while India follows closely, emphasizing the platform's global appeal. India leans towards movies, South Korea favors TV shows, and Australia showcases a balanced content mix.

The dashboard delivers a detailed picture of content distribution, illustrating regional preferences and guiding content decisions for various countries and industries. Netflix's evolving strategy, showcased in the data, aligns with the platform's commitment to meeting diverse viewer demands.

