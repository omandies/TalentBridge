# TallentBridge
Final project for the Building AI course (An **AI**_dea to find things to do between classes.).

## Summary
University students often have enough spare time between classes or on weekends to grow their personal and professional skills outside of campus. But how can we match their current expertise and free time schedule with the opportunities available in the city, considering the unavailability of full-time dedication?

## Background
Most universities offer their curriculums during the daytime, with classes taking up 50% to 60% of the week, leaving the rest of the time for extracurricular activities and/or leisure. According to the International Labour Organization (ILO) in 2024, the European continent has an average of 29.53 working hours per week (considering only Sweden, Norway, Germany, and Spain); the American continent averages 37.92 working hours per week (considering only the United States, Canada, Mexico, Colombia, and Argentina); and other countries average 38.60 working hours per week (considering Japan, Indonesia, and South Africa).

If we consider 50% of an average of 35.9 hours per week for all continents, we can say that 17.65 hours can be dedicated to other activities. Extending this to 12 hours a day, 6 days a week, the total available time increases to 54.35 hours per week. Imagine the economic opportunities a university, city, or country could unlock if all this spare time were used for unpaid jobs, beneficial activities, or simply volunteering. But how can we match students' free time and skills with the available opportunities?

The idea would be to create an algorithm, similar to the cabin example, that cross-references data on each student, such as age, gender, skills, field of study, and interests, with available opportunities. This would help find the best matches for students interested in occupying their free time with activities, whether at the university, in the city, in the country, or even internationally.

### Data
| Continent | Country | Average | Average of Man | Average of Women |
| ---       | --- | --- | --- | --- |
| America   |  | 37.92 | 38.70 | 34.10 |
|  | Argentina | 35.40 | 39.10 | 30.30 |
|  | Canada | 32.30 | 25.10 | 29.10 |
|  | Colombia | 42.60 | 45.00 | 39.00 |
|  | Mexico | 42.70 | 45.80 | 38.00 |
|  | United States | 36.60 | 38.50 | 34.10 |
| Europe |  | 29.53 | 32.23 | 26.48 |
|  | Germany | 29.70 | 33.40 | 25.40 |
|  | Norway | 27.10 | 29.70 | 24.30 |
|  | Spain | 32.10 | 34.40 | 29.40 |
|  | Sweden | 29.20 | 31.40 | 26.80 |
| Others |  | 38.60 | 41.43 | 35.00 |
|  | Indonesia | 37.40 | 39.20 | 34.80 |
|  | Japan | 36.70 | 41.30 | 31.10 |
|  | South Africa | 41.70 | 43.80 | 39.10 |
| **Grand** | **Total** | **35.29** | **37.23** | **31.78** |

## How is it used?
The algorithm would be installed locally and/or centralized to be accessed from different external sources, taking the form of a website to capture data with AI agent ready to help. Both students and/or companies can input the required information to nourish the data. Using an AI agent, the system would then query available options based on factors such as the season, study zone, living zone, working zone, and student information, including age, gender, skills, field of study, interests, and expertise (such as safeguarding, IT, spoken languages, sign languages, etc.).
Based on the recommendations, the student or interested might continue with the formal process to hire the resource available.

## Data sources and AI methods
### Data sources
- https://ilostat.ilo.org/
- https://worldpopulationreview.com/
- https://worldpopulationreview.com/country-rankings/average-work-week-by-country

### AI Methods
I believe that some of the best AI methods to make this idea possible would be the following, though not limited to them:
1. Collaborative Filtering with algorythm like KNN.
2. Content-Based Filtering with algorythm like Cosine Similarity, TF-IDF, or Neural Networks.
3. Clustering (Unsupervised Learning)  with algorythm like DBSCAN.
4. Classification (Supervised Learning) with algorythm like Decision trees or Neural Networks.
5. Natural Language Processing (NLP) with algorythm like BERT or TF-IDF.
     
## Challenges
### Accuracy
As explained and reinforced throughout the modules, the accuracy of the results depends 100% on the quality of the data. For this reason, how the data is captured, validated, and maintained is the biggest challenge of this project.

### Engagement
The other challenge is the adoption of the idea by the university itself or external entities willing to share their available opportunities. It also involves transforming their culture to a more flexible one, allowing for temporary workers and knowledge rotation. In other words, tailoring their processes to minimize the learning curve due to the high turnover of workers.

## What next?
This is just an “pasabocas” (spanish), “un apéritif” (french), an appetizer, of an idea. As any idea, following a strick order to make it possible is mandatory, such as:
1. Data
    a. Student data
    b. Opportunities data
2. Technical skills
    a. Data enginering
    b. Machine learning/AI
    c. Natural Language Processing
    d. Software Development
    e. Project management
3. Tools and libraries
4. Data provacy and ethics consideration
    a. User consent and privacy
    b. Bias and fairness
5. Collaboration with experts
6. Time and resource management
    a. Time
    b. Budget
7. Deployment and feedback loops for improvement

## Acknowledgments
The idea raises because my daughter, a student of second semester of physiotherapy at university of Sherbrook (Sherbrook-Quebec-Canada), posees several skills such as safeguard certified, first aid certified, she speaks three languages (English, Spanish, and French), knowledge in offimatic, and several other qualities, however, finding a non-qualified or qualified job use her free time in a productive way between classes or during the recesses has been an imposible task.
