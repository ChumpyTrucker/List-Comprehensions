# List-Comprehensions
#List, set, dictionary comprenhensen
my_list = [char for char in 'hello']
my_list2 = [num for num in range(0,100000)]
my_list3 = [num**2 for num in range(0,100)]
my_list4 = [even**2 for even in range(0,100) if even %2 ==0]
my_list5 = [odd**2 for odd in range(0,100) if odd %2 ]



#Set comprenhensen
my_listS = {char for char in 'hello'}
my_listS2 = {num for num in range(0,1000)}
my_listS3 = {num**2 for num in range(0,100)}
my_listS4 = {even**2 for even in range(0,100) if even %2 ==0}
my_listS5 = {odd**2 for odd in range(0,109) if odd %2 }


#Dictionary comprenhensen
simple_dict = {
    'a': 1,
    'b': 2
}
my_dict = {key:value**2 for key,value in simple_dict.items()}

my_dict2 = {key:value**2 for key,value in simple_dict.items() if value %2==0}

my_dict3 = {num:num*2 for num in [1,2,3]}

print(my_dict3)
