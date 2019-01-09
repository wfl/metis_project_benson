

Back Story
An email from a potential client:
Vinny & Julia -
It was great to meet with you and chat at the event where we recently met and had a nice chat. We’d love to take some next steps to see if working together is something that would make sense for both parties.
As we mentioned, we are interested in harnessing the power of data and analytics to optimize the effectiveness of our street team work, which is a significant portion of our fundraising efforts.
WomenTechWomenYes (WTWY) has an annual gala at the beginning of the summer each year. As we are new and inclusive organization, we try to do double duty with the gala both to fill our event space with individuals passionate about increasing the participation of women in technology, and to concurrently build awareness and reach.
To this end we place street teams at entrances to subway stations. The street teams collect email addresses and those who sign up are sent free tickets to our gala.
Where we’d like to solicit your engagement is to use MTA subway data, which as I’m sure you know is available freely from the city, to help us optimize the placement of our street teams, such that we can gather the most signatures, ideally from those who will attend the gala and contribute to our cause.
The ball is in your court now—do you think this is something that would be feasible for your group? From there we can explore what kind of an engagement would make sense for all of us.
Best,
Karrine and Dahlia
WTWY International
Data:
* MTA Data (Google it!)
* Additional data sources welcome!
Skills:
* python and pandas
* visualizations via Matplotlib & seaborn
Analysis:
* Exploratory Data Analysis
Deliverable/communication:
* Group presentation (4-5 people per)
* slide presentation
* visual and oral communication in group presentations
* organized project repository
We are very excited to see what you will learn and do for Project Benson!


Goal
* WomenTechWomenYes (WTWY) has an annual gala at the beginning of the summer each year. As we are new and inclusive organization, we try to do double duty with the gala both to fill our event space with individuals passionate about increasing the participation of women in technology, and to concurrently build awareness and reach.

Questions
* What are the qualities of people who are interested in increasing participation of women in tech?
    * Location/neighborhood of people who are interested in.
    * Neighborhoods with lots of tech companies
    * Meetups for tech company or women in tech events
    * Where are a lot of women
    * Locations near universities, colleges, etc.
* Tech centers in NYC?
* Universities in NYC?
* Software/tools
    * Heat maps
    * Addresses in radius of other addresses
Observations
* Totals are determined by the difference between the entries in the ENTRIES and EXITS columns.
* This will be a little tricky b/c to find the total for a particular day you need all of the dates on that day and the first 00:00:00 entry of the next day.
* Also the tabulations need to be done by STATION and SCP together to find the totals for a particular station. We then need to split by date and map over the course of each week and then over the course of the entire 7 weeks.
    * SCP is unique by station and seems to determine the individual turnstiles at a station.
* There are 40k unique time values so we should set time values for intervals if we're curious about times of high traffic.
* Will need to convert the time column to time series.
My Questions
* What are the qualities of people who tend to be interested? Students, people in tech, anyone else?
    * Donors, participants
    * Early summer gala
* Do we have to collect emails? Could we do handouts?
* When do you need to have the street team deployed?
    * Ok to make our assumption
Approach
* Decide on time frame before the event.
* Move the positioning from entrances to inside the station where people are waiting for their trains.
* Find the stations with the most and most relevant traffic.
    * Find stations with most traffic.
    * Curate based on other factors (schools, tech, etc)
    * Top 5 - 10?
        * Curated from top ~20
