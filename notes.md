# Week Four Notes

## Week 4 Readings
 Must do this after

## Week 4 Tasks

### Excel & R

**Mini Excel Tutorial**

- There were no issues from steps 1 - 3
- If I did it right, the total sum that appeared was **20780**, and the equation I wrote in was **=SUM(P15500:P15503)**
- Here is a picture of the chart I created as a part of step 3: ![Chart](https://github.com/Elissap5100/Week-Four-Work/blob/master/Chart.PNG)

- After the "Topic Modeling" section in this weeks work, I have to remeber to check out https://senderle.github.io/topic-modeling-tool/documentation/2017/01/06/quickstart.html for a pivot table tutorial. 

**Some Basic Counting and Plotting in R**

*Disclaimer:* In week 2 I belive when we were supposed to download Rstudio through Anaconda, it would not work no matter how hard I tried and played around with the files (following tutorials of course), but this week i am attempting to download the free to use version from their official website. I am hoping it works or I will be at a severe disadvantage for the rest of this week.

- There were overall no issues with this tutorial. Everything functioned fine after I downloaded the "external" version of R and Rstudio.
- Here is a picture of the first chart created during the tutorial: ![Chart1](https://github.com/Elissap5100/Week-Four-Work/blob/master/RplotA.png)
- Here is a picture of the Second Chart created during this tutorial: ![Rplot2](https://github.com/Elissap5100/Week-Four-Work/blob/master/RplotB.png)

- For the last part of this tutorial, we were pushed to try some other simple plots by following the tutorial linked. I was struggling for sume reason to upload the text files to Rstudio in the first place. After some research, I stubled across this link: http://www.sthda.com/english/wiki/reading-data-from-txt-csv-files-r-base-functions , which showed me this code: **my_data <- read.delim(file.choose())** , which allows me to choose a text file from anywhere on my computer. I simply saved the tauras.txt file to a designated folder and selected it using that code. From there I followed the first tutorial and made a few other basic plots!

- Here are the "Tarsus" plot examples:

![Chart](https://github.com/Elissap5100/Week-Four-Work/blob/master/TarsusA.png)
![Chart](https://github.com/Elissap5100/Week-Four-Work/blob/master/TarsusB.png)
![Chart](https://github.com/Elissap5100/Week-Four-Work/blob/master/TarsusC.png)

- Here are the "Unicorn" plot examples:

![Chart](https://github.com/Elissap5100/Week-Four-Work/blob/master/UnicornA.png)
![Chart](https://github.com/Elissap5100/Week-Four-Work/blob/master/unicornB.png)
![Chart](https://github.com/Elissap5100/Week-Four-Work/blob/master/unicornC.png)
![Chart](https://github.com/Elissap5100/Week-Four-Work/blob/master/unicornD.png)

## Voyant

**Voyant Tools Tutorial**

- I have run into an issue and it will not create the visualization: ![Issue](https://github.com/Elissap5100/Week-Four-Work/blob/master/Issue.PNG)
-Here is the error message that the warning links to: 

![Issue](https://github.com/Elissap5100/Week-Four-Work/blob/master/Problem1.PNG)
![Issue](https://github.com/Elissap5100/Week-Four-Work/blob/master/Problem2.PNG)

- I tried looking through the discord and googling the issue, but I could not seem to find any fixes to this problem. My nly guess is that I am somehow copying the wrong link (https://craftingdh.netlify.app/data/cnd.xlsx)? It is not the biggest issue in the world, because luckily we were provided with the Proffessor's version of the link. In the name of completing this weeks work and learning more, I decided to go ahead an use the version provided.


**Explore the Newspaper Corpus**

*Disclaimer*: I used the corpus link provided as I could not make my own for some unknown reason and did not want to delay this week's work progression too much.

- I dont have too much prior knowledge about this topic, but it was interesting to explore this digital tool
- I am unsure what i was exactly expecting, but I did not think that the term "New" would be the most used
  - After looking into the individual occurances of the word a little more, I realized that many of the uses of "New" were a part of a city or country name typically (ex: New York or New South Wales)
  - Many articles cover stories of growth, discoveries and new political boundaries and such, so it makes sense for "new" to be prevelant
- I also noticed that "Mr" was one of the most used terms, but (if I looked correctly) "Mrs" wasnt even in the top 50 terms used... It makes sense given the timeline that women were not spoken of much. Especially if the articles were talking about people with power. Earlier in history, of course it ws well known that it was typically men in those "top" positions
- I found the "links" view of the terms was very impactful as well: ![Links](https://github.com/Elissap5100/Week-Four-Work/blob/master/Links.PNG)
- I am unsure if this widget will work but:

<!--	Exported from Voyant Tools (voyant-tools.org).
The iframe src attribute below uses a relative protocol to better function with both
http and https sites, but if you're embedding this into a local web page (file protocol)
you should add an explicit protocol (https if you're using voyant-tools.org, otherwise
it depends on this server.
Feel free to change the height and width values or other styling below: -->
<iframe style='width: 509px; height: 329px;'src='https://voyant-tools.org/tool/CollocatesGraph/?query=new&query=mr&query=country&mode=corpus&context=3&corpus=ea1868d7f1fbece8f0f5538c23a3128e'> </iframe>

<!--	Exported from Voyant Tools (voyant-tools.org).
The iframe src attribute below uses a relative protocol to better function with both
http and https sites, but if you're embedding this into a local web page (file protocol)
you should add an explicit protocol (https if you're using voyant-tools.org, otherwise
it depends on this server.
Feel free to change the height and width values or other styling below: -->
<iframe style='width: 509px; height: 329px;' src='https://voyant-tools.org/tool/CorpusTerms/?corpus=ea1868d7f1fbece8f0f5538c23a3128e'></iframe>
