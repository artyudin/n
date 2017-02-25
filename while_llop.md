

A while loop statement in Python programming language repeatedly executes a target statement as long as a given condition is true.

Let's create a shopping list:
```
shopping_list = ["milk", "bread","bananas","soda","oranges"]
```

Create a new variable number_of_items and measure(number of items) the length of shopping list
```
number_of_items = len(shopping_list)
```

Use while loop using condition  number_of_items > 0: to remind to buy an item from shopping list, with a nested for loop, decrease number_of_items by 1, every time you run while loop
```
while number_of_items > 0:
    number_of_items -= 1
    for item in shopping_list:
        print ("Do not forget to buy:", item)
```

As we "buy" all items from the shopping list and condition number_of_items == 0, while loop stops iterating 