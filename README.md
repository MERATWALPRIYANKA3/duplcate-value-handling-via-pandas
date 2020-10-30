# duplcate-value-handling-via-pandas
#how to handle duplicate vale in a csv file using pandas

df = pd.read_csv('file.csv')

#checking for duplicated values

df.duplicated()

#duplicate value in a specific column

df.duplicated('colum')

#remove all the duplicates

df.drop_duplicates()

#droping from a specific column

df.drop_duplicates(['column'])
