# Lab1.py
# IT1114
# Dan Suero
# Lab1
# Due Date: 01/19/25
# Purpose: This program is able to calculate the amount and cost of purchasing flooring, no matter the inputs or outputs.
# Resources used: my notes from 1114 and intro python Youtube videos

# Get user input
length = float(input("enter the length of the room in feet"))
width = float(input("enter the width of the room in feet"))
cost_per_sqft = float(input("enter the cost of flooring per square foot"$))
# ^ First the program takes input from the user for room length, width, and flooring cost per sqft.

# Calculate the total square feet
total_sqft = length x width
# ^ Here the program finds the total sqft by multiplying length times width

# Calculate the cost of flooring
flooring_cost = total_sqft x cost_per_sqft
# ^ Then we get the flooring cost by multiplying total squarefeet by the cost per squarefoot

# Calculate the tax
tax = flooring_cost x 0.07 (7%)
# ^ we get the tax from multiplying the flooring cost by the tax percentage

# Calculate total amount due
total_amount_due = flooring_cost + tax
# ^ Here the program will calculate the total amount by adding the tax to the flooring cost

# Get user output
print("Total square feet needed: {total_sqft}")
print("calculated cost of flooring: ${flooring_cost}")
print("tax amount: ${tax}")
print("total amount due: ${total_amount_due}")
# ^ Finally, the program will display the output results, showing total square feet needed, flooring cost, tax amount, and the total amount due from those numbers.
