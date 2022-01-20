# Convert my hourly wage to an equivalent annual salary

hourly_wage = input("What is your salary per hour?")

worked_hours_per_week = input("How many hours do you work per week(1-80)?")

work_weeks_per_year = input("How many weeks do you work per week (1 to 52)?")

annual_salary = float(hourly_wage) * float (worked_hours_per_week) * float(work_weeks_per_year)

print("Your annual salary is " + str(annual_salary))
