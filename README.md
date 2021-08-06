# Tangling is easy but untangling is hard. Some advice on exploratory data analysis for longitudinal data

[![Netlify Status]()]()

# Learn more at [brolgar.njtierney.com](http://brolgar.njtierney.com/)

# Slides available [here](https://njt-jsm21.netlify.com/)

# Take home messages

1.  Longitudinal data as a time series
2.  Specify structure once
3.  Use `facet_sample()` / `facet_strata()` to look at data
4.  Summarise with `features` to find interesting observations
5.  Reconnect summaries to data with a **left join**
6.  Repeat this process

# Abstract

Longitudinal (panel) data provide the opportunity to examine temporal patterns of individuals, because measurements are collected on the same individuals at different, and often irregular, time points. One of the challenges with this data is the typical "spaghetti plot" visualisation, where a line plot is drawn for each individual, measured over time for some variable. Even a small number of individuals can make these plots too overplotted to parse, and interesting signals are lost to the noise.  Statistical models can be fit to these data to understand them, but we can often miss the individual patterns. 

This talk discusses new methods for identifying interesting individuals to better capture the individual experience. I introduce the R package, brolgar (BRowse over Longitudinal data Graphically and Analytically in R), which provides tools to facilitate these methods.


# Thanks

  - Di Cook
  - Tania Prvan
  - Stuart Lee
  - Mitchell O’Hara Wild
  - Earo Wang
  - Rob Hyndman
  - Miles McBain
  - Hadley Wickham
  - Monash University
  - Nick Golding
  - Telethon Kids Institute

# Resources

  - [feasts](http://feasts.tidyverts.org/)
  - [tsibble](http://tsibble.tidyverts.org/)
  - [Time series graphics using
    feasts](https://robjhyndman.com/hyndsight/feasts/)
  - [Feature-based time series
    analysis](https://robjhyndman.com/hyndsight/fbtsa/)

# Colophon

  - Slides made using [xaringan](https://github.com/yihui/xaringan)
  - Extended with
    [xaringanthemer](https://github.com/gadenbuie/xaringanthemer)
  - Colours taken + modified from [lorikeet theme from
    ochRe](https://github.com/ropenscilabs/ochRe)
  - Header font is **Josefin Sans**
  - Body text font is **Montserrat**
  - Code font is **Fira Mono**

# bio

Dr. Nicholas Tierney (PhD. Statistics, BPsySci (Honours)) is a Research Software Engineer at the [Telethon Kids Institute](https://www.telethonkids.org.au/), working with [Professor Nick Golding](https://www.telethonkids.org.au/contact-us/our-people/g/nick-golding/). He was previously a Lecturer in Business Analytics and Statistics at Monash University, working with Professors
[Dianne Cook](http://dicook.org/) and [Rob Hyndman](https://robjhyndman.com/). 
His research aims to improve data analysis
workflow, and make data analysis more accessible.

Nick is a member of the [rOpenSci](https://ropensci.org/) collective, which works to make science open using R, has been the lead organiser for the rOpenSci ozunconf
events from 2016-2018 ([2016](https://auunconf.ropensci.org/), [2017](https://ozunconf17.ropensci.org/), [2018](https://ozunconf18.ropensci.org/)). Outside of research, Nick likes to
hike, rockclimb, kayak, make coffee, take photos, and explore new hobbies.
