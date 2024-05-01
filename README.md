[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-24ddc0f5d75046c5622901739e7c5dd533143b0c8e959d652212380cedb1ea36.svg)](https://classroom.github.com/a/9bMXU1P_)


Dataset website: https://www.kaggle.com/code/tayyarhussain/netflix-popular-movies-data-analysis

# Final Project Proposal

Please complete your proposal following the outline below.

## Project title

Analyzing TV Shows and Movies on Netflix Based on Popularity

Give your project a concise, interesting title that summarizes the entirety of your project. (Your title can change on subsequent deliverables.)

### Authors
- Jolie Sim (jsim19@uw.edu)
- Yuvika Verma (yverma@uw.edu)
- Najat Alnuaimi (najatn@uw.edu)

### Date

Spring 2024

## Abstract

The focus of our project is to see how COVID-19 influenced the popularity of various Netflix shows and movies because we would like to see how viewer engagement was during a pandemic and what was trending and valued at that time. To address the question, we will use a dataset containing information about various Netflix shows and movies to analyze their IMDb ratings and see what genres were trending at the time. One thing we need to be mindful of during this project is knowing that IMDb ratings doesn't provide a complete picture of viewer engagement with each content, as this is only one metric to gauge a specific content's popularity. 

No more than three sentences that summarize your project. Focus on the very most important aspects. For example: (1) "Our main question is .... This question is important because .... To address the question, we will ...." (2) "We are concerned with ..., because .... To address this concern, we plan to ...." (3) "Consider that .... This is important because .... Accordingly, we plan to ...."

## Keywords

movies and tv shows, ratings, Netflix, popularity

3-5 keywords that summarize your project.
(e.g., "Keywords: human physiology; bicycle exercise; Gen Z; times-series data")

## Proposal

1. Introduction  

During the Covid-19 pandemic, every aspect of life was different: more people stayed at home, companies shut down, and others thrived. While absolute necessities such as the food and health industries represent some of the most notable high-demand work at the time, overall, many industries presented noticeable differences in production between the years of 2019-2021 regardless of popularity. With this in mind, our group is interested in making observations of how the Covid era may have impacted the popularity of Netflix shows and movies, as lockdown forced many to stay to spend extended time inside. Does the release year of a show or movie affect the popularity (IMDb rating) of the media? Specifically, do shows/movies released from 2019-2021 have higher ratings compared to media released at other times? Do they typically have more votes by the public in general? Were different ratings of movies (PG, MA, R, etc.) more popular during Covid and did a certain group of them receive higher ratings (scores)? What does this say about who was most involved with Netflix consumption and what shows/movies were most popular during the pandemic? Considering Netflix is such a popular streaming platform that not only displays new movies but creates their own Netflix-branded content, we are motivated to delve into such a complex platform. Through this class we have learned the significance of data analysis, and have come to understand that everything is data that can be analyzed. Furthermore, as frequent Netflix users ourselves, we are inspired by what correlations we can observe from data that we use every day and do not typically think about as "data". With normality resuming around the world and streaming platforms becoming more mainstream in general, we find that it is important to understand patterns in popularity of media to accurately form predictions as to what types of content will be best perceived in the future.

> Briefly introduce your project.  Include 3-5 research questions. What motivates the questions? Why are they important? (at least 200 words)

2. Related Work  

The streaming platform of Netflix is a staple in many people's lives. With it's diverse selection of TV shows and movies, viewers are able to find content within any genre they are in the mood for. When gathering data, patterns such as type of show/movie and genre can then reflect current trends in society, whether that is what audiences are currently resonating with, or possibly greater representations of what is going on in the world. With Covid, it is harder to decipher what exact genres were popular during lockdown as essentially everyone was at home watching. Hence, the general audience grew. Many articles delve into the driving reasons for this, whether it be because we are missing out on daily activities, or because there are simply less things to do. In a [2020 Forbes article](https://www.forbes.com/sites/danafeldman/2020/12/10/netflix-allowed-us-to-escape-2020-at-home-in-lockdown-heres-what-the-streamer-says-we-watched/?sh=13ef8a3b1d2d) for instance, the author Dana Feldman expands on this topic as she dissects some of the most notable things that Covid took away from our daily lives. For example, Covid lessened dating and our sense of routine. Feldman then uses theses issues to explain some of the most popular shows that year, such as the rise in popularity of dating shows and the increase in family show viewers. On the other hand, different research focuses more on the cognitive and behavioral tendencies we have as humans that draw us to watching more media. For example, a [study published by the Technology in Society journal](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC8437809/) analyzes the concept of increased TV viewership due to desire for communication. The authors of this study, a group of researchers from the University of Central Florida, Ohio State, and Cal Poly SLO, explain that humans are social creatures and want to have something to talk about and to connect with others on, which is one reason why we watched more TV during Covid. Finally, a third perspective offered in this work is looking at how Netflix subscription numbers are affected post-pandemic. In a [Guardian article](https://www.theguardian.com/media/2021/apr/20/netflix-records-dramatic-slowdown-in-subscribers-as-pandemic-boom-wears-off), the author notes how Netflix subscriptions have dropped dramatically by the middle of 2021. In relation to our intentions for this project, this explains a lot about increased trends in media consumption during the pandemic itself, just as we predicted. This offers an interesting alternative perspective that helps articulate how drastically the pandemic affected Netflix usage.
- Citations:
  - Feldman, Dana. "Here’s What We Watched On Netflix In 2020 To Escape The Pandemic." Forbes, 10 Dec. 2020, www.forbes.com/sites/danafeldman/2020/12/10/netflix-allowed-us-to-escape-2020-at-home-in-lockdown-heres-what-the-streamer-says-we-watched/?sh=13ef8a3b1d2d.
  - Kim, Jihyun, et al. "Social TV viewing during the COVID-19 lockdown: The mediating role of social presence." Technology in Society, vol. 67, Nov. 2021, https://doi.org/10.1016/j.techsoc.2021.101733.
  - Rushe, Dominic. "Netflix records dramatic slowdown in subscribers as pandemic boom wears off." The Guardian, 20 Apr. 2021, www.theguardian.com/media/2021/apr/20/netflix-records-dramatic-slowdown-in-subscribers-as-pandemic-boom-wears-off.



> Describe your topic and related work in this space. You must include 3 citations to related work (URLs to similar work, high quality articles from the popular press, research papers, etc. ) Please use a standard citation style of your choice. (at least 200 words)

3. The Dataset

- Where did you find the data? Please include a link to the data source
Our primary dataset for this analysis was sourced from Kaggle, a platform well-known for hosting diverse and comprehensive datasets for analytical competitions and research. The specific dataset can be accessed at(https://www.kaggle.com/code/tayyarhussain/netflix-popular-movies-data-analysis).

- Who collected the data?
The data was collected by Kaggle user Tayyar Hussain, who aggregated it to facilitate data analysis projects related to streaming content on Netflix. The dataset compilation involved automated scripts to extract data from public databases such as IMDb, as well as with Netflix's publicly available information on their titles.

- How was the data collected or generated?
The dataset on popular movies and TV shows on Netflix was collected using automated data scraping techniques, targeting publicly available sources such as IMDb and Netflix's own platform. Scripts were utilized to extract a variety of data points, including titles, release dates, genres, and viewer ratings. Following extraction, the data underwent a cleaning process to ensure its accuracy and usability, which involved tasks like removing duplicates and correcting errors. 

- Why was the data collected?
This dataset was collected mainly to provide insights into the popularity metrics of movies and TV shows available on Netflix, measured through IMDb ratings and audience engagement statistics. Such datasets are important for understanding consumer behavior in the media consumption sector and for academic purposes in data science and analysis courses.

- How many observations (rows) are in your data? 
The dataset contains 9957 observations, representing different titles on Netflix.

- How many features (columns) are in the data?
The dataset on popular movies and TV shows on Netflix contains 9 features (columns). These features include critical information such as title name, release year, genre, IMDb rating, duration, cast, description, and other relevant attributes that help in analyzing the popularity and viewer engagement with the content on Netflix.

- What, if any, ethical questions or questions of power do you need to consider when working with this data? 
When working with a dataset that includes popular movies and TV shows on Netflix, it's important to consider various ethical questions and power dynamics. Privacy concerns are crucial, ensuring that no personal viewer information is indirectly revealed, in compliance with regulations like GDPR or CCPA that protect user data. The dataset's potential bias towards English-speaking and Western-centric content raises issues about cultural representation and the perpetuation of cultural dominance. This highlights the responsibility of handling data in a way that avoids influencing public opinion or promoting certain types of content unfairly. Also, there are ethical considerations regarding the commercial exploitation of data analysis, where findings could drive targeted advertising or influence Netflix’s content creation strategies, potentially leading to a homogeneous media landscape that might not reflect diverse societal needs. The power to influence content trends can cause creativity if only certain genres are favored. Finally, ethical analysis should consider who has access to this data and who benefits from the insights, ensuring equitable access among different producers and creators, thereby addressing potential power imbalances within the industry. These considerations call for a careful, responsible approach to data analysis and interpretation, ensuring outcomes are not only technically sound but also ethically justified and socially responsible. 

- What are possible limitations or problems with this data?   (at least 200 words)
The dataset focusing on Netflix's popular movies and TV shows, primarily derived from IMDb ratings, presents several limitations and potential problems that could impact the validity and generalizability of research findings. One significant limitation is the dataset's inherent bias towards Netflix-specific content, excluding titles from other streaming platforms like Amazon Prime or Hulu, which may lead to an incomplete picture of global streaming preferences. Moreover, the content is likely leaned towards English-speaking and Western-centric audiences, potentially overlooking diverse viewer habits in non-Western regions. Another critical issue is the reliance on IMDb ratings as a primary measure of popularity. These ratings can be biased, reflecting the preferences of a demographic that is more likely to rate content on IMDb, typically younger, internet-savvy viewers who do not represent the entire spectrum of Netflix's audience. This bias could distort findings, especially in understanding broader viewer preferences and behaviors. Additionally, the dataset may suffer from data completeness issues, lacking crucial variables like marketing efforts, budget allocations, or detailed viewer demographics such as age and geographic distribution. These omissions can lead to an oversimplified analysis that fails to capture the complex factors driving a show's or movie's popularity. Temporal and sampling biases present notable issues; the dataset could disproportionately represent certain times, such as more recent years where data collection methods are typically more advanced. Such biases could affect analyses of trends, particularly when assessing the effects of specific occurrences like the COVID-19 pandemic. Additionally, if the dataset mainly consists of highly rated or popular titles, it might introduce a sampling bias that depicts an overly favorable view of Netflix's catalog, thereby restricting the applicability of the findings to the broader range of available content. Having these limitations makes it necessary to adopt a careful analytical approach, using statistical methods to address biases and ensure the reliability of the findings derived from this dataset.

4. Implications

Data and insights from this project could help technologists as it could inform data scientists and streaming platform developers about the shifts that occur within consumer preferences during times of crisis such as COVID-19. By seeing the trends between release years and content genres with viewer ratings and engagement can help in improving recommendation algorithms. Additionally, these findings could help platforms, such as Netflix, to adapt their content strategies in response to changing viewer engagements. Designers can utilize the insights to upgrade the presentation of various content on streaming platforms. For instance, highlighting popular content from different time periods can help enhance user engagement and satisfaction. Policymakers can benefit by making informed decisions regarding content creation, distribution, and regulation. The insights can help them support the production of content that the audience feels most connected to, especially during challenging times. It can also inform decisions around various media consumption habits and the impact it can have on mental health. Policymakers can implement guidelines in order to promote balanced content consumption habits.

> Assuming you answer your research questions, briefly describe the expected or possible implications for technologists, designers, and policymakers. (at least 150 words)

5. Limitations & Challenges

Some challenges that might need to be addressed with our project idea include data quality, knowing the difference between causation and correlation, being mindful of sampling bias, and accurately interpreting ratings. One major challenge includes accessing reliable and extensive data on Netflix shows and movies, which includes information such as viewer demographic, release dates, and IMDb ratings. By having limited access to this kind of data or inaccurate information could make it hard to have an accurate analysis. Additionally, when finding the trends between the release year of a specific content and how popular it was during COVID-19, it's hard to establish causality with that information. This is because there are other factors that could influence viewer ratings and engagement, such as production quality and marketing efforts. A potential limitation that could occur with this project idea is having sampling bias, especially if the dataset consists mostly of well-known Netflix titles. This can result in skewed results, which can limit the generalizability of our analysis to a broader range of content. Lastly, being mindful that IMDb ratings is only one way to gauge viewer popularity and doesn't fully capture the entire spectrum of viewer preferences. Therefore, it's important to include other viewer engagement metrics that can help provide more insights and further strengthen the analysis.

>What challenges or limitations might you need to address with your project idea more broadly? Briefly discuss. (at least 150 words)

Acknowledgements

We would like to thank our Teaching Assistant Kiyomi Komatsu, who provided us various links to find our dataset as well as potential ideas for our project. 

> Is there anyone you would like to thank? A librarian who helped you with your research? A Teaching Assistant? A friend who helped you find your data? Say thank you in this section.
