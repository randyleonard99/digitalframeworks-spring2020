# Assignment 3: Collecting your own data.
## In class:

Watch [this webinar](https://resources.rstudio.com/wistia-rstudio-essentials-2/rstudioessentialsprogrammingpart1-2) on RSudio, starting with the 6-minute mark. 

Work as a group through the first of five chapters of [Codecademy R course](https://www.codecademy.com/courses/learn-r), take turns with each chapter presenting your screen to work through each exercise (2 through 5).

## Assignment 3: Collecting your own data.

Some great stories come out of reporters collecting their own datasets. Here are some examples:
* [Governors with very low approval ratings](https://fivethirtyeight.com/features/chris-christie-is-still-more-popular-than-governors-who-were-literally-criminals/)
* [Snap counts for various running backs](https://github.com/brentschwartz/digital-frameworks-hw/blob/master/finalproject.md), by a former Digital Frameworks student
* [Every Trump tweet insulting anything](https://www.nytimes.com/interactive/2016/01/28/upshot/donald-trump-twitter-insults.html)
* [White House visitors](https://www.politico.com/interactives/databases/trump-white-house-visitor-logs-and-records/index.html)
* [Emergency room bills](https://erbills.vox.com/)

Think about an area you're interested in, or one you may do your final project on, and come up with a dataset you wish existed. Then submit the following:

* A description of the question you're curious about, and an explanation about how this data could turn into a story. (Imagine this as your justification to your editor as to why this is worth your time)
* A list of the things you want to know about any data point
* An explanation of how you'd go about collecting that data (you don't actually have to do it on an ongoing basis, especially if it involves staking something out, just tell me how you would do it).
* A table including at least five data points in this dataset
* You can put your data in a google sheet (in which case, put the link in your markdown file) or make a table directly in the markdown document you submit like the example below.
* Your dataset cannot be something you can just find elsewhere. For example, do not pick something like "all earthquakes above magnitude 7 in the US" because someone (the USGS) already has exactly that data collection. If you want to do earthquakes, add more information such as the number of injuries and deaths reported in the media, and possibly include a link to the relevant media report as one of your columns.
* Submit this assignment as `assigment3.md`

## Can we have an example?

### Sure

President Trump has been conducting press conferences on the COVID-19 response. He wears a variety of ties, and I wonder if there is any coincidences with the colors he choses. For example, how often does he wear red vs. blue, given the party associations with the colors? 

Here are the features I'll be collecting, and an explanation of why:
* The color of Trump's tie
* The day and date of the press conference
* The time of the press conference (start time)
* The biggest takeaway from the conference (tone, outlandish comment, reality factors)
* A list of other people who spoke from the podium at the press conference, separated by semicolons
* A link to an image of Trump at the press conference from one of the following news sources: NYT, WaPo, WSJ, Politico, CNN, CSPAN

I will collect the data by watching part of the press conference and recording this information. I will use Twitter to find the most repeated takeaway. I will find the image by looking at the news sources cited above.

Color | Day | Date | Time | Takeaway | Other speakers | Image link
---- | ----- | ---- | -------- | ----------- | -------------- | ----------
tk | tk | tk | tk | tk | tk | tk


*you actually have to collect 5 datapoints from your proposed dataset -- this is just an example*