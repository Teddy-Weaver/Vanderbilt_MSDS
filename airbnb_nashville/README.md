# Airbnb Nashville
Create a polished 'slidedoc', aimed at a targeted audience, that analyzes a data set of your choosing. This slidedoc should clearly present a hypothesis and analysis of a real-world problem for your audience.

**Purpose**
Over the past several years, Nashville has been one of the fastest growing cities in the county. A side effect of this growth is that hotels have reached $300-$500 per night for a room. Many tourists and visitors are resorting to short-term rentals With over 7,000 listings, how do you pick the right one?

**Audience**
General consumers, in particular those not very familiar with short-term rentals (Airbnb, VRBO, etc.), looking to stay in Nashville. We assumed they are not intimately familiar with the area and have no strong inclinations about where to stay.

### Partners
[Rastko Stojin](https://github.com/ok-tsar)

[Shaswat Rajput](https://github.com/shaswat01)


### About the Data
Unofficial Airbnb data for the Nashville-metro area was created by [Inside Airbnb](http://insideairbnb.com). Available data includes publicly available property listings and reviews as of 9/20/19.
On their website, Inside Airbnb does call out significant caveats related to their collected data. Below are a few of the most important ones relative to our analysis.
* Calendar Data: Data is sourced from the Airbnb calendar. This does not differentiate between a booked night and an unavailable night. In addition, this is dependent on a Host keeping this calendar up to date.
** Due to these factors, we did not use the Calendar data set or availability data in the Listing data.
* Price: Unclear how this was collected, as price varies signfiicantly based on day of the week, holidays, etc.

For our analysis, we focused on listing data. If we were to expand or continue our analysis we would also perform a textual analysis of property reviews.

### Technology Used 
* R (tidyverse, ggplot2, ggcorplot, stringr)
* Tableau


### Description of files
airbnb_nashville.rmd - Working document for analysis and vizualziations
presentation.pdf - Completed presentation
