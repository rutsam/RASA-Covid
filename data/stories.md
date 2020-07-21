## story_goodbye
* goodbye
    - utter_goodbye

## story_thankyou
* thankyou
    - utter_noworries
	
## going_to_rusizi_simple
* greet{"name_bot": "Mbaza"}  
    - utter_greetings
	- utter_introduction
	- utter_mytask
* visit_rusizi_district{"particular_location": "rusizi","district_rusizi": "district"}
    - utter_response_on_rusizi

## going_to_rusizi_long_affirmative
* greet{"name_bot": "Mbaza"}
    - utter_greetings
	- utter_introduction
	- utter_mytask
* visit_rusizi{"particular_location": "rusizi"}
    - utter_confirm_district
* affirmative
    - utter_response_on_rusizi

## going_to_rusizi_long_negative
* greet{"name_bot": "Mbaza"}
    - utter_greetings
	- utter_introduction
	- utter_mytask
* visit_rusizi{"particular_location": "rusizi"}
    - utter_confirm_district
* negative
    - utter_free_to_travel
	