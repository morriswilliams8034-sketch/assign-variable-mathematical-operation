# assign-variable-mathematical-operation
Create a solution that accepts three integer input representing the number of times an explain travel to job sites. 
employee_a_miles = 15.62
employee_b_miles = 41.85
employee_c_miles = 32.67

a_trips = int(input("Enter trips: "))
b_trips = int(input("Enter trips 2:"))
c_trips = int(input("Enter trips 3:"))

total_mileage = (employee_a_miles * a_trips) + (employee_b_miles * b_trips) + (employee_c_miles * c_trips)
print(f"The total mileage is {total_mileage:.2f} for the three of them")
