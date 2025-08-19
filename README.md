# list to sub list only having even numbers

def func1(): # function definition
  num = [-2,3,-1,-4,1,5,6]
  even_list = []
  for x in num:
    if x % 2 == 0:
      even_list.append(x)
  print(even_list)

func1() # function call



def func3(num):
  even_list = []
  for x in num:
    if x % 2 == 0:
      even_list.append(x)
  return even_list

even_list1 = func3(num1)
even_list2 = func3(num2)

print(even_list1)
print(even_list2)
