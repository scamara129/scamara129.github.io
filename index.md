## Portfolio

---

### About Me

[Go to Projects](#projects)

Hi! My name is Shanley Camara and I am an early career data scientist/data engineer based out of New Hampshire. I graduated summa cum laude from University of New England in May 2022 with a Bachelor's of Science in Data Science and a minor in Biological Sciences with a 3.98 GPA. Through my academics I have loved learning about machine learning and AI, learning new programs and tools for data analysis and visualization, and finding ways to intersect data science with biological sciences. I am always eager to continue learning even after completing my formal education by keeping up with new technologies in the data science world.

A passion for data analysis and visualization lead me to specialize in Geospatial Information Systems (GIS) in my early career, starting with a GIS internship and continuing as a Geospatial Data Engineer. These professional opportunities have allowed me to gain a lot of experience in data gathering, data wrangling, and database management with SQL in the unique and highly visual subset of spatial data. In my time with Maprisk, acquired by Insurity, I became an integral part of the team by taking on large data gathering and data wrangling projects, improving data quality assurance practices, improving database management practices by writing queries, writing detailed documentation, and assisting in customer requests and communication all while working remotely with minimal supervision. 

Now for the fun stuff: hobbies and interests. I am an avid animal lover (pet pictures always acceptable), fabric art creator, painter, video game enthusiast, skier, hiker, and powerlifter. Knitting in particular is my favorite art, which is something that I picked up in college and even co-founded and was president of a fabric art club for knitters, crocheters, and people who wanted to learn. I love being able to use my creativity to design and make cozy wearable pieces. Being a New Hampshire resident means that I have access to some beautiful places to ski and hike, and these have ignited a passion for physical fitness. These things have taught me consistency, diligence, and a willingness to learn are all important aspects of both your professional and personal life.

Scroll down to see some examples of my work. If you would like to connect please feel free to reach out to me at shanleycamara@gmail.com or add me on [LinkedIn](https://www.linkedin.com/in/shanley-camara).

---

### Projects

#### [Spotify Recommendation System](https://github.com/scamara129/song_recommendor)
This project uses Python to create a Spotify recommendation system by comparing cosine similarity of an input song and all tracks found in this [1.2+ million song dataset](https://www.kaggle.com/datasets/rodolfofigueroa/spotify-12m-songs?reso=) from Kaggle. Clustering, an unsupervised machine learning algorithm, is utilized to reduce the processing time of this system by only comparing the input song to other songs within its cluster. I was inspired to create this to find new songs based on a song I like that is independent from artist or genre, and instead base recommendations on song composition metrics provided by Spotify's API. Some of these metrics include danceability, energy, valence, etc. that may be able to quantify the overall "vibe" of a song. This was a fun project because I got to explore some of Spotify's open developer tools like Spotify for Developers, Spotify API, and the Python package 'spotipy', and listen to some fun new songs that I may not have found otherwise.
- To see the source code and results, go to the [GitHub Repository](https://github.com/scamara129/song_recommendor)
- Skills: Python (pandas, numpy, sklearn, matplotlib), machine learning (unsupervised, clustering), data visualization, data exploration

<p float="left">
  <img src="images/spotify2.png" height = "150" />
  <img src="images/clusters_10.png" height = "150" />
</p>

#### [Broadband Usage Modeling](https://github.com/scamara129/broadband_usage)
Internet accessibility in the United States is greatly important for people to thrive in our society. Many rural communities may not even have internet services available at all, let alone the ability to pay and access those services at high speeds. Broadband allows people to access the internet at much faster speeds than other more outdated methods and is accessible at any time. In this project I examined broadband availability and usage by county across the United States, and then predicted broadband usage based on county census data using several machine learning techniques. Features used to predict broadband usage include broadband availability, county population, unemployment rate, percent without health insurance, poverty rate, percent receive SNAP, percent without computer, and percent without internet.
- To see source code and results, go to the [GitHub Repository](https://github.com/scamara129/broadband_usage)
- Skills: R (tidyverse, caret), machine learning (supervised, regression, linear regression, knn, elastic net, pcr), data cleaning, data wrangling, data visualization, data exploration

<p float="left">
  <img src="images/broadband_hist.png" height = "150" />
  <img src="images/broadband.png" height = "150" />
</p>

#### [Marine Biodiversity in the Gulf of Maine](https://arcg.is/8KP1L)
The Gulf of Maine is a particular point of interest when it comes to maintaining marine biodiversity. Through this ArcGIS Story Map, I explore the importance of biodiversity in conserving our ecosystems, the species richness and rarity in the Gulf of Maine, and the current government protections in place to conserve species in the Gulf of Maine. 
- To view the Story Map visit [https://arcg.is/8KP1L](https://arcg.is/8KP1L)
- Skills: GIS (ArcGIS, Story Maps), story telling with data

<p float="left">
  <img src="images/marine_biodiversity.png" height = "150" />
  <img src="images/marine_legend.png" height = "150" />
</p>

#### [Game of Thrones: A Combinatorial Game Using Graph Theory](https://github.com/scamara129/game_of_thrones)
A combinatorial game is a game in which there is no randomization (like dice or flipping a coin) and in which there is perfect information, meaning that both players know everything about the state of the game. A combinatorial game played on graphs refers to the pair-wise mathematical structure that represents relationships between objects, typically represented by vertices (the objects) and edges (lines that connect the objects.) 

The Game of Thrones is a combinatorial game played on a type of graph called a tournament. A tournament is a graph in which every pair of vertices is connected by an edge *and* every edge has a direction (i.e. point A is directed towards point B.) These are also called completed directed graphs or digraphs. Following the JavaScript code in [Trevor???s William???s 2017 dissertation](https://digitalcommons.usu.edu/cgi/viewcontent.cgi?article=7649&context=etd), I was able to recreate his tournaments applet in GeoGebra. It takes in a binary string that represents the adjacencies of the upper triangle of a tournament and creates a tournament that can show/hide any kings. This applet can help you find where the kings are in a game and when in edit mode, you can manually delete vertices to play the game. 
- Read *How to Play* in the README.md file on this [github repository](https://github.com/scamara129/game_of_thrones)
- To use the GeoGebra applet, visit [https://www.geogebra.org/m/gfc8v9dz](https://www.geogebra.org/m/gfc8v9dz)
- Skills: JavaScript, GeoGebra, combinatorics, graph theory, game theory, communication

<img src="images/game_app.png" />

#### Geospatial Solutions in the Property and Casualty Insurance Industry Poster
In October 2022 I had the opportunity to help present a poster at the Maine GIS User Group (MEGUG) annual meeting. With the Data team at Insurity, we created a poster presentation giving a brief overview of how we use geospatial data in our work and in the insurance industry. Our poster presentation was voted Best Poster in the professional category. 

'Insurtech' is a portmanteau that describes the relatively new movement within the insurance industry to prioritize technology and data to improve processes and profit. Geographic Information Systems (GIS) and spatial data can provide invaluable insight into property and casualty (P/&C) insurance underwriting and risk management. Improvement the databases analyses that form the foundation of P/&C insurance can affect policy-writing decisions and insurance premium costs. Additionally, geospatial data analysis may help insurers navigate current issues such as climate change.
- To view LinkedIn post about the poster, visit [here](https://www.linkedin.com/posts/spring-beinema-332a85b0_a-little-over-a-week-ago-i-had-the-opportunity-activity-6995139280561979392-6nda?utm_source=share&utm_medium=member_desktop)
- Skills: GIS, technical writing, communication
<img src="images/insuretech_poster.jpg?raw=true"/>

---

