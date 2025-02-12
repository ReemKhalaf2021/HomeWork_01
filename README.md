Task Description:

The task of this lecture is to develop a Python system that generates all possible meal combinations based on input lists of main dishes, side dishes, beverages, and desserts.
> Make sure to practice this lecture’s topic by using comprehension whenever possible.
> 
Inputs:
Template (String with placeholders)
Main Dishes (List of Strings)
Side Dishes (List of Strings) - Optional
Beverages (List of Strings) - Optional
Desserts (List of Strings) - Optional

Output:

A list of strings representing all possible meal combinations formatted according to the provided template, including available inputs.
Example 1:

template = "{main_dish} paired with {side_dish}, {beverage}, and {dessert}"
main_dish = ['Roasted duck', 'Mushroom risotto', 'Lobster tail']
side_dish = ['Truffle fries', 'Quinoa salad', 'Garlic spinach']
beverage = ['Orange juice', 'Sparkling water', 'Artisanal soda']
dessert = ['Crème brûlée', 'Panna cotta', 'Macarons']

output = [

    "Roasted duck paired with Truffle fries, Orange juice, and Crème brûlée",
    "Roasted duck paired with Truffle fries, Orange juice, and Panna cotta",
    "Roasted duck paired with Truffle fries, Orange juice, and Macarons",
    ...
]
Example 2:

template = "{main_dish} accompanied by {side_dish} and {dessert}"
main_dish = ['Stuffed peppers', 'Tofu stir-fry']
side_dish = ['Herb couscous', 'Roasted vegetables']
dessert = ['Lemon tart', 'Berry sorbet']

output = [

   "Stuffed peppers accompanied by Herb couscous and Lemon tart",
   "Stuffed peppers accompanied by Herb couscous and Berry sorbet",
   "Stuffed peppers accompanied by Roasted vegetables and Lemon tart",
    ...
]
