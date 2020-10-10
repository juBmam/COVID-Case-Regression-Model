Metis Project 2: COVID-19 Case Study per County by Julian Cheng
In this project, I scraped data from multiple sites using Beautifulsoup
and Selenium to get the data that I needed, which was county-wide 
statistics that could help me model COVID cases. This originated from 
sites such as the US Census, Department of Agriculture, among other 
medical databases. This data was then used as features (Density, Urban
Index, Vulnerable Populations, Unemployment Rate, Median Household 
Income, Political Party Distribution), while COVID Cases per 100K
individuals per county was the target. Sources are listed in the
Appendix of the presentation. I used Seaborn, Matplotlib, Yellowbrick,
Sklearn, Selenium, BeautifulSoup, and various Regression models.
This project's impact is limited by its static model. It can only
predict a region to be a COVID hotspot or various degrees. Dynamic time
seris exist on the internet, using data on a continuous scale, making 
my data far less relevant, although I think that the use of readily
available and understandable data without medical knowledge is a 
great benefit.