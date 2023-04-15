# practice-1
inventory = {'apple': 10, 'banana': 5, 'orange': 20, 'grape': 15}

max_key = max(inventory, key=inventory.get)
min_key = min(inventory, key=inventory.get)

print("Key with maximum value:", max_key)
print("Key with minimum value:", min_key)
