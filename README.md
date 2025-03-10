# mod11-challenge

All work and solutions for the Module 11 HTML Scraping challenge are contained in this repo. 

## Part 1

Part 1 involves scraping news titles off of a webpage full of articles. All titles and previews are succesfully scraped and placed into a dictionary. 

## Part 2

Part 2 involves a little more data work. This section focuses on the climate data (min temp and pressure) for Mars over a period of about 3 Martian years. Data was scraped and cleaned, and then the analysis began. 

### Temperature

Firstly, the Average Minimum Temperature was analyzed. This lead to realizing that the first 6 months of the Martian year are (on average) colder than the last 6 months. Extrapolation from this data, assumptions can be made that Mars' Perihelion is likely in the 8th month, and its Aphelion is likely in the 3rd. 

### Pressure

Pressure showed no similar patterns to temperature. While there does appear to be a cycle of pressure, it is not as clear cut as temperatures cycle. Monthly pressure begins high, moving higher until the middle of the year, where it crashes down to its yearly low in the 6th month. Then, it jumps back up to its peak in the 9th month before falling down to the middle of the graph in the 11th and 12th months. After this, assuming this is indeed a yearly trend, the pattern would start over. 

### Year Length

A quick look at all observations for min temp in the data set can give a pretty good estimate of Martian year length. The estimate derived from the graph was a 660 Earth day orbital period, which lines up pretty closely with the actual figure of a 687 Earth day rotational period. [Source: Nasa](https://science.nasa.gov/mars/facts/#:~:text=A%20year%20on%20Mars%20lasts,its%20orbit%20around%20the%20Sun.)
