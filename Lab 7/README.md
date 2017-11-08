## The financial markets do not punish security breaches
--------------------------------------------------------------------------------------------------------------------------------------
### Objective:

Develop persuasive visualization for data breaches and its impact on stocks over last 13 years. Perform data wrangling to read JSON symbols from Yahoo Query Tool to extract and clean stock price data of various companies from Yahoo Finance.

--------------------------------------------------------------------------------------------------------------------------------------
### Datasets:
In this assignment we are going to work on two datasets.

1. We are going to take the first dataset from last assginment.

2.  For second dataset we are going to use Yahoo Query Tool to extract the stock price for the companies from Yahoo Finance in the first dataset.
--------------------------------------------------------------------------------------------------------------------------------------
#### Target Audience:
Finance and Security personnel, organization
--------------------------------------------------------------------------------------------------------------------------------------
#### Claim: 
The financial markets do not punish security breaches
#### Qualifier: 
Security breaches in last 13 years all over the world for 250 companies.  
#### Warrant: 
Change in stock prices usually shows overall performance of a company. If the change is positive, that means there was no significant impact of any incident on company’s performance and reputation. Positive change in stock price indicates that even after the data breach, company did not have to suffer much in terms of stock price.
Backing:  
#### Reservations: 
The stock price we have taken here is average stock price for the year. We don’t know what was the immediate impact on the stock right after the breach. It may have dropped after the incident and then again the stock price would have spiked through because of some other factors.
So, it is inappropriate to say based on the data that we have, that financial markets do not punish security breaches.
-------------------------------------------------------------------------------------------------------------------------------------
#### Perception:
Security breach incidents for each company and the number of records lost

### Comprehension:
Comparision between average stock price of the year in which the breach happened with the average stock price for the previous year in order to find out the changes in stock. This comparision is used to analyze if the breach affected the financial positio n of the company or not.

--------------------------------------------------------------------------------------------------------------------------------------
#### _For actual assignment please refer the Jupyter file.
--------------------------------------------------------------------------------------------------------------------------------------
### Scope of Improvement/Future Enhancements:

There is a lot of scope of improvement in the Lab 3 version of visualization.
Below are some the points which I can improve on:

1. In the first graph, the ratio of data pixels to visualization pixels is not correct. We can improve by changing the scale for "Number of records lost". 

2. Second graph makes use of colors which do not really represent anything useful. So we can change it use to uniform color.

3. The green line which represents changes for Yahoo is not easily interepretable. So, the line can be removed.

4. Text added on the visualization is difficult to read. Hence, we can make it brief and increase the font so that it can be readable.

Above all were the aesthetic changes in the visualization.

We will try to focus on the content now.

1. As we coulnd't extract stock prices for all the companie, the sample that we have taken here is only for 30 companies. We are not sure if the sample we have taken is correct or not. The global market may show different trend. Hence one improvement could be to write a python code in such a way that it will extract the stock prices for as many companies as possible.

2. The Jupyter file does not show any detail about the project, its objective, kind of datasets we have taken. Adding a short explanation which contains objective and comment for each steps makes it much easier for an user to understand the project.

3. We are making a claim solely based on stock prices in an assumption that if there was a change in the stock, that was because of the breach. There can be other factors which are responsible for the change in stock price. For example, a company might have been affected adversely due to the breach, but they might have employed some strategies to recover back. The other possibility is some of the company's products might have been outstanding due to which companies stock was increased in the same year which would nullified the negative effect of breach on the stock price. In addition to that, we don't have the date on which the breach happened so we cannot compare the stock price before and after that day. As we know only the year of breach, we have taken the average stock price for that year. We don't know the immediate impact of the breach on the financial position of a company. In order to make the visualization better, we should either mention these assumptions or we should try to get the data which tells us when exactly the breach happened.

4. Effect of security breaches can be different for different organisations. For example, impact can be severe for banking and finance as compared to web organisations. Hence, it is a good idea to implement this point in visualization and categorise the companies based on their organisations. 

#### Audience fear:

Tableau Link: https://public.tableau.com/profile/priyanka.n4310#!/vizhome/DatabreachesvsFinancialposition/Dashboard2?publish=yes
You can find the Jupyter file in the same directory.


                                                                                                                          -Priyanka N
