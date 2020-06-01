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
- **Update**: I tried it and tested both embed links and neither worked, so using Github markdown practices I just highlighted the code. The class lesson mentioned we will learn more next week about this technique so I let it go for now.

```
<!--	Exported from Voyant Tools (voyant-tools.org).
The iframe src attribute below uses a relative protocol to better function with both
http and https sites, but if you're embedding this into a local web page (file protocol)
you should add an explicit protocol (https if you're using voyant-tools.org, otherwise
it depends on this server.
Feel free to change the height and width values or other styling below: -->
<iframe style='width: 509px; height: 329px;'src='https://voyant-tools.org/tool/CollocatesGraph/?query=new&query=mr&query=country&mode=corpus&context=3&corpus=ea1868d7f1fbece8f0f5538c23a3128e'> </iframe>
```
```
<!--	Exported from Voyant Tools (voyant-tools.org).
The iframe src attribute below uses a relative protocol to better function with both
http and https sites, but if you're embedding this into a local web page (file protocol)
you should add an explicit protocol (https if you're using voyant-tools.org, otherwise
it depends on this server.
Feel free to change the height and width values or other styling below: -->
<iframe style='width: 509px; height: 329px;' src='https://voyant-tools.org/tool/CorpusTerms/?corpus=ea1868d7f1fbece8f0f5538c23a3128e'></iframe>
```

**Build Your Own Corpus**

- I decided to search for all the times the words "Graphic design" appeared from 1789 - 1963 in all states from Chronicling America database
![Step 1](https://github.com/Elissap5100/Week-Four-Work/blob/master/Step1.PNG)
- After following the process we did in week 2, I managed to (somewhat) successfully upload the collected texts into voyant 
   - All important files will be uploaded to this week's repository
![Step 2](https://github.com/Elissap5100/Week-Four-Work/blob/master/Step2.PNG)   
- I will admit my first look at the uploaded information was a bit difficult to understand as it seems the text was uploaded abit messily and there were some "fake words" that appeared and scewed the data. To fix this, I tried to add said strange words to the stop list. Here are the new results: 
![Step 2](https://github.com/Elissap5100/Week-Four-Work/blob/master/step3.PNG)  
- It was quite interesting to explore. The text that was downloaded was not the cleanest, but I was able to understand the context of most words. Expectedly, words relating to school (program, course, class, student, art, ect) were trending. In fact, many of the texts I explored were talking about prorams offered in universities in graphic design, which was cool to see!
- Here is the link to view my work: https://voyant-tools.org/?corpus=6445c4c3faf897ac8fd2afe4485b73da
- Next time, I would take the time to edit the text, remove any "/n" that appear or odd words like we did in last weeks tutorial. 

**Going Further**
- There were no major issues downloading Voyant on to my own computer

**AntConc**

- This section was completed by following: https://programminghistorian.org/en/lessons/corpus-analysis-with-antconc
-Overall, I found it pretty pleasant to follow and learned of how useful a tool this can be. In future projects I am sure this will be very helpful in finding themes amoungst mass amounts of data and text! I wonder in what massive ways this technique has been used, or if it is used for projects in other fields than history (media production maybe)? 

- This tutorial was pretty easy to follow, even with the differing data. The only "hard part" was deciding which key words to find (which I think was the main point of the whole task)
- I did find that the word 'king' was the most used word (that wasnt a connecting word), which was interesting!
- Lord was not too far behind, used as both a title and as in God
- The word 'devil' was used more than the word queen in all the texts
- any files created during this turotial will be included in the repository

**Topic Modeling with the TMTool**
- There was no issues with downloading this software or following the steps 
- I tried a few of the tutorials and made some visualizations
  - The tutorials were easy enough to follow, and fairly impactful to look at the data in another way. With more context, I could see how helpful this tool could be
  - I struggled with the second pivot table because none of my files had the years attached to them, so I got creative and organized the data abit.
  
![Viz A](https://github.com/Elissap5100/Week-Four-Work/blob/master/vizA.PNG) 
![Viz B](https://github.com/Elissap5100/Week-Four-Work/blob/master/vizB.PNG) 
![Viz C](https://github.com/Elissap5100/Week-Four-Work/blob/master/vizC.PNG) 

**Topic Model in R**
P.S - I have no idea why the six showed up like that and it would not change no matter what I tried
- This whole process actually went quite smoothly, I only ran into one issue
   - At the last part of the code i ran into an error: " Error in alphabet(20) : could not find function "alphabet" "
   - Fortunatley, this issue was brought up in the discord group and the suggested fix worked perfectly.
   
- Here are some of the visualizations I made:

![Viz A](https://github.com/Elissap5100/Week-Four-Work/blob/master/finalA.png) 
![Viz B](https://github.com/Elissap5100/Week-Four-Work/blob/master/final2.png) 
 
  
### Bonus

![B1](https://github.com/Elissap5100/Week-Four-Work/blob/master/b1.png) 
![B2](https://github.com/Elissap5100/Week-Four-Work/blob/master/b2.png) 
![B3](https://github.com/Elissap5100/Week-Four-Work/blob/master/b3.png)
![B4](https://github.com/Elissap5100/Week-Four-Work/blob/master/b4.png)
