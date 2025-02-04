# practice
# Exercise 3.1 Rewrite your pay computation to give the employee 1.5 times the hourly rate for hours worked above 40 hours.
# Enter Hours: 45
# Enter Rate: 10
# Pay: 475.0
# Exercise 3.2 Rewrite your pay program using try and except so that your program handles non-numeric input gracefully by printing a message and exiting the
# program. The following shows two executions of the program:
# Enter Hours: 20
# Enter Rate: nine
# Error, please enter numeric input
# Enter Hours: forty
# Error, please enter numeric input

try:
    base_hours = (float(input('Enter hours')))
    base_rate = (float(input('Enter rate')))
    baseline_pay = base_hours * base_rate
    additional_hours = base_hours-40
    additional_rate= base_rate*1.5
    additional_pay= additional_hours*additional_rate
    corrected_base_pay= baseline_pay - (additional_hours * base_rate) 
    total_additional_pay = corrected_base_pay + additional_pay
    if base_hours > 40:
        print (total_additional_pay)
    else:
        print (baseline_pay)
except:
    print ('Enter a number')
