import random
num1 = ['A','B','C','D','E','F','G','H']
office = [[],[],[]]
i = 1
for name in num1:
    num2 = random.randint(0,2)
    (office[num2].append(name))
for offices in office:
     print(f'办公室{i}人数是{len(office)},老师叫;')
     for name in offices:
         print(name)
     i += 1
