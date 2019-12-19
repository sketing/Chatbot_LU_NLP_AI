## happy path
* greet
  - utter_greet
* pizza_list
  - utter_pizza_list
* pizza_chosen
  - utter_ask_more

## sad path 1
* greet
  - utter_greet
* mood_unhappy
  - utter_cheer_up
  - utter_did_that_help
* affirm
  - utter_happy

## sad path 2
* greet
  - utter_greet
* mood_unhappy
  - utter_cheer_up
  - utter_did_that_help
* deny
  - utter_goodbye

## order path 1
* greet
 - utter_greet
* product_add
 - product_add
 - utter_did_that_help
* affirm
  - utter_happy

## say goodbye
* goodbye
  - utter_goodbye

## bot challenge
* bot_challenge
  - utter_iamabot