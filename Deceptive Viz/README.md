![emissions](https://user-images.githubusercontent.com/31669563/32973068-6889a05e-cbaa-11e7-9520-9ca85a56bc22.jpg)

## Project overview:

The purpose of this project is analyze worldwide emissions of carbon dioxide- the greenhouse gas most responsible for global warming. According to the reports released at United Nations’ annual climate change conference, global CO2 emissions appear to be going up. The atmospheric concentration of carbon dioxide has been rising extensively since the Industrial Revolution and has now reached dangerous levels not seen in the last 3 million years. In this project, we are tying to understand the contributions of developed and developing nations to global climate forcing and overall CO2 emission. 

## Motivation:

I wanted to work on the global issue as part of my project, so I shortlisted two topics - population explosion and climate change. These two are the most critical problems that the world is facing today. I couldn’t find the enough data which can serve the purpose of deceptive visualization, I decided to go with climate change as the topic of deceptive visualization project. 

Among the major challenges affecting the world today, climate change and destruction of natural resources is the most serious one. From shifting weather patterns that threaten food production, to rising sea levels that increase the risk of catastrophic flooding, the impacts of climate change are global in scope and unprecedented in scale. Most scientists agree that the main cause of climate change is human expansion of “greenhouse effect“ – warming that results when atmosphere traps heat radiating from Earth towards space. Carbon dioxide(CO2) is an important heat-trapping gas and CO2 emissions contributed significantly towards climate change.  Over the years, human activities such as deforestation, land use changes, burning fossil fuels have increased atmospheric CO2 levels by more than a third since the Industrial Revolution. 

There is a strong need of determining mitigating strategies that seek to hold individuals and nations accountable for their historic emissions. For that, it is a good idea to divide the countries into two groups – developing nations and developed nations. In this visualization, we will try to understand the relative contribution of each group which will us come up with an action plan to reduce the CO2 emission. 

## Objective of visualization:

The world’s countries contribute different amounts of CO2 to atmosphere. We cannot solve the climate change problem without participation of all the countries. In order to figure out the steps necessary to reduce global emissions of greenhouse gases in an effort to check global climate change, it is important to study the CO2 emissions by each country. Formulation of targets for emissions reduction for all countries based on the principle of “common but differentiated responsibilities” depends primarily on the quantitative attribution of the responsibilities of developed and developing countries for historical climate change. So, we have divided our analysis into two groups – developed and developing countries. 

The visualization will present the CO2 emissions for last 160 years for developing and developed countries.  We will be developing two visualizations which refute each other.  The purpose is to experience and realize the ethical implications of design decisions during the development of visualizations.

## Datasets:

Here, we have taken CO2 emissions(measured in  million tons) since 1751 till 2013 for almost all the countries in the world.

Source: https://ourworldindata.org/co2-and-other-greenhouse-gas-emissions/#the-long-run-history-cumulative-co2

Also uploaded at: https://github.com/PriyankaN22/Dashboard-Visualization/blob/master/Deceptive%20Viz/cumulative-co-emissions.csv

## Roadmap:
### Phase 1:
#### Data exploration and development of a basic prototype

After selecting a topic, I started exploring data. https://ourworldindata.org/ provided a good quality data which was needed for this analysis. This site has used CDIAC(Carbon Dioxide Information Analysis Center) - http://cdiac.ess-dive.lbl.gov/trends/emis/meth_reg.html as the main source to extract and collate CO2 emissions from various factors. As the data was already clean and in required format, there was no need to perform data wrangling. I used this data as it is.

At the beginning, I wanted to understand the overall trend of CO2 emission. Hence, I plotted a graph of average cumulative CO2 emissions for last 150 years for all the countries. The graph showed that CO2 emission is increasing rapidly over the years with 2014 being the year of highest emission. Please refer below.

<img width="548" alt="v1 0" src="https://user-images.githubusercontent.com/31669563/32976233-00fa2e8c-cbc7-11e7-9f96-d51b439ffe82.PNG">


These findings helped me form a base for developing a claim. Hence, I developed following model.

#### Claim: 
CO2 emission is increasing rapidly all over the world.

#### Qualifier: 
Average CO2 emission for all the countries in the world.

#### Warrant: 
According to  World Meteorological Organisation (WMO), surging carbon dioxide levels have pushed greenhouse gases to records high in the atmosphere. The concentration has increased at its fastest rate for 30 years in 2013. These facts show that average CO2 emission is rapidly increasing all over the world

#### Backing: 
https://www.theguardian.com/environment/2014/sep/09/carbon-dioxide-emissions-greenhouse-gases

#### Disadvantage: 
This version provides us the holistic view and indicates the overall trend, however, it is difficult to target a particular parameter in order to develop action plans.

### Phase 2: 
#### Approval for basic prototype and the implementation process

As part of this step, I presented the basic prototype to professor along with the claim and implementation process that I was going to follow. 

### Phase 3: 
#### Development of final visualization I

After receiving approval for basic prototype, I started working on the flaws in previous version. I came up with an idea of dividing countries into two categories – developed and developing. The purpose of this categorization was to determine which category has more CO2 emission. As the two categories differ significantly in terms of industrial revolution, mitigation strategies to reduce the emission in these categories would also be different. Therefore, these categories will give us a way to compare and find out reasons for rising emissions. 

In this version, I have plotted emission for both the categories against year. Clearly, we can see CO2 emission is way higher for developed countries. In 2014, emission for developed nation was 376,213 million tons whereas it was 174,875 million tons for developing countries. That means developed countries contribute almost twice as that of the developing countries. I chose area graph because I wanted to show the comparison between two categories. Looking at the area, we can easily figure out the difference.

<img width="499" alt="v2 0" src="https://user-images.githubusercontent.com/31669563/32977495-60ab9778-cbe3-11e7-81b8-548307b584e6.PNG">


Hence, I modified my claim as below.

#### Claim: 
Developed nations contribute more to overall CO2 emission than developing nations.

#### Qualifier: 
Average CO2 emission for developed and developing countries.

#### Warrant: 
As the average CO2 emission for developed countries is almost twice as that of the developing countries, developed countries are major sources of rising CO2 emission levels. 

#### Backing: 
https://www.cgdev.org/media/who-caused-climate-change-historically



#### Analysis: 
Global warming is the consequence of greenhouse gas emissions, mainly CO2, which has accumulated in the Earth’s atmosphere as a result of fossil fuel based industrial activity in the developed countries of the world. Between 1850 to 1960, developed countries saw a large increase in industrialization and population due to which the world experienced a constant growth of emissions. Developed nations are heavily industrialized as compared to developing nations and release more greenhouse gases per capita than developing ones. Developed countries have high number of vehicles which produce more gas eventually leading to the excessive CO2 emission and thereby causing climate change.

#### Actions/Corrective measures: 
Developed countries must put every necessary effort to stabilize greenhouse gas emissions caused by industrialization.

International agreements like Kyoto protocol should be strictly enforced to follow emission reduction targets.

General public in these countries should be made aware about increasing CO2 levels. As per the saying “Change should start from within”, every individual should consider climate change as their own problem and should try to support global effort by contributing on individual level.  Some of the ways an individual can reduce emissions is are:

-Using public transport instead of own vehicles

-Planting more and more trees. Trees absorbs CO2 thereby reducing the trapped CO2 in the  atmosphere.  

-Carpooling

### Phase 4: Development of deceptive version

The task was to develop a visualization which will purposefully deceive the audience. 

For this, I have plotted two graphs. First one showing percentage difference between CO2 emissions for developed and developing nations from year 1850 to 2014 and second for average emission of two countries from each category. 

<img width="502" alt="v3 0" src="https://user-images.githubusercontent.com/31669563/32978382-175f00d8-cbf6-11e7-808e-a40903d794bc.PNG">

We see that in the above graph, from 1850 to 1930, percent increase in CO2 emission of developed nations is below 5%. From year 1930 till 2014, it decreased significantly. There was only an increase of 1.4% in year 2014 as compared to emission in 2013. Whereas, if we observe for developing nations, rate of increase in CO2 emission went on increasing from year 1850 till 1865. The rate decreased slightly from 1870 till 1930, but it again increased to become 6.7% in 1960. After that the rate never decreased, it remained stagnant(4-5%) till now. Comparison for both the categories shows that CO for developing countries is increasing at a much higher rate than that of developing countries. According to U .S. Energy Information Administration (EIA), if the emission continue to increase at this rate, emissions from developing countries will be 127 percent higher than the developed economies by 2040. 

<img width="498" alt="v4 0" src="https://user-images.githubusercontent.com/31669563/32985441-0c6ea834-cc70-11e7-9038-96518f377d99.PNG">

In the second graph, I have picked the sample of two maximum emitters from each category. Developing countries like UAE and Qatar are the highest emitters, US and UK are highest amongst developed countries.  I have plotted average CO2 emission per capita per year for UAE, Qatar, UK and US for a time period of 1950 to 2014. Per capita emission for developing countries is way higher than that of developed countries. Average per capita emission for developed nations is some what constant between 6-9 tons per year for the given time period. Developing nations saw a huge rise in per capita emission in the decade of 1960. Though the emission decreased after that, it still remained significantly more than the emission from developed countries. Looking at the latest data, Qatar is the highest emitter with 49.7 tons followed by 23.3 tons for UAE. UK could keep their emission in check to around 6.5 tons for all these years. Even US has managed to curb down their emission to around 16 tons per capita per year. This means, per capita emission for developing nation is almost thrice the per capita emission for developed nations. 

Carbon emissions are created as people burn fossil fuels to produce electricity and power cars. Middle east countries including Qatar and UAE has the highest carbon footprint globally. Oil and gas resources are plentiful and cheap in these countries, so there is no financial incentive to use less energy.  Gulf countries has world’s largest oil reserves, and exports most of what it, this had been a source of seemingly endless wealth and major source of carbon emission. Dubai has also constructed no less than ten golf courses in the middle of its desert, Gulf countries have create unnatural marvels at great expense and with heavy energy consumption. While the other countries have constantly made efforts to cut back on emission, UAE and other gulfs has done little to nothing to reduce its carbon footprint. Pollution from vehicles continues to blacken the air in Arab cities. So, these developing nations from Middle east have to think about the ways to reduce energy consumption.









