**Previous Titanic project:**

''' 
df_original = pd.read_csv('../dataset/train.csv')
df_unclean = df_original.copy()
df = df_unclean.dropna()
print(df) 
'''

This data got rid of any values that did NOT have a value. However, upon finding the results of the data, the results were baffling
Due to my limited knowledge of programming, I did not realise that 70% of data would be excluded
This led to some hilarious findings such as the average person being more likely to survive the titanic than not by a factor of 3

***Current Titanic Project Notes***
This project has been started in a different manner by checking the data beforehand using **.info()**, allowing me to make changes based on WHAT data is missing in the first place.

This project aims to find the likely hood of any particular person surviving the titanic, with the aim to create *my first ever machine learning project* that can do it for me