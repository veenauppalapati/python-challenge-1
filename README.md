# python-challenge-1
This is my homework assignment for week 2 - Module 2 Challenge

## Tasks
1. Prompt the user the menu with just the categories

```
Welcome to the variety food truck.
From which menu would you like to order? 
1: Snacks
2: Meals
3: Drinks
4: Dessert
```

2. Take the category input from the user

3. Prompt the user with the sub menu of the category they have selected

```
What Snacks item would you like to order?
Item # | Item name                | Price
-------|--------------------------|-------
1      | Cookie                   | $0.99
2      | Banana                   | $0.69
3      | Apple                    | $0.49
4      | Granola bar              | $1.99
```

4. Take the order input of the `menu_selection`

5. Add the menu selection into the order

6. Ask the user if they would like to keep placing the order

7. Display the order list to the user

```

Item name                 | Price  | Quantity
--------------------------|--------|----------
Apple                     | $0.49  | 1
Tea - Thai iced           | $3.99  | 2
Fried banana              | $4.49  | 3

```

8. Display the total cost of the order to the user



## Sequence
1. Event 1 : Place the order

    Conditional: 
    
    If (`y`)
                    
        keep placing the order

    if (`n`)
        
        Prompt thank you message

    else:
        
        Tell the customer to try again because they didn't type a valid input
