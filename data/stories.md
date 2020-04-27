## happy path 1
* greet_es
  - utter_greet_es
  - utter_ask_business_name_es
* affirm_es
  - utter_ask_business_address_es
* affirm_es
  - utter_thanks_es
  - utter_goodbye_es

## happy path 2
* greet_es
  - utter_greet_es
  - utter_ask_business_name_es
* deny_es
  - utter_ask_business_address_es
* affirm_es
  - utter_thanks_es
  - utter_goodbye_es

## unhappy path 1
* greet_es
  - utter_greet_es
  - utter_ask_business_name_es
* deny_es
  - utter_ask_business_address_es
* deny_es
  - utter_thanks_es
  - utter_goodbye_es

## bot challenge 1
* greet_es
  - utter_greet_es
  - utter_ask_business_name_es
* bot_challenge
  - utter_iamabot
* goodbye_es
  - utter_goodbye_es

## say goodbye
* goodbye_es
  - utter_goodbye_es

## bot challenge
* bot_challenge_es
  - utter_iamabot_es
