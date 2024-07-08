# Project 1: Is Diversity Getting Better in Hollywood? The "Walk of Fame" Would Indicate No
This is my submission for the Lede Program’s Project One - to create a simple chart.

After delving into a massive rabbit hole, I decided to analyze stars on the Hollywood Walk of Fame as a scraping project. Initially, my goal was to find out who had the most stars, but the more data I uncovered, the more I noticed something: the Walk of Fame is very WHITE. This prompted me to dig deeper.

## Data Collection
I first scraped data from Wikipedia’s "List of stars on the Hollywood Walk of Fame." I created a CSV file with the names, categories, and dates of the stars. Then, I scraped data from the Hollywood Walk of Fame webiste, filtering by race. Using Excel, I matched the names to their corresponding races. I combined Caucasian and Australian into “white,” African Americans I combined with “Black.”  For about 300 names that lacked race information, I had to manually enter the details by Googling the person or group. Cartoon characters, magazines, restaurants, events, etc., were labeled as N/A.
## Links: 
* https://en.wikipedia.org/wiki/List_of_stars_on_the_Hollywood_Walk_of_Fame
* https://walkoffame.com/

## Findings
My findings indicate that the Hollywood Walk of Fame is predominantly white and heavily favors the motion picture industry.

## Tools and Techniques
- Python: Used in a Jupyter Notebook for data analysis.
- BeautifulSoup: Utilized for web scraping.
- Excel: Assisted in matching names and races.
- Pandas: Employed for data manipulation and analysis.
- Matplotlib/ggplot/DataWrapper: Used to create visualizations, although not all charts were included in the final webpage.
  
## Skills and Growth
This project significantly improved my scraping skills and techniques. Scraping multiple tables is challenging, but I completed the task.

## Future Work
Given more time, I would like to visualize changes over time, particularly in the last 10 years, to see if people of color are receiving more stars on the Walk of Fame. It would also be interesting to investigate who is paying the hefty price tag of $78,000 for a star. Also I would like to see who is on the committee to approve the nominations. 

## Project Page
You can view the project here: https://jsorrell99.github.io/Project1/
