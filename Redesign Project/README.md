![Alt text](https://user-images.githubusercontent.com/31669563/32384578-a08588ac-c078-11e7-8165-c8b5fb4da1d9.png)
### Project Overview:
According to the institute for Women’s Policy Research, women are paid 20 percent less than their male counterparts. Some experts even say that women won’t even reach pay equity until 2151. Even after introducing number of bills across the country aiming at shrinking the pay gap, situation has not changed much for women. With this pay bias, a woman working full time, year-round will lose more than $10,000 a year to the wage gap. As a result women will have less wealth, less resources for their retirement and this will affect overall quality of their life. The aim of this project is to analyze the gender pay group for different age groups to figure out the impact of age on women’s earnings, we will also try find out several reasons behind this pay gap.


### Motivation for this topic:
When I was shortlisting topics for redesigning, I stumbled upon a great visualization on gender pay gap. Coincidently, the very next day I came across an article in Forbes magazine. The article heading compelled me to go through every word of it. It said “Why The Pay Gap Widens As Women Get Older”. Being a woman, I was able to relate with the article. My inquisitive mind started relating these two topics and I thought I should redesign the existing visualization on gender pay gap to find the its behavior as the woman gets older. 

### Intended audience:
_Government, corporate professionals and general public._

### Task of the visualizaion:
This visualization is developed to redesign and improve the existing visualization on gender pay gap. 

#### Critique on the original visualization:

![Alt text](https://user-images.githubusercontent.com/31669563/32383676-de3d0222-c075-11e7-8273-668478f92302.PNG)
![Alt text](https://user-images.githubusercontent.com/31669563/32383682-e0889802-c075-11e7-8760-8858ceee5bd2.PNG)


First of all, the original visualization is not sorted based on pay gap. Hence it is difficult to figure out in the first look which category has the maximum pay gap. Also, the visualization is based on each job role under each occupational category. Current claim is “Women are getting paid less than their male counterparts”. If we try to relate the claim with the data on the visualization, we see that lot of unnecessary information has been put at once which can distract the audience from the main claim. Holistic view of just the occupational categories would have sufficed the goal.

Secondly, the viz compares the pay gap on the basis of job role which seems inappropriate. Job role in each category can be very different from the job role in another category. For example, skillset of a production worker is completely different than skillset of a lawyer. Hence, comparing these job roles doesn’t give us any useful information. 

Additionally, it would have been helpful if the visualization had the actual pay gap in the tooltip. When we look at the categories like “Laundry & dry-cleaning workers” and “Agricultural workers”, pay gap appears to be the same for both. Actual or percentage pay gap would have helped us differentiate between the two roles. 

Finally, the visualization does not highlight the parameters which can help us in taking effective actions to reduce the pay bias. Neither, does it give the baseline to find out the reasons behind the pay gap. 

#### Scope of improvement: 
In addition to showing the wage gap for each occupational category, visualization should provide some parameters on the basis of which the audience can easily figure out the reasons for pay gap. Once the reasons are clear, it would be easy for them to think about the corrective measures. 

Hence, I took salaries of men and women serving the same occupation as my second dataset in order to find out the reasons behind this bias. This will help us understand what happens to wage gap when a woman gets older. Does her accumulated experience brings fairness in the pay structure? Does her family responsibilities affect her work life? Does she feel motivated to continue her work? We will try to find answer for all of these questions in this report. 

### A glance at the development process:

#### Data collection/exploration/wrangling: 
Data for the original visualization is was obtained from US Bureau of Labor Statistics, UK Office of National Statistics and The Guardian Datablog. The salaries shown here are for Full-time employees in Year 2016. Due to lack of data, part-time or freelance salaries are not covered as part of this visualization. I picked this as my first dataset, as it was already clean, there was no need of data wrangling. I did make minor formatting changes to make it easily readable by Tableau.


Dataset1:

Source for original: http://www.informationisbeautiful.net/visualizations/gender-pay-gap/

Also uploaded at https://github.com/PriyankaN22/Dashboard-Visualization/blob/master/Redesign%20Project/Datasets/Gender%20Pay%20Gap%20-%20Public%20Data.xlsx

My version: https://github.com/PriyankaN22/Dashboard-Visualization/blob/master/Redesign%20Project/Datasets/Gender%20Pay%20PAN.csv


Dataset2: 
Second dataset is median weekly earnings of men and women in Year 2016 all the age groups. Again, the data considered here is for full-time employees only. 

Source for original: https://www.bls.gov/cps/earnings.htm

Also uploaded at https://github.com/PriyankaN22/Dashboard-Visualization/blob/master/Redesign%20Project/Datasets/cpsaat11b.xlsx

My version: https://github.com/PriyankaN22/Dashboard-Visualization/blob/master/Redesign%20Project/Datasets/Age%20analysis.xlsx


Dataset 3: Occupational categories “Management” and “Legal” has the maximum wage gap. Hence I tried to research on the number of women from each age group working for above two categories. I have combined the two categories into one.

Source for original: https://www.bls.gov/cps/earnings.htm

Also uploaded at https://github.com/PriyankaN22/Dashboard-Visualization/blob/master/Redesign%20Project/Datasets/womens-earnings-tables-2016.xlsx

My version: https://github.com/PriyankaN22/Dashboard-Visualization/blob/master/Redesign%20Project/Datasets/Category%20wise.xlsx

#### Visualization:

#### Claim: 
Gender pay gap increases with age

#### Qualifier: 
Average earnings of men and women working full-time in US.

#### Warrant: 
Management and legal category has the widest wage gap. Most of the women working in this field are of age between 35 to 54 years. Almost 6,208 women are between the age group 35 to 44 years which forms almost 23% of the overall count. As the age increases, count of women also increases raising the percentage from 23% to 25%. This proves our claim(shown in the first chart on the dashboard) that pay gap increases as the women get older.

#### Backing: 
Third graph on the dashboard(Number of women of each age group working in Management and Legal category) provides the backing for our claim.

https://www.thebalance.com/understanding-the-gender-wage-gap-in-the-legal-profession-4000621

https://www.wgea.gov.au/media-releases/gender-pay-gap-biggest-manager-ranks

#### Reservations: 
The claim is formed only on the basis of salaries of full-time employees. Earnings of part-time employees may alter the visualization data.

#### Version 1.0:

![Alt text](https://github.com/PriyankaN22/Dashboard-Visualization/blob/master/Images/v1.0.PNG)


Plotted by weekly earnings of men and women against age group. Clearly, the chart shows that the difference in earnings signifincantly increases with age.

The pay gap is narrow for men and women early in their careers, a dynamic possibly driven by today’s heightened awareness of a gender pay gap. Earnings are pretty much equal for first 4-5 years of their career. But after 4-5 years’ experience, a gap appears. We can see that after 24, the gap widens substantially and it becomes broader over the next three decades. Why does he gap increase ? It’s the late 20s and 30s – when most of the women have family and child care responsibilities. Child care, and even marryingin the first place impacts women’s pay relative to men’s. Even if both the spouses work full-time, the division of labour is not equal. Women tend to take less strenuous jobs in preparation for their children, or employers hesitate to give them more resposibilies in an assumption that they will have babies and will have to take time-off. When women take parental leave, their salaries are affected more negatively than when men take leave. 

Married women without the children also earn less because they have to give up job opportunities for their husband’s job. It is logical that the less earning spouse does all the household chores and child care. But it’s also a reason women earn less in the first place. This re-inforces the bias and women are trapped in this self-reinforcing cycle. 

Some women do work less after having children, but not all. Employers pay less to these women too assuming they will be less committed. This generelization adds on to the widening of gap. If your boss believes you will leave the workforce in the foreseeable future to have kids, chances are he or she will pass over you for promotions and additional responsibility and instead invest in the men who they think will be around for the long haul.

Furthur, surprisingly, after the age of 35, earning of a man increases till the age of 64 whereas for a woman it starts reducing gradually making this gap widest at the age of 55. Another reason could be, women not getting raises and promotions at the rateof men within companies. Seniority and experiences seem to pay off much morefor men than for women. 

To improve this version and to provide backing for the claim, I added two more datasets to analyze the pay gap in each occupational category and number of women working in late 20s & 30s for the category with maximum pay gap.

#### Version 2.0:

![Alt text](https://github.com/PriyankaN22/Dashboard-Visualization/blob/master/Images/v4.0.PNG)

First chart is plotted by average pay gap against each occupational category. It has been observed that women in management and legal profession earn highest salaries, ironically, this is the category with the maximum wage gap. Though these women earn high salary, it is way less than what they deserve and what their male colleagues get paid. Senior managers and executives have 38% average pay gap and legal professionals have 30% average pay gap. 

Second chart is plotted by age group against number of women working for this category. Most of the women are of age between 35 to 54 years. 48% of women working in this field are of age between 34 to 54 years. Qualification and experience doesn’t always lead to higher pay. This proves that the more years a woman spends in the workforce, in other words, as the woman gets older, the bigger the gap gets between her and her equally experienced male colleagues.

These two charts provide the backing to our claim that “Gender pay gap increases with age”. 

#### Final version: 

Putting all of these three charts on one dashboard is the best way to make this visulization persuasive. First graph gives the holistic view about the behaviour of wage bias with age. Second and third graph provides the backing for claim by providing more information about the gap for each job category and by highlighting the number of women with the highest pay gap in each age group respectively. 


### Actions/Corrective measures: 

We will divide the actions as per the target audience:

_Government:_ 
The visualization puts light on an important issue of pay bias. The results found under this visualization would be of great help for government to come up with better policies for women welfare. 
Providing subsidized child-care and moderate-length parental leave can be the other remedy to curb the pay gap. 
Lawmakers should publicly set goals for hiring and promoting women to higher positions if they are capable. 

_Workplaces:_ 
Hiring managers should insist for fairness in pay for both men and women. 
They should use blind screening to remove gender identifiers when selecting candidates for interviews; and support equal-paid parental leave for men and women. 
Workplaces should not generalize and assume that a woman will be less committed due to her family responsibilities. 
Firms should conduct regular salary audits to look for gender and race-based inequities. 

_General public and individuals:_ 
Equal division of household duties should be incorporated. Men should contribute equally in household chores. 
Biases accumulate over time. Workplaces often base new hires’ compensation on their most recent salary. Since women are generally paid less than men, that difference gets exacerbated at every new job they take. 
Women are less aggressive in negotiating and when they try they meet more resistance. Women should be armed with data knowing what their worth is. There are various online tools which can help to get this information. 
Lastly, women should learn to negotiate and speak for themselves. 
