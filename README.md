# data-scrapping
Piece of code used to scrap meter data from an energy platform website. Using Python and Selenium. 

"""
This module is used to scrap data from eSight website. It takes as input a table extracted from the 'Mass Edit Meters' tab and return
a CSV file with each meter details. When a line does not have any Site.MeterCode it means that the tool did not manage to extracted 
any information. 

Call the start_scrap(input_dataframe) to start the scraping process

Requirements: firefox + selenium library
"""
