# group_subclasses
Group level2 subclasses 

Tutorials

Reading and Writing CSV Files in Python https://realpython.com/python-csv/  --reading the data

loops basics https://treyhunner.com/2016/04/how-to-loop-with-indexes-in-python/#range_of_length --- loop

dictionaries basics https://www.w3schools.com/python/python_dictionaries.asp  ---save data in a dictionary

save dictionary to csv https://www.tutorialspoint.com/How-to-save-a-Python-Dictionary-to-CSV-file  ----write the dictionary in a csv file

import csv
my_dict = {'1': 'aaa', '2': 'bbb', '3': 'ccc'}
with open('test.csv', 'w') as f:
    for key in my_dict.keys():
        f.write("%s,%s\n"%(key,my_dict[key]))



