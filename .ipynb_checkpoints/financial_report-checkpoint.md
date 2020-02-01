1. Budget Analysis: Summarize the transaction data from the budget analysis and include images for each chart and table produced.
2. Retirement Planning: Summarize the retirement portfolio analysis and include the charts for the Monte Carlo simulation.

## Below is a list of Categories for each transaction, with the first category being selected when there is multiple categories:
special: |Travel
special: |Travel
place: |Food and Drink
special: |Payment
place: |Food and Drink
place: |Shops
special: |Payment
special: |Travel
special: |Transfer
special: |Transfer
place: |Recreation
special: |Travel
place: |Food and Drink
place: |Food and Drink
place: |Food and Drink
special: |Transfer
special: |Travel
special: |Travel
place: |Food and Drink
special: |Payment
place: |Food and Drink
place: |Shops
special: |Payment
special: |Travel
special: |Transfer
special: |Transfer
place: |Recreation
special: |Travel
place: |Food and Drink
place: |Food and Drink
place: |Food and Drink
special: |Transfer
special: |Travel
special: |Travel
place: |Food and Drink
special: |Payment
place: |Food and Drink
place: |Shops
special: |Payment
special: |Travel
special: |Transfer
special: |Transfer
place: |Recreation
special: |Travel
place: |Food and Drink
place: |Food and Drink
place: |Food and Drink
special: |Transfer
special: |Travel

## Using pandas to avoid loops is faster, but this can't pick up one single category from several categories.

   transaction_type                                    category
0           special    [Travel, Airlines and Aviation Services]
1           special                              [Travel, Taxi]
2             place               [Food and Drink, Restaurants]
3           special                                   [Payment]
4             place    [Food and Drink, Restaurants, Fast Food]
5             place                     [Shops, Sporting Goods]
6           special                      [Payment, Credit Card]
7           special                              [Travel, Taxi]
8           special                           [Transfer, Debit]
9           special                         [Transfer, Deposit]
10            place      [Recreation, Gyms and Fitness Centers]
11          special    [Travel, Airlines and Aviation Services]
12            place    [Food and Drink, Restaurants, Fast Food]
13            place  [Food and Drink, Restaurants, Coffee Shop]
14            place               [Food and Drink, Restaurants]
15          special                          [Transfer, Credit]
16          special    [Travel, Airlines and Aviation Services]
17          special                              [Travel, Taxi]
18            place               [Food and Drink, Restaurants]
19          special                                   [Payment]
20            place    [Food and Drink, Restaurants, Fast Food]
21            place                     [Shops, Sporting Goods]
22          special                      [Payment, Credit Card]
23          special                              [Travel, Taxi]
24          special                           [Transfer, Debit]
25          special                         [Transfer, Deposit]
26            place      [Recreation, Gyms and Fitness Centers]
27          special    [Travel, Airlines and Aviation Services]
28            place    [Food and Drink, Restaurants, Fast Food]
29            place  [Food and Drink, Restaurants, Coffee Shop]
30            place               [Food and Drink, Restaurants]
31          special                          [Transfer, Credit]
32          special    [Travel, Airlines and Aviation Services]
33          special                              [Travel, Taxi]
34            place               [Food and Drink, Restaurants]
35          special                                   [Payment]
36            place    [Food and Drink, Restaurants, Fast Food]
37            place                     [Shops, Sporting Goods]
38          special                      [Payment, Credit Card]
39          special                              [Travel, Taxi]
40          special                           [Transfer, Debit]
41          special                         [Transfer, Deposit]
42            place      [Recreation, Gyms and Fitness Centers]
43          special    [Travel, Airlines and Aviation Services]
44            place    [Food and Drink, Restaurants, Fast Food]
45            place  [Food and Drink, Restaurants, Coffee Shop]
46            place               [Food and Drink, Restaurants]
47          special                          [Transfer, Credit]
48          special    [Travel, Airlines and Aviation Services]