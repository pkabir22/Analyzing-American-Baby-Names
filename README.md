# Analyzing American Baby Names

Recently one of my friends moved to the US from Germany. When she arrived here, she was pregnant. On a casual chat, she asked for a baby name. She wanted to pick an American baby name for her little special. 



I wanted to be a niche and logical on my suggestion. So, I collected a dataset of American baby names since 1920 from the US Social Security Administration, which lists first names along with the number and sex of babies they were given to in each year. For processing speed purposes, I've limited the dataset to first names which were given to over 5,000 American babies in a given year. 

The [dataset](https://drive.google.com/drive/u/0/folders/17gzNfF-zC2Yo7pUzwS2VFbPSell9SCvz) features year (year of baby name records), first_name (first names of the babies), sex (sex of the baby given that first name) and num (number of babies with a particular first name).

My primes task were to find which female and male baby names were mostly used over the years in the United States, which boy names were mostly used and for low many years, which girl names ending in 'a' had been popular in the recent years. 

I analyzed the dataset in PostgreSQL and the query can be found [here](https://github.com/pkabir22/Analyzing-American-Baby-Names/blob/main/notebook.ipynb)


