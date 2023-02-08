| [home page](https://cmustudent.github.io/tswd-portfolio-templates/) | [visualizing debt](visualizing-government-debt) | [critique by design](critique-by-design) | [final project I](final-project-part-one) | [final project II](final-project-part-two) | [final project III](final-project-part-three) |

# Critique by Design Assignment: improvement on "Confirmed COVID–19 cases last week vs the week before"
## the original design
- source: https://blog.datawrapper.de/coronaviruscharts/ -> find the graph"Confirmed COVID–19 cases last week vs the week before"->click edit the chart ->go back to step 1->download the dataset or download directly from here: https://static.dwcdn.net/data-feed/coronavirus/summed-up_seven.csv?ah
- the source of the source/ original data source: https://github.com/CSSEGISandData/COVID-19

<img width="690" alt="Screen Shot 2023-02-06 at 11 10 25 PM" src="https://user-images.githubusercontent.com/93154040/217379395-db3b7371-1669-4674-940e-b70523b27331.png">

This table compares the new reported COVID–19 cases in the last seven days (between 8 days ago and yesterday) with the new reported cases in the seven days before that, and reveals which country has the most deathes in this period. 
### Problem with this original visulization: 
- **Informative**: The original graph just have too much information to follow, if we only speak from the perspective of informative, the graph definitely provides tons of information
- **Usefulness**: assume the target audience is scholars who study for covid, the trend maybe very usesul. 
- **Completeness**: the graph did have all the element of a completing setting. Although it was very hard to understand, but if you read closely, you will understand the points that author want to make 
- **Perceptibility**: very low given too much information 
- **Truthfulness**: given the data source is from JHU, it's a truthful data
- **Intuitiveness**: the intutiveness of this graph is very low because it has too much information such that it's hard to understand which point does the author want to enphasize 
- **Aesthetics**: limited colors are used here, thus the Aesthetics is poor. 
- **Engagement**: due to too much information, low enegagment could be scored to the graph. 
## Redesign process: 
given the evaluation above, we need to change the following perspective of the original design, which are **Informative**, **Usefulness**,**Perceptibility**,**Intuitiveness**,**Aesthetics**,**Engagement**. such that a simpler design could be implemented. To achieve this goal, I will delete the last 3 columns: change, total confirmed case, and the case on yesterday. To make the contrast between "this week" and "the week before", I will use bar graph to emphasize the contrast on number. Also, I will change the order of the graph, rank the death from the highest to lowest in order to make the contrast more obvious. I will also change the color to increase aesthetic. Originally, only grey is used here, thus decreasing the aesthetics. The last thinng I will change is to empathize japan instead of other countries: here is the reasoning: if the target audience is sholars who study for covid trends in general, only empathize on Europe is usefullessness. which is to say if the sholar only want to study european countries, there is no need to list other countries. Thus, in order to have a global view, i recommand to emphasize Japan.
## Sketch and feed back 
![IMG_0249](https://user-images.githubusercontent.com/93154040/217387945-5a13ace3-f4e5-495d-9e6f-fa893bd1e4c7.jpg)

### Interview with different people 
- Can you tell me what you think this is? 

**A: Male, mid 20s**: it had a informative title that reveals trend of Confirmed COVID–19 cases last week vs the week before. Also the graph reveals that Japan has the most death this week and the week before.

**A: Female, mid 20s**: it had a informative title that reveals trend of Confirmed COVID–19 cases last week vs the week before. Also the graph reveals that Japan has the most death this week and the week before.
  
- Can you describe to me what this is telling you?

**A: Male, mid 20s**:that Japan has the most cases  this week and the week before, also reveals that Japan has the most cases among major countries worldwide

**A: Female, mid 20s**: that Japan has the most cases  this week and the week before, also reveals that Japan has the most cases among major countries worldwide, but if you add another date that will be helpful 

- Is there anything you find surprising or confusing?

 **A: Male, mid 20s**:no. it is supreise that Japan has more cases than US (it turns out I made a mistakes that label the "total cases" into "total death cases")
 
 **A: Female, mid 20s**: No. 

- Who do you think is the intended audience for this?

 **A: Male, mid 20s**:people who want latest info of covid-19, probably scholars who study this. 
 
 **A: Female, mid 20s**: people who need latest data about covid-19 cases confirmation. 

- Is there anything you would change or do differently?

 **A: Male, mid 20s**: use more color and make the number stand out. 
 
 **A: Female, mid 20s** delete the grid line and highlight the labels to make it more good looking. 
 
 ### concusion
 Both interviewees think that my title/subtitle is informative enough. In order to increase engagmenet and asetetics, I should use slightly more color and make the whole graph more consise. It's also an interesting fact that the female is tend to focus on asthetics and detail a little bit more. I also even redesign another legend to make things stands out. 


## Rebuild
here is my final version of the rebuid. I use the same data source, while only keep the cases this week and last week. Two different color scheme is used here. I used pure red to make Japan stand out while using another lighter color sheme for other countriees. I also add the specific date on the title and subtitle to make things more clear. I also delete the grid line to make things more clear and consise. 
 **there are a pattern that I want to achieve but flourish does not allow me to do so ** : if I could add a small label on the first bar indicates that's the new case and a label for the second bar, that would be great. however, I can not add that. It's lucky that the interactive feature would provide label for the second bar and the first bar though. 

<div class="flourish-embed flourish-chart" data-src="visualisation/12667095"><script src="https://public.flourish.studio/resources/embed.js"></script></div>

