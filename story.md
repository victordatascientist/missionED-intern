## path1- a new person directly going for paid course
* about_missionED
	- utter_intro_to_MissionEd
* about_product
	- utter_explain_product
* course
	- info_form
	- form{"name": "info_form"}
	- form{"name":null}
* price
	- utter_tell_price
* payment	
	- utter_payment_page
* payment_confirmation
	- action_payment_done
* thankyou
	- utter_noworries
* goodbye
	- utter_bye

## path2- a new person opting for free course
* about_missionED
	- utter_intro_to_MissionEd
* about_product
	- utter_explain_product
* course
	- info_form
	- form{"name": "info_form"}
	- form{"name":null}
* free_course
	- utter_ask_interested
* affirm
	- utter_free_course_link
* thankyou
	- utter_noworries
* goodbye
	- utter_bye
	
## path3- a new person enquiring for free course but take a paid course
* about_missionED
	- utter_intro_to_MissionEd
* about_product
	- utter_explain_product
* course
	- info_form
	- form{"name": "info_form"}
	- form{"name":null}
* free_course
	- utter_ask_interested
* deny
	- utter_tell_about_paid_courses
* price
	- utter_tell_price
* payment	
	- utter_payment_page
* payment_confirmation
	- action_payment_done
* thankyou
	- utter_noworries
* goodbye
	- utter_bye

## path4- an existing missionEd customer comes for a new paid course
* course
	- info_form
	- form{"name": "info_form"}
	- form{"name":null}
* price
	- utter_tell_price
* payment
	- utter_payment_page
* payment_confirmation
	- action_payment_done
* thankyou
	- utter_noworries
* goodbye
	- utter_bye
	
## path5- an existing missionEd customer comes for a free course
* free_course
	- utter_ask_interested
* affirm
	- utter_free_course_link
* thankyou
	- utter_noworries
* goodbye
	- utter_bye

## path6- existing customer comes for free and paid course but didn't took both 
* about_missionED
	- utter_intro_to_MissionEd
* about_product
	- utter_explain_product
* course
	- info_form
	- form{"name": "info_form"}
	- form{"name":null}
* free_course
	- utter_ask_interested
* deny
	- utter_tell_about_paid_courses
* course
	- info_form
	- form{"name": "info_form"}
	- form{"name":null}    
* price
	- utter_tell_price
* payment	
	- utter_payment_page
* deny
    - sorry_this_is_not_what_i_wanted
* thankyou
	- utter_noworries
* goodbye
	- utter_bye 

## path7- existing customer comes for paid course but didn't took 
* course
	- info_form
	- form{"name": "info_form"}
	- form{"name":null}
* price
	- utter_tell_price
* payment
	- utter_payment_page
* deny
    - sorry_this_is_not_what_i_wanted
* thankyou
	- utter_noworries
* goodbye
	- utter_bye  

## path8- existing customer comes for free course but didn't took 
* free_course
	- utter_ask_interested
* affirm
	- utter_free_course_link
* deny
    - sorry_this_is_not_what_i_wanted    
* thankyou
	- utter_noworries
* goodbye
	- utter_bye 

## path9- existing customer comes for free and paid course but took both 
* free_course
	- utter_ask_interested
* affirm
	- utter_free_course_link 
* course
	- info_form
	- form{"name": "info_form"}
	- form{"name":null}
* price
	- utter_tell_price
* payment
	- utter_payment_page
* payment_confirmation
	- action_payment_done
* thankyou
	- utter_noworries
* goodbye
	- utter_bye

## path10- a new customer going for paid as well as free course too
* about_missionED
	- utter_intro_to_MissionEd
* about_product
	- utter_explain_product
* course
	- info_form
	- form{"name": "info_form"}
	- form{"name":null}
* price
	- utter_tell_price
* payment	
	- utter_payment_page
* payment_confirmation
	- action_payment_done
* free_course
	- utter_ask_interested
* affirm
	- utter_free_course_link
* thankyou
	- utter_noworries
* goodbye
	- utter_bye

## path10- a new customer going for free as well as paid course but didn't took both
* about_missionED
	- utter_intro_to_MissionEd
* about_product
	- utter_explain_product
* course
	- info_form
	- form{"name": "info_form"}
	- form{"name":null}
* free_course
	- utter_ask_interested
* deny
	- utter_tell_about_paid_courses
* course
	- info_form
	- form{"name": "info_form"}
	- form{"name":null}    
* price
	- utter_tell_price
* payment	
	- utter_payment_page
* deny
    - sorry_this_is_not_what_i_wanted
* thankyou
	- utter_noworries
* goodbye
	- utter_bye 



           


