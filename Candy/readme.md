### Candy Clean-up

#### Objective
Clean up a candy survey data I found. The main issue I found is when the survey was conducted they did not limit some answers nor did they specify the input class/type. So a fairly simple variable like 'Age' should most likely be less than 100 and averaging about two digits, unfortunately all numeric answers are strings/characters coupled with answers of pure text or an absurd age or nothing at all. 

Instead of dropping all those records, we could assume some people are not comfortable giving their age or they just wanted a laugh. In that case the rest of their answers may be legitimate, but I would like to denote them somehow.

There was also a lot of missing data, so where appropriate I wanted to remove those columns.

JOY/DESPAIR can be considered as a factor or revalues to +1/-1 respectively and 0 for NULL, but to keep most of the data intact to the original I may leave it. Some programs will be able to just make a count of each, i.e. JOY/NA/DESPAIR, others may need that extra formatting step.

After adjusting I will export the new data as an excel/spreadsheet file.

#### Practicing
All of this is done is R-Studio, using Markdown syntax in a rmd file but also implementing html formatting directly into the rmd file (pre-knit). So other than R code, I use markdown and html.
