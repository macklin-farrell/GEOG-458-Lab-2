# GEOG 458 Lab 2: Youtube Crawler and Word Cloud Analysis

For this lab, I decided to look at urbanism in various cities around the United States. Urbanism is the study of urbanization, and how people interact with the built environment around them. It can be considered a form of cultural expression, but it is also a way to evaluate design choices about the built environment in question. This can include physical layout, policy, transportation methods, and more. For parameters, I used the city name, as well as the term 'Urbanism'. 

I chose each of them for different, specific reasons. I chose Seattle because it's where we are currently, so it feels salient and like a good baseline for comparison. I chose New York because it's a relatively old city, where the density lends itself to what are currently more popular design choices in urbanism, such as mixed use spaces, robust public transportation, and again density, which is opposite to urban sprawl. I chose Charlotte, North Carolina, due to it's recent growth. I wanted to see how an older city (older than Seattle, anyways) would compare to an old city like New York, and how it would differ. I was curious to see what kinds of terms or phrases would be common due to the urbanism thread between all three searches, and what would be different because of the geographical context provided to each search. 

![Seattle Word Cloud](img/Seattle%Word%Cloud.png)

## Seattle

What stood out to me, and a little bit what I went into this looking for, were things about the new light rail. There is also mention of housing, without very many mentions of specific neighborhoods. Some, but not many. Some of the words make it seem like the person doing the writing is not familiar with Seattle, or perhaps they're aware that other people watching their video might not be familiar with Seattle. 

![New York Word Cloud](img/New%York%Word%Cloud.png)

## New York

There were some surprise words here, such as "war" and "grim". While those were not big in the word cloud, I did think that it was interesting. A lot of the words here are about the character of the city, rather than about urbanism in a political sense. The word cloud reads like the introduction to a city in a book. It tells you a lot about the way the city is, currently. There is also the highest amount of named neighborhoods in this word map. I wonder if that's because that's how people there in NYC relate to the place, or if it's because the video author expects the viewer to relate to that information in a way that is not the case in lesser known Seattle and Charlotte. 

![Charlotte Word Cloud](img/Charlotte%Word%Cloud.png)

## Charlotte

I think of the three, this one had the most vernacular related to urbanism, and urban planning. "Planning", "planned", "urban planning", "architecture", "design". It also has mentions of the cities past, along with some of the culture there still. "Industrial", and "worship" stood out to me. It does also seem like of the three, this one picked up the most unrelated terms, which despite trying to filter through in both Word, and WordArt, I missed some. 


##Future Improvements
- Do more rigorous filtering, for example, needing a word to occur at least 3 times to be included, to filter noise.
- Additionally, do multiple versions of the same search to try to hit different videos.
- Use less explicit terms like "urbanism", and instead use related terms like "density", "transit", or "housing".
- Due to the open nature of publishing videos on Youtube, I'd be very interested to try and focus on people who are either specifically from there, talking about their hometown, or tourists who are experiencing the place for the first time. 

## Final Thoughts
I like the concept of expanding the way we look at being able to collect and visualize data about a place. I was surprised not so much at the way that each city varied, but how much they varied. I really expected with the one "urbanism" keyword that the results would be more homogenous than they were. 

**Download CSVs**
[Seattle](assets/Seattle%Urbanism%search%result.csv)

[New York](assets/New%York%Urbanism%search%result.csv)

[Charlotte](assets/Charlotte%Urbanism%search%result.csv)