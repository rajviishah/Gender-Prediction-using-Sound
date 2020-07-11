# Gender-Prediction-using-Sound
Analyzed the gender distribution of children's book writers(dataset) and use sound name matching to match names to gender.

Project Name: Gender Prediction using Sound
Programming language: Python
Python libraries used: Pandas,NumPy, Matplotlib and fuzzy
Purpose of the project: To understand and implement pandas, numpy and matplotlib for real-time data.

Project Description:

Gray and grey, colour and color, or Mark and Marc all are pronounced in the same way, while having different spellings or meanings. There are many words that are pronounced the same way but have different spellings. While it is easy for us to realize their equivalence, basic programming commands will fail to equate such two strings.

In this project, gender of the author is predicted on the basis of the sound of his/her first name using Fuzzy(https://pypi.org/project/Fuzzy/). 
1) nytkids_yearly.csv contains data of children's book authors. Firstly, from this csv file, first name of authors were analyzed and then using fuzzy.nysiis()- sound matching was done. There are more chances of more first names than fuzzy first names.  
2) babynames_nysiis.csv contains gender distribution as the percentage of times the name appeared as a female name and the percentage of times it appeared as a male name. So, if percentage of female is more than percentage of male than that name will be considered as female's name and vice versa. With same percentage value, the name will be considered as neutral.
3) Now, both csv files are compared so that author's name can be predicted from another csv file(babynames_nysiis.csv) and if the name was not found then it was categorized as unidentified.
4) Finally, data was analyzed and represented as Male, Female and Uncategorized.
5) To showcase author by gender(male and female), graph was plotted with number of females and male numbers with respective years. 

Challenge:
Few author’s name is categorized as unidentified due to data collection limitation(it is collected from social security of US and it may possible that unidentified authors are foreigners).
