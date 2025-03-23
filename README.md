# python-week-2-assign
# Create an empty list
my_list = []

# Append elements to the list
my_list.append(10)
my_list.append(20)
my_list.append(30)
my_list.append(40)

# Insert 15 at the second position in the list
my_list.insert(1, 15)

# Extend the list with another list [50, 60, 70]
my_list.extend([50, 60, 70])

# Remove the last element from the list
my_list.pop()

# Sort the list in ascending order
my_list.sort()

# Find and print the index of the value 30
index_of_30 = my_list.index(30)
print(f"The index of 30 in my_list is: {index_of_30}")

# Print the final state of the list
print("Final list:", my_list)
