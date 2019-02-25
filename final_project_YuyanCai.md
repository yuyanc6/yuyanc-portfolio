# Final Project Part I

## Project Outline
Project name: High Risk of Bitcoin  
Project outline: Introduction to Bitcoin -> Price change of Bitcoin -> Volatility as risk measure -> Risk of exchange hacks -> Conclusion

## High-Level Summary
High risk of Bitcoin is not acknowledged by many investors

## Project Structure
![Moodboard](https://raw.githubusercontent.com/yuyanc6/yuyanc-portfolio/master/moodboard.jpg) 

## Data Source
* My data is the volatility of Bitcoin, S&P 500 index, EUR/USD, and gold calculated by the weekly-average prices, and the price of Bitcoin. The source of the prices is investing.com. For example, the historical prices of Bitcoin are from: https://www.investing.com/crypto/bitcoin/btc-usd-historical-data
* Volatility is a measurement of the risk of an asset. It is calculated as the standard deviation. I want to compare the volatility of Bitcoin with other 3 assets in addition to the weekly-averaged prices of Bitcoin to show the high risk of it. The prices of Bitcoin will serve as a background (in line chart with colored fill\ rigion) to give audience an intuitive feeling of the risk.  The volatility of all 4 assets will be shown in line chart. 
* Link to the data: https://github.com/yuyanc6/yuyanc-portfolio/blob/master/all_volatility_bitPrice.xlsx

## Method and Medium
* I will use shorthand to complete my final project
* In the front of the presentation, I will give a very brief introduction to Bitcoin about what it is and its historical prices.
* In the data analysis part, I will give a brief introduction to volatility, stating that it is simply a measure of risk. Then I will show the chart, and talk about the main idea of it. 
* Finally, I will give the call to reaction: Get to know Bitcoin better than other investors or do not invest in it. 

# Final Project Part II

## Sketches
https://github.com/yuyanc6/yuyanc-portfolio/blob/master/Sketches.pdf

## Storyboard
https://github.com/yuyanc6/yuyanc-portfolio/blob/master/Storyboard.pdf

## User research

* the target audience you hope to reach with your story;  
Normal investors who at least heard about Bitcoin  
  
* your approach to identifying representative individuals to interview;  
Representative individuals include my classmates, who knew something or heard about Bitcoin before but not familiar with it. Also, they want to invest in some asset in order to keep their money from depreciation.  
I presented to them my storyboard and sketches as I would in my final presentation. Here are the feedbacks from them. The answers given by them are listed under the corresponding question.  
  
* your interview script;  
Questions are modified from the Data Visualization Effectiveness Profile:  
1.	Do you get the point I tried to make?  
a)	Yes.  
b)	Yes.  
c)	Combined with the title and the volatility chart, your point is made.  
2.	All basic aspects covered?  
a)	Do not Know. Maybe.  
b)	Yes.  
c)	If volatility reveals risks well, then yes.  
3.	Is the presentation logical?  
a)	Yes.  
b)	There should be more description in presentation to transit from the price part to volatility part.  
c)	Yes  
4.	Do you understand the chart?  
a)	Yes.  
b)	No for the first sight.  
c)	Do not understand the hack part, how does it relate to risk?  
5.	Easy to understand the chart?  
a)	No, texts should be made more obvious. Volatility chart is difficult to understand because what is represented by each line is hard to be told.  
b)	Easy if there are more marks on the line for the second chart.  
c)	Volatility chart is easy but hack chart is not  
6.	Do the charts look good?  
a)	No.  
b)	Chart should be decorated more.  
c)	Yes  
7.	Do you know more about the risk of Bitcoin now?  
a)	Yes for risk of hacks, No for price risk.  
b)	Yes, overall Bitcoin is dangerous.  
c)	Yes, risk of price is high.  
  
* the findings from your interviews;  
  * Further modifications need to be made on the volatility chart to make it easier to understand. Emphasize on the volatility line of Bitcoin.
  * Typography of text needs to be more contrasting.
  * Charts needs to be refined
  * Information should be talked that cannot be described in charts or website but is important to make the presentation logical
  
* changes you implemented to your sketches, storyboards and wireframes to address the issues identified.
  * Change the price chart from line chart to bar chart. The color of the chart is changed to orange – the theme color of Bitcoin. Key information about Bitcoin is added on the chart.
  * Change the font size of the text. Change the color of each line (for example use green for dollar line and yellow for gold line). Add a small Bitcoin icon for the Bitcoin line to differentiate it from other line. Add the area chart of price and make it opaque (serve as the background and help audience transfer from the price chart in the former part to the volatility chart in this part).
  * Change the title from “Bitcoin Hacks” to “Bitcoin Stolen in Exchange Hacks”. Increase the overall size of circles. 
  
## Wireframes
https://preview.shorthand.com/Rjz0DpqzgoG7z8gD (It is the same link as the final shorthand page, since in part II I developed a draft using shorthand and I finished my final shorthand presentation based on the draft.)

# Final Project Part III

## Intended Audience
* My intended audience are common investors who at least heard about Bitcoin.  
* A common investor does not have to hold any investment, but care enough to hear some advices.  
* My audience might just have heard the word "Bitcoin" but do not know the exact meaning of it. Therefore, in the story I will use one or two sentence to introduce Bitcoin briefly.  

## Work summary
* In part I, I mainly focused on the story I wanted to tell, including the topic, the story outline, and the data.   
  * The topic is the risk of Bitcoin, which is something I want to talk about since many perple do not acknowledge the risk of it.   
  * The story outline frames how I will tell the story. The moodboard contributed a lot since the emotion curve helped me come up with what I needed to include in my story in order to tell it right. The emotion experience includes up and down, which is the classical way to impress an audience. Therefore, instead of just talk about the risks of Bitcoin and let audience experience only the downs, I decided to talk about the high price of Bitcoin and its fortune effect in the beginning to let audience experience the up first.  
  * The volatility data, which could make audience feel the risk of Bitcoin in the most straight-forward way, cannot be find in the format I wanted. Therefore, I downloaded the historical prices and calculated the volatility myself using the most commonly-used formula.  
* In part II, I hand drew the sketches and storyboards, and used Tableau to draw the sketches. After getting some feedback from the audience, I made some modifications to the sketches on tableau and finished the first draft of shorthand. 
  * The hand drawn sketches helped to express to my research audience whay I wanted to show in the charts. However, the sketches are too abstract, so I made the sketches on Tableau. Tableau is a helpful tool to make charts, especially in the case where I already had a desired visualization in head and just needed to present it by a convenient tool. Other tools like RAWgraph does not enable me to customize a visualization, so I chose Tableau.
  * The interview (user research) was helpful in that it made it possible for my visualization and presentation to be reviewed from other angles. For example, some audience in research told me that they do not understand what is a "hack" to the exchange and why does it matter to the risk of Bitcoin. Therefore, I added some content to explain the hacks in the context of Bitcoin exchange. Another example it the little Bitcoin icon I added on the volatility graph. Some audience told me that my original volatility chart was kind of a mess with all the lines that could ne be easily told which is Bitcoin. Therefore, I change the colors of all lines to make them more intuitive (green for dollar, yellow for gold, ...). Also, I added a little Bitcoin icon at the end of the Bitcoin line to emphasize it and make it easier for the audien to identify the most important part in the chart.
  * After all the modifications were done, I integrated the visualization and text into the shorthand. 

## Final Data Story
https://preview.shorthand.com/Rjz0DpqzgoG7z8gD
  

      

