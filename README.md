# NETFLIX Insights uing SQL and PowerBi Dashboard 
_________________________________________________________________________________________
Project description,functions,queries written,environment used are mentioned in readme.

# Netflix Data - Cleaning & Exploration
Removing and adding columns as necessary in the tables and preparing the database tables for Analysis. Data subset collected in SQL dump file and loaded to SQL server for exploring the data tables. Tables:
1. Netflix Titles.
2. List
3. Description
4. Direcctors
5. Country
6. Cast

# SQL queries for data cleaning and exploration
Data acquired is cleansed using SQL queries here 
https://github.com/kunal1300/Netflix_SQL_PowerBI_project/tree/868ca9a3696334134ec9fb771172af8e2ebf7dc8/Sql%20scripts






















### 1. Introduction 
_______________________________________________________

In this Project, I perform data analytics on Netflix data 

   - split Text to column 
   - Trim and separate Data
   - sort and filter Data
   - common Calculation (Sum,Avg,Max,Min)
   - Setup Relational Tables for BI with help of MySQL workbench
_____________________________________________________________________________________________________________

### 2. Technology 
________________________________________________________________
 - Programming language - SQL and Dax
 - Concept of SQL & DAX
 - MySQL workbeanch
 - PowerBI


## Data Used
The data used in this is open-source and contains all the information regarding Netflix, including 1 file with all the data regarding movies and TV shows. The data contains null values and then, it was sorted and extracted in different files with different fields of Casts, countries, Descriptions, Directors, Lists and Netflix fields. Then the file was  
modified into the MySQL workbench. The file was modified by combining all the data by using the Union function as well as creating a new file.


# To check out the Dashboard

