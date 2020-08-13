## Project Name
> Linkedin/glassdoor scraping

### General info
* Scraping linkedin webpage for jobs defined in start_url
* Writing results to pandas df
    * df is saved to _*.h5_ file for later use/comparison
    * example: _linkedin-Wednesday08July202007-11-28-01.h5_
* At the end there is comparison of most recent scraping and present status diffrence is displayed so the user has nice summary


### Technologies
* Python, 
* BeautifulSoup, 
* pandas, 
* re

### Setup
easiest is to have conda environment with jupyter lab or jupyter notebook and mentioned libraries
or just make  stanalone .py file based on the functions in notebook


### Status
Project is: _in progress_ 

> glassdoor-scrap_RevB.ipynb 13_08-2020
Glassdoor changed the structure of the webpage a bit.
To be able  create summary of of weblinks there is a small change in scrapping part:   

>class _"jobInfoItem jobTitle css-13w0lq6 eigr9kq1 jobLink"_ is used to find joblinks.
There are some extras like saving results of comparison to md files for quick review

### Other information
Notebook is divided on universal fuctions whicht except scrapping part could be easlily used elsewhere.




### Contact
Created by: _len.sla_

