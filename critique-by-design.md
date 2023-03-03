| [home page](https://sammijiang.github.io/tswd-portfolio/) | [visualizing debt](visualizing-government-debt) | [critique by design](critique-by-design) | [final project I](final-project-part-one) | [final project II](final-project-part-two) | [final project III](final-project-part-three) |

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
##  Questions to answer: 

**Describe your overall observations about the data visualization here.  What stood out to you?  What did you find worked really well?  What didn't?  What, if anything, would you do differently?**

Although the graph provides a summary of covid-19 death data for a group of countries and interesting icons, the graph gave too much information on the countries’ covid-19 death data. I really like the idea that how the author uses country icon to represnts counrty, that is fun to read. I also like how author put explanation on the text below title, make it a little bit more easier to understand (still not clear though). Things doesnt’t work out is listed below: 1. Too much information on death, don’t know which column to follow(not informative, and easy for readers to lose engagement). If we want to compare the dealth condition this week and the week before, why we need total death and death yearestday? 2. Why we are highlighting europe? Also if we want to emphasize on Europe condition, we could highlight the entire roll rather than the first column. Also the column is highlighted very lightly, and it’s actually really hard to track. There are something I could done differently: 1. I will change the title and the sub title to something shorter but more informative. 2. I will get rid of the last three columns: change, total confirmed case, and the case on yesterday. 3. In order to compare the last 2 weeks death, I will use other tables to do a more informative visualization. In conclusion, 
The data visualization is not highly informative, as it presents too much information and makes it difficult to follow and understand. The perceptibility is poor, as the layout is cluttered and the only color used is gray, making it hard to track and compare the data. The truthfulness of the data is not called into question, but the presentation of it is not intuitive, making it harder for the audience to understand. The emotive aspect is not considered, as the visual is mainly focused on presenting the data in a clear manner. The aesthetics could be improved, with the recommendation to use a bar chart and improve the color scheme to better highlight European countries. Finally, the engagement with the audience is limited, as the presentation does not effectively convey the information (too much information thus hard to track ).

**Who is the primary audience for this tool?  Do you think this visualization is effective for reaching that audience?  Why or why not?**
The primary audience for this visualization would be people who still care about the pattern of COID-19 death. The visulization will not be effeive for reaching out the audience becasue people who study covid-19 nowadays are scholars who still care about covid such that they want to understand the data as concise as possible, as a result, they are chasing for a visualization with good truthfulness,engagement and poor Perceptibility. Since the data source is realizable, I don’t worry about the truthfulness. However this visualization is not concise in a way that it has too much information and the pattern is not clear revealed. If we could design a view that concisely convey the information, it will be more efficient for the audience. In conclusion, due the aspect I mentioned above, poor engagement and poor Perceptibility are main reasons why this graph is doing a bad job when conveying information.  In conclusion, In summary, the COVID-19 death data visualization is intended for individuals interested in the patterns of COVID-19 deaths. Despite the reliability of the data source, the visualization falls short in its effectiveness due to several factors. The visualization is not concise and the pattern is not easily revealed, leading to poor perceptibility and engagement for the intended audience. The layout and color scheme also lack aesthetics, further reducing the overall engagement of the visualization. To improve its effectiveness, a more concise and intuitive visualization with improved aesthetics is needed to clearly convey the information to its intended audience.

**Final thoughts: how successful what this method at evaluating the data visualization you selected? Are there measures you feel are missing or not being captured here?  What would you change?  Provide 1-2 recommendations (color, type of visualization, layout, etc.)**
I think this scheme is very good at evaluating the data visualization. It’s a comprehensive model that capture all the aspects of a visualiztaion. But the color would be another concerns: the only color used in the original graph is grey. However the author also said they want empasize  European countries, only highlight the first column is not useful at all; Also the layout could be improved, we could find a more concise way of drawing the graph using bar chart. Using 4 columns to design the layout is not wise. All in All, the visualization can be improved by using a more intuitive layout, incorporating a more aesthetically pleasing color scheme, and simplifying the information to make it more concise and easier to understand. Additionally, using a bar chart visualization instead of a table may also help to clearly reveal the pattern of the data.

## Redesign process: 
given the evaluation above, we need to change the following perspective of the original design, which are **Informative**, **Usefulness**,**Perceptibility**,**Intuitiveness**,**Aesthetics**,**Engagement**. such that a simpler design could be implemented. To achieve this goal, I will delete the last 3 columns: change, total confirmed case, and the case on yesterday. To make the contrast between "this week" and "the week before", I will use bar graph to emphasize the contrast on number. Also, I will change the order of the graph, rank the death from the highest to lowest in order to make the contrast more obvious. I will also change the color to increase aesthetic. Originally, only grey is used here, thus decreasing the aesthetics. The last thinng I will change is to empathize japan instead of other countries: here is the reasoning: if the target audience is sholars who study for covid trends in general, only empathize on Europe is usefullessness. which is to say if the sholar only want to study european countries, there is no need to list other countries. Thus, in order to have a global view, i recommand to emphasize Japan.
To make the graph more vivid, I also added another tree map to empahzie the case on yerestoday to add more additional information if needed. 
## Sketch and feed back 
![IMG_0249](https://user-images.githubusercontent.com/93154040/217387945-5a13ace3-f4e5-495d-9e6f-fa893bd1e4c7.jpg)

![IMG_58F4D3009819-1](https://user-images.githubusercontent.com/93154040/217415427-f06cbb1a-1c62-47a3-b9fa-b6d9936f2ca2.jpeg)


### Interview with different people 
- Can you tell me what you think this is? 

**A: Male, mid 20s**: it had a informative title that reveals trend of Confirmed COVID–19 cases last week vs the week before. Also the graph reveals that Japan has the most death this week and the week before. The tree map's title is not informative enough, I think you'd better change it to the total case of COVID-19 would be helpful 

**A: Female, mid 20s**: it had a informative title that reveals trend of Confirmed COVID–19 cases last week vs the week before. Also the graph reveals that Japan has the most death this week and the week before.
  
- Can you describe to me what this is telling you?

**A: Male, mid 20s**:that Japan has the most cases  this week and the week before, also reveals that Japan has the most cases among major countries worldwide. So does the tree map 

**A: Female, mid 20s**: that Japan has the most cases  this week and the week before, also reveals that Japan has the most cases among major countries worldwide, but if you add another date that will be helpful 

- Is there anything you find surprising or confusing?

 **A: Male, mid 20s**:no. it is supreise that Japan has more cases than US (it turns out I made a mistakes that label the "total cases" into "total death cases")
 
 **A: Female, mid 20s**: No. 

- Who do you think is the intended audience for this?

 **A: Male, mid 20s**:people who want latest info of covid-19, probably scholars who study this. 
 
 **A: Female, mid 20s**: people who need latest data about covid-19 cases confirmation. 

- Is there anything you would change or do differently?

 **A: Male, mid 20s**: use more color and make the number stand out in the bar graph. Reduce the color in tree map 
 
 **A: Female, mid 20s** delete the grid line in treemap and highlight the labels to make it more good looking. 
 
 ## Conclusion from feedback 
- Based on the interview result and some initial thought, before conducting a real graph, I decide to perform the following adjustmen to my draft and original design: 
 **Usefulness**: follow my draft, using bar graph to represents different data
 **Perceptibility**: add legend to enphasize different countries/make the label above each bar graph to make the country stand out 
 **Intuitiveness**:delete the gridline to make the graph looks concise 
 **Aesthetics**: use more colors to make the graph more vivid. 
 **Engagement** use more colors. Only grey and red make the graph boring, we can use two different color scheme to make the graph looks vivid. I also even redesign another legend to make things stands out. 
 - I also gained common feedback that I should make my title even more clear, and I plan to add a little bit more explanation on the title/subtitle. 
 - Date also need to be added to the title to make it more informative
 - I also change the title of treemap to make it more informative 

## Rebuild
here is my final version of the rebuid. I use the same data source, while only keep the cases this week and last week. Two different color scheme is used here. I used pure red to make Japan stand out while using another lighter color sheme for other countriees. I also add the specific date on the title and subtitle to make things more clear. I also delete the grid line to make things more clear and consise. 


### Bar Graph 
<div class="flourish-embed flourish-chart" data-src="visualisation/12681719"><script src="https://public.flourish.studio/resources/embed.js"></script></div>

### Treemap
<div class="flourish-embed flourish-hierarchy" data-src="visualisation/12681723"><script src="https://public.flourish.studio/resources/embed.js"></script></div>

## Another round of interview 
### Interview with different people 
- Can you tell me what you think this is? 
**A: Male, mid 20s**: it had a informative title that reveals trend of Confirmed COVID–19 cases last week vs the week before. Also the graph reveals that Japan has the most death this week and the week before. The tree map's title is not informative enough, I think you'd better change it to the total case of COVID-19 would be helpful 

**A: Female, mid 20s**: it had a informative title that reveals trend of Confirmed COVID–19 cases last week vs the week before. Also the graph reveals that Japan has the most death this week and the week before.

**both interviee gave the same answer of the last round of interview ** 
  
- Can you describe to me what this is telling you?

**A: Male, mid 20s**: Japan is a dangerous place to visit

**A: Female, mid 20s**: Maybe add date to the title will be even more helpful. Since we don't know the exact date of ending and start 

- Is there anything you find surprising or confusing?
 **A: Female, mid 20s**: Why the bar graph is not ranked? I think rank gives reader a more clear view 
 
 **A: Male, mid 20s**: Same. Also you need to add the date to the title to make the reader know which week you are refering to 

- Who do you think is the intended audience for this?

 **A: Male, mid 20s**:people who want latest info of covid-19, probably scholars who study this. 
 
 **A: Female, mid 20s**: people who need latest data about covid-19 cases confirmation. 

- Is there anything you would change or do differently?

 **A: Male, mid 20s**: Reduce the color in tree map even more, add label to tree map given it has so much white space 
 
 **A: Female, mid 20s** No other advice. 
 
 ## Conclusion from feedback 
based on the 2nd round of interview, I decide to change the data a little bit more: add label to tree map, adjust the font, and both add date and subtitle for the bar graph and tree map. 

## Rebuild of rebuild 
Finally, after all the adjustment, I rebuilt the tree map and the bar graph. Date problem is fixed and fonts are further adjusted. Everything ranking in order. 

 **there are a pattern that I want to achieve but flourish does not allow me to do so ** : if I could add a small label on the first bar indicates that's the new case and a label for the second bar, that would be great. however, I can not add that. It's lucky that the interactive feature would provide label for the second bar and the first bar though. 
 
## Tree map
<div class="flourish-embed flourish-hierarchy" data-src="visualisation/12681849"><script src="https://public.flourish.studio/resources/embed.js"></script></div>

## Bar graph
<div class="flourish-embed flourish-chart" data-src="visualisation/12667095"><script src="https://public.flourish.studio/resources/embed.js"></script></div>

 

