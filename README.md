# Data Analysis of Women Empowerment and Gender-Based Violence in India 2015-16

### J124 Final Project by Srikavya Jawabnavis 

The data I used was originally from a National Family Health Survey conducted by the Government of India, Ministry of Health and Family Welfare in 2015-16. The survey was conducted in correspondence with the International Institute of Population Sciences Information. The survey collected information from 601,509 households and 699,686 women.  

The data sets that I used were compiled by Samarth Bansal at the Hindustan Times. The .csv files can be found on Github -> HindustanTimesLabs -> women-empowerment-index. 

The specific .csv files I used were: 
1. [Married women who participated in household decisions (%)](https://github.com/HindustanTimesLabs/women-empowerment-index/blob/master/data/101.csv)
2. [Working women who got paid in cash (%)](https://github.com/HindustanTimesLabs/women-empowerment-index/blob/master/data/102.csv)
3. [Married women who have experienced spousal violence (%)](github.com/HindustanTimesLabs/women-empowerment-index/blob/master/data/103.csv) 
4. [Married women who experienced violence during pregnancy (%)](https://github.com/HindustanTimesLabs/women-empowerment-index/blob/master/data/104.csv)
5. [Women who own a house and/or land (%)](https://github.com/HindustanTimesLabs/women-empowerment-index/blob/master/data/105.csv)
6. [Women who have their own bank/savings account (%)](https://github.com/HindustanTimesLabs/women-empowerment-index/blob/master/data/106.csv) 
7. [Women who have their own mobile phone (%)](https://github.com/HindustanTimesLabs/women-empowerment-index/blob/master/data/107.csv) 
8. [Women who use hygienic products during their menstrual period (%)](https://github.com/HindustanTimesLabs/women-empowerment-index/blob/master/data/108.csv)

I downloaded the .csv files and imported them to Google Sheets where I interrogated the data for interesting trends or finds. I realized that the best way to understand this data was to visualize it. I created choropleth maps for each of the 8 indicators of Women Empowerment and Gender-Based Violence that the Indian  Ministry of Health and Family Welfare decided to collect data on. I chose to use Datawrapper to create the choropleth maps but before I could create them, I had to clean the data to match the datawrapper qualifications. 

There were slight discrepancies between the names of state in the data and on datawrapper. I had to make the following changes to the data to match the Datawrapper qualifications. 
1. Andaman and Nicobar Islands -> Andaman & Nicobar Island 
2. Dadra and Nagar Haveli -> Dadara & Nagar Havelli
3. Daman and Diu -> Daman & Diu
4. Jammu and Kashmir -> Jammu & Kashmir

After creating the choropleth maps I was able to continue my analysis of the data, but now visually. I wanted to would be interesting to see if there was regional trends in any of the indicators. I found three indicators showed regional trends.

#### 1. Higher percentages of married women participated in household decisions in Central India compared to the North and South. 
(with the exception of Punjab, Himachal Pradesh, and Uttarakand) 
<iframe title="Married women who participated in household decisions (%)" aria-label="map" id="datawrapper-chart-4roWv" src="https://datawrapper.dwcdn.net/4roWv/1/" scrolling="no" frameborder="0" style="width: 0; min-width: 100% !important; border: none;" height="765"></iframe><script type="text/javascript">!function(){"use strict";window.addEventListener("message",(function(a){if(void 0!==a.data["datawrapper-height"])for(var e in a.data["datawrapper-height"]){var t=document.getElementById("datawrapper-chart-"+e)||document.querySelector("iframe[src*='"+e+"']");t&&(t.style.height=a.data["datawrapper-height"][e]+"px")}}))}();
</script>


#### 2. Higher percentages of working women were paid in cash in the Southern states compared to Northern states. 

<iframe title="Working women who got paid in cash (%)" aria-label="map" id="datawrapper-chart-sD0Q3" src="https://datawrapper.dwcdn.net/sD0Q3/1/" scrolling="no" frameborder="0" style="width: 0; min-width: 100% !important; border: none;" height="765"></iframe><script type="text/javascript">!function(){"use strict";window.addEventListener("message",(function(a){if(void 0!==a.data["datawrapper-height"])for(var e in a.data["datawrapper-height"]){var t=document.getElementById("datawrapper-chart-"+e)||document.querySelector("iframe[src*='"+e+"']");t&&(t.style.height=a.data["datawrapper-height"][e]+"px")}}))}();
</script>


#### 3. Higher percentages of married women who have experienced spousal violence in the Southeast compared to the Northwest. 

<iframe title="Married women who have experienced spousal violence (%)" aria-label="map" id="datawrapper-chart-4yNr5" src="https://datawrapper.dwcdn.net/4yNr5/1/" scrolling="no" frameborder="0" style="width: 0; min-width: 100% !important; border: none;" height="765"></iframe><script type="text/javascript">!function(){"use strict";window.addEventListener("message",(function(a){if(void 0!==a.data["datawrapper-height"])for(var e in a.data["datawrapper-height"]){var t=document.getElementById("datawrapper-chart-"+e)||document.querySelector("iframe[src*='"+e+"']");t&&(t.style.height=a.data["datawrapper-height"][e]+"px")}}))}();
</script>


Based on these indicators, I can not make any conclusions on 2015-16 regional trends regarding women empowerment and gender violence. While both __participating in household decisions__ and __being paid in cash__ are indicators of women empowerment, the higher percentages were in different regions of India. Additionally, South India had higher percentages of __working women were paid in cash__ (an indicator of women empowerment) but also higher percentages of __spousal violence__ (indicator of gender violence). 