![Netflixpage1](https://github.com/user-attachments/assets/f12de33b-001c-438d-aa89-7b62a49551ea)

Insight Description:

The image contains information about a Netflix movie titled **"A Very Murray Christmas"**. Here's a breakdown of the key insights from the image:

1. **Title of the Movie**:  
   - "A Very Murray Christmas"

2. **Rating**:  
   - TV-14 (suitable for audiences age 14 and older)

3. **Release Date**:  
   - 2015

4. **Short Film Description**:  
   - The film features **Bill Murray** rounding up an all-star cast for a night of music, mischief, and camaraderie in a comedic twist on traditional holiday variety shows.

5. **Category/Genres**:  
   - **Music & Musicals**
   - **Comedies**

6. **Director**:  
   - **Sofia Coppola**

7. **Countries Available**:  
   - Based on the map in the image, it appears that the movie is available in the **United States**.

8. **Type**:  
   - Movie

9. **Date Added on Netflix**:  
   - **04 December 2015**

10. **Cast**:  
    The cast includes several well-known actors and entertainers, such as:
    - **Amy Poehler**
    - **Bill Murray**
    - **Chris Rock**
    - **George Clooney**
    - **Maya Rudolph**
    - **Michael Cera**
    - **Miley Cyrus**

This movie is a festive holiday special blending comedy and music with an impressive ensemble cast under the direction of Sofia Coppola. In this insight you can get all the information from various categories of Movies and Tv-Shows.

__________________________________________________________________________________________________________________________________
![page 2](https://github.com/user-attachments/assets/e018d373-0edb-4052-81c1-d41b2a5f8153)

Insight Description:

The image provides data-driven insights about Netflix content, categorized in various ways. Here's a detailed analysis based on the charts displayed:

1. **Shows Added by Year (2012-2022)**:
   - The number of shows added each year (categorized by movies and TV shows) increases significantly starting around 2015.
   - The peak of content addition occurs around 2018-2020, after which it declines slightly.
   - Both movies and TV shows are steadily rising, but TV shows seem to have experienced a faster initial growth.

2. **Shows by Rating**:
   - The highest number of shows are rated **TV-MA** (Mature Audiences), followed by **TV-14** (suitable for 14+).
   - Other notable ratings include **TV-PG** (Parental Guidance), **R** (Restricted), and **PG-13**.
   - Lower-rated shows (G, PG, NR, etc.) make up a smaller proportion of the total.

3. **Popular Categories Around the World**:
   - The map shows the popularity of categories by region.
   - Significant concentrations of Netflix users are seen in **North America**, **Europe**, and **Asia**, with varying popularity of content types in different regions.
   - Major categories, both TV shows and movies, are consumed across the world.

4. **Total Number of Productions by Categories**:
   - **International Movies** lead in production volume, with around **2.6K** productions.
   - **Dramas** are the next most common, at **1.6K**.
   - Other popular categories include **Comedies** (1.2K), **Action & Adventure** (0.9K), **Documentaries** (0.8K), and **TV Dramas** (0.7K).
   - Romantic Movies are also a notable category, with around **0.6K** productions.

This data gives insights into Netflix’s content strategy and regional preferences, highlighting the growth in TV show production, especially in more mature-rated content like TV-MA and TV-14 categories. The production volume in categories like international movies, dramas, and comedies indicates a focus on diverse genres across different markets.

___________________________________________________________________________________________________________________________________________________________
![page 3](https://github.com/user-attachments/assets/bca320fa-4437-404b-bde8-d202ad385297)

Insight Description:

## Analyzing the Netflix Data Dashboard

**Overview**

The provided dashboard offers a comprehensive overview of Netflix's content library, focusing on the distribution of films, TV shows, and their production across various countries and months. 

**Key Findings**

### Content Production and Distribution

* **Total Content:** Netflix boasts a vast library with 8797 films and 29K cast members.
* **Geographic Diversity:** Content originates from 196 countries, showcasing a global reach.
* **Production Consistency:** 5116 directors have contributed to the platform's content.

### Monthly Content Trends

* **TV Shows:** December and July see the highest number of TV show releases, followed by September and August.
* **Movies:** July and April are the peak months for movie releases, with December and January following closely.

### Regional Trends

* **North America:** The map indicates a significant concentration of content production and distribution in North America.
* **Global Presence:** While North America dominates, the scattered distribution of markers suggests a global presence of Netflix content.

### Additional Insights

* **Data Visualization:** The use of bar charts and maps effectively communicates the distribution of content across months and regions.
* **Missing Information:** The dashboard could be enhanced by providing data on content genres, ratings, and viewership trends.

**Recommendations**

* **Genre Analysis:** Incorporate data on content genres to understand audience preferences and production trends.
* **Rating and Viewership:** Track ratings and viewership data to identify popular content and inform future programming decisions.
* **User Engagement:** Analyze user behavior to personalize recommendations and improve user experience.
* **Content Acquisition:** Explore opportunities to acquire content from emerging markets to expand the platform's global reach.
_________________________________________________________________________________________________________________________________________________________

![page 4](https://github.com/user-attachments/assets/26baf137-9729-48cb-b773-45fe1b00edb7)
## Analyzing the Netflix Top Producers and Actors Dashboard

**Overview**

The dashboard provides a detailed look at the top producers and actors involved in Netflix's content creation. It focuses on the number of films and TV shows each individual has contributed to.

**Key Findings**

### Top Producers

* **Film Production:** Rajiv Chilaka, Jan Suter, and Raúl Campos are the leading directors in terms of film production.
* **TV Show Production:** Alastair Fothergill, Ken Burns, and Gautham Vasudeva are the top directors for TV shows.

### Top Actors

* **Film Appearances:** Anupam Kher, Shah Rukh Khan, and Akshay Kumar have appeared in the most films.
* **TV Show Appearances:** Takahiro Sakurai, Ai Kayano, and David Attenborough are the most frequent actors in TV shows.

### Additional Insights

* **Data Visualization:** The use of bar charts effectively compares the contributions of different producers and actors.
* **Content Type:** The dashboard differentiates between film and TV show contributions, providing a comprehensive view.
* **Missing Information:** Data on the specific roles of actors and producers in each project could enhance the analysis.

**Recommendations**

* **Role Analysis:** Include information on the specific roles of actors and producers to understand their contributions in detail.
* **Collaboration Analysis:** Explore collaborations between producers and actors to identify successful partnerships.
* **Content Impact:** Analyze the impact of specific producers and actors on content popularity and viewership.
* **Emerging Talent:** Identify emerging talent and support their growth to foster a diverse and innovative content ecosystem.

_____________________________________________________________________________________________________________________________





