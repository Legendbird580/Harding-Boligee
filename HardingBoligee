import secrets
# opening the file in read mode 
my_file = open("familynames-usa-top1000.txt", "r") 
my_other_file = open("us-cities.txt", "r") 
data = my_file.read() 
datae = my_other_file.read()
data_into_list = data.split("\n") 
dataeintolist = datae.split("\n")
dataeintolist=list(map(str.upper, dataeintolist))
print(secrets.choice(data_into_list), secrets.choice(dataeintolist))
my_file.close() 
