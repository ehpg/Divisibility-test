# Divisibility-test
Finding numbers in a range than divide by 7 but not by 5

list=[]

for i in range(2000, 3200):
	if (i%7 == 0 and i%5 != 0):
		list.append(i)

print(list)

