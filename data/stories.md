
## happy path
* greet
  - utter_greet
* goodbye
  - utter_bye

  

## story  2
* order_pizza
  - utter_ask_size
* order_pizza{"size":"large", "size":"medium", "size":"small"}
  - utter_ask_type
* order_pizza{“pizza_type”:“bacon cheeseburger” , “pizza_type”:“BBQ” , “pizza_type”:“cheese” , “pizza_type”:"Hawaaiian”}
  - utter_ask_toppings
* deny
  - utter_confirm_order1
* thanks
  - utter_bye
  
## story order 4
* greet
  - utter_greet
* order_pizza
  - utter_ask_size
* order_pizza{"size":"large", "size":"medium", "size":"small"}
  - utter_ask_type
* order_pizza{“pizza_type”:“bacon cheeseburger” , “pizza_type”:“BBQ” , “pizza_type”:“cheese” , “pizza_type”:"Hawaaiian”}
  - utter_ask_toppings
* affirm
  - utter_name_toppings
* order_pizza{"topping":"cheese", "topping":"olives", "topping":"pepperoni", "topping":"onions", "topping":"tomatoes", "topping":"corn"}
  - utter_confirm_order1
* thanks
  - utter_thanks
  
## story order 5
* greet
  - utter_greet

* thanks 
  - utter_thanks