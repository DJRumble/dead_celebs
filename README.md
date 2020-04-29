# Dead Celebrities

2016 has seen a unparreleled levels of 'celebrity deaths' leading some people to hail it hyperbollically as the 'worst year ever'. 
Is it true that the number of celebrity deaths has increased in 2016 relative to previous years. 

Henry Hartigen notes that, "as we move through the years, the number of 'celebs' in general increases due to the globalisation of 
media, film, music etc? So naturally we should expect the raw numbers to increase but relative to the number of 'celebs' year on 
year perhaps it is still a reasonable expectation to see more deaths?"

Can this be proven using the data? And is it possible to model the rates of celeberity deaths into the future?

# The DATA

The primary data source for this project is the website: http://fiftiesweb.com/dead/dead-people-2006/

I leave the deffinition of what makes a person a celeberity to this website. 

Data will be nee to be extracted from the websites HTML. This will allow for the following features:

- Name
- Year (oD)
- Month (oD)
- day (oD)
- Age (aD)
- Profession

This data spans 2000 to 2017, though format does change across the course of the website (which is not helpful). 

# Celebrity status

James Ball notes - "how did you define a Celebrity death? How much of a celebrity does someone need to be for them to be counted?"

In this project I am totally reliant on http://fiftiesweb.com/ for this deffinition. This is an American website and is likily to be biased thusly.
On thier website they appear to provide two lists of major, and all celeberity deaths.

Some suggestions for alternative methods:

- twitter - count the tweet mentions of a Celebrity the week following thier death (problematic for those celebs not on Twitter).
- Obituaries - count the length of thier obituary in a news paper (subject to newspaper bias and requiring NLP).




