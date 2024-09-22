# python-challenge-1
This is my homework assignment for week 2 - Module 2 Challenge

## Tasks
1. Prompt the user the menu with just the categories

2. Take the category input from the user

3. Prompt the user with the sub menu of the category they have selected

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

    Conditional: If (`y`)
                    keep placing the order
                 if (`n`)
                    Prompt thank you message
                 else:
                    Tell the customer to try again because they didn't type a valid input
