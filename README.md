# 5.3 LAB*: Program: Automobile service invoice
This is a zybook project of automotive services and the corresponding cost of each service
## Getting Started
I am using Pycharm on my local machine to execute the code before submit on zybook
### Prerequisites
Program: Davy's auto shop invoice  (https://learn.zybooks.com/zybook/RTCCNA336DaySpring2020/chapter/5/section/3)
## Running
```
After download pycharm follow the next step:
```
```
Run the exe for install Pycharm. Then click next
On the next screen, you can change or leave as default the path location
On the next scree, you could create a desktop shortcut ither for 32 or 64-bit launcher. Then click next
On the Choose Start Menu folder select JetBrain and click on Install
Once installation finish you should a receive a message that pycharm is installed.
Select the Run Pycharm Community Edition box, then click on finish
After click on Finish you can selec create New project
```
## To execute the code Program: Davy's auto shop invoice
Copy the following code
```
#This code represents the input from user
print("Davy's auto shop services")
print('Oil change -- $35')
print('Tire rotation -- $19')
print('Car wash -- $7')
print('Car wax -- $12')
```
```
#Output a menu of automotive services and the corresponding cost of each service.
print()
```
```
#Output an invoice for the services selected. Output the cost for each service and the total cost.
service1 = input('Select first service:\n')
service2 = input('Select second service:\n')
print()
print("Davy's auto shop invoice")
print()
```
```
#Extend the program to allow the user to enter a dash (-), which indicates no service.
if service1 == 'Oil change':
    print('Service 1: Oil change, $35')
    cost1 = 35
```
```
#Select first service:
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
```
```
#Select the second service:
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
```
```
#Davy's auto shop invoice
print()
print('Total:', '$'+str(cost1 + cost2))
```
## Inputs:
```
Oil change
Car wax
```
## Output
```
Davy's auto shop services
Oil change -- $35
Tire rotation -- $19
Car wash -- $7
Car wax -- $12

Select first service:
Select second service:

Davy's auto shop invoice

Service 1: Tire rotation, $19
Service 2: No service

Total: $19
```
## Thanks
Thanks for your attention
