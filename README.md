python home work
# Type your code 
print("Davy's auto shop services")
print('Oil change -- $35')
print('Tire rotation -- $19')
print('Car wash -- $7')
print('Car wax -- $12')
print()
service1 = input('Select first service:\n')
service2 = input('Select second service:\n')
print()
print("Davy's auto shop invoice")
print()
if service1 == 'Oil change':
    print('Service 1: Oil change, $35')
    cost1 = 35
elif service1 == 'Car wax':
    print('Service 2: Car wax, $12')
    cost1 = 12
elif service1 == 'Tire rotation':
    print('Service 1: Tire rotation, $19')
    cost1 = 19
elif service1 == 'Car wash':
    print('Service 1: Car wash, $7')
    cost1 = 7
elif service1 == '-':
    print('Service 1: No service') 
    cost1 = 0
else:
    print('done')
    
if service2 == 'Oil change':
    print('Service 2: Oil change, $35')
    cost2 = 35
elif service2 == 'Car wax':
    print('Service 2: Car wax, $12')
    cost2 = 12
elif service2 == 'Tire rotation':
    print('Service 2 : Tire rotation, $19') 
    cost2 = 19
elif service2 == 'Car wash':
    print('Service 2: Car wash, $7')
    cost2 = 7
elif service2 == '-':
    print('Service 2: No service')
    cost2 = 0
else:
    print('done')
    #abc
print()
print('Total:', '$'+str(cost1 + cost2))
