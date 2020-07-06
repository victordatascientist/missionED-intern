## path1- a new person directly going for paid course
* about_missionED
	- utter_intro_to_MissionEd
* about_product
	- utter_explain_product
* registration
	- info_form
	- form{"name": "info_form"}
	- form{"name":null}
* course
	- show_courses_form
	- form{"name": "show_courses_form"}
	- form{"show_courses_form":null}
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
* registration
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
* free_course
	- utter_ask_interested
* deny
	- utter_tell_about_paid_courses
* registration
	- info_form
	- form{"name": "info_form"}
	- form{"name":null}
* course
	- show_courses_form
	- form{"name": "show_courses_form"}
	- form{"show_courses_form":null}
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
* registration
	- info_form
	- form{"name": "info_form"}
	- form{"name":null}
* course
	- show_courses_form
	- form{"name": "show_courses_form"}
	- form{"show_courses_form":null}
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
	
## path6- A person comes to just enquire about the courses offered
* greet
	- utter_greet
* about_missionED
	- utter_intro_to_MissionEd
* about_product
	- utter_explain_product
* price
	- utter_tell_price
* free_course	
	- utter_ask_interested
* affirm	
	- utter_free_course_link
* thankyou
	- utter_noworries
* goodbye
	- utter_bye

## path7- A person coming to enquire about the paid courses
* greet	
	- utter_greet
* about_missionED
	- utter_intro_to_MissionEd
* about_product
	- utter_explain_product
* free_course
	- utter_ask_interested
* deny
	- utter_tell_about_paid_courses
* price
	- utter_tell_price
* thankyou
	- utter_noworries
* goodbye
	- utter_bye

## path8- new customer comes for free and paid course but didn't took both 
* about_missionED
	- utter_intro_to_MissionEd
* about_product
	- utter_explain_product
* registration
	- info_form
	- form{"name": "info_form"}
	- form{"name":null}
* free_course
	- utter_ask_interested
* deny
	- utter_tell_about_paid_courses
* course
	- show_courses_form
	- form{"name": "show_courses_form"}
	- form{"show_courses_form":null}
* price
	- utter_tell_price
* payment	
	- utter_payment_page
* deny
    - utter_we_will_come_with_new_courses
* thankyou
	- utter_noworries
* goodbye
	- utter_bye 

## path9- existing customer comes for paid course but didn't took 
* course 
	- show_courses_form
	- form{"name": "show_courses_form"}
	- form{"show_courses_form":null}
* price
	- utter_tell_price
* payment
	- utter_payment_page
* deny
    - utter_we_will_come_with_new_courses
* thankyou
	- utter_noworries
* goodbye
	- utter_bye

## path10- existing customer comes for free course but didn't took 
* free_course
	- utter_ask_interested
* affirm
	- utter_free_course_link
* deny
    - utter_we_will_come_with_new_courses   
* thankyou
	- utter_noworries
* goodbye
	- utter_bye 

## path11- a new customer going for paid as well as free course too
* about_missionED
	- utter_intro_to_MissionEd
* about_product
	- utter_explain_product
* registration
	- info_form
	- form{"name": "info_form"}
	- form{"name":null}
* course
	- show_courses_form
	- form{"name": "show_courses_form"}
	- form{"show_courses_form":null}
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
	
## path12- a new customer going for free as well as paid course but didn't took both
* about_missionED
	- utter_intro_to_MissionEd
* about_product
	- utter_explain_product
* registration
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
    - utter_we_will_come_with_new_courses
* thankyou
	- utter_noworries
* goodbye
	- utter_bye 


## path13- a new person enquiring for paid course but took free course 
* about_missionED
	- utter_intro_to_MissionEd
* about_product
	- utter_explain_product
* registration
	- info_form
	- form{"name": "info_form"}
	- form{"name":null}
* course
	- show_courses_form
	- form{"name": "show_courses_form"}
	- form{"show_courses_form":null}
* deny
	- utter_tell_about_free_courses 
* free_course
	- utter_ask_interested
* affirm
	- utter_free_course_link
* thankyou
	- utter_noworries
* goodbye
	- utter_bye  

## path14- new customer comes for paid course but didn't took 
* course 
	- show_courses_form
	- form{"name": "show_courses_form"}
	- form{"show_courses_form":null}
* price
	- utter_tell_price
* payment
	- utter_payment_page
* deny
    - utter_we_will_come_with_new_courses
* thankyou
	- utter_noworries
* goodbye
	- utter_bye

## path15- new customer comes for free course but didn't took 
* free_course
	- utter_ask_interested
* affirm
	- utter_free_course_link
* deny
    - utter_we_will_come_with_new_courses   
* thankyou
	- utter_noworries
* goodbye
	- utter_bye  


## path16- a existing customer going for paid as well as free course too
* about_missionED
	- utter_intro_to_MissionEd
* about_product
	- utter_explain_product
* registration
	- info_form
	- form{"name": "info_form"}
	- form{"name":null}
* course
	- show_courses_form
	- form{"name": "show_courses_form"}
	- form{"show_courses_form":null}
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
	
## path17- a existing customer going for free as well as paid course but didn't took both
* about_missionED
	- utter_intro_to_MissionEd
* about_product
	- utter_explain_product
* registration
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
    - utter_we_will_come_with_new_courses
* thankyou
	- utter_noworries
* goodbye
	- utter_bye    


## path18- a existing enquiring for free course but take a paid course
* about_missionED
	- utter_intro_to_MissionEd
* about_product
	- utter_explain_product
* free_course
	- utter_ask_interested
* deny
	- utter_tell_about_paid_courses
* registration
	- info_form
	- form{"name": "info_form"}
	- form{"name":null}
* course
	- show_courses_form
	- form{"name": "show_courses_form"}
	- form{"show_courses_form":null}
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

## path19- a existing enquiring for paid course but took free course 
* about_missionED
	- utter_intro_to_MissionEd
* about_product
	- utter_explain_product
* registration
	- info_form
	- form{"name": "info_form"}
	- form{"name":null}
* course
	- show_courses_form
	- form{"name": "show_courses_form"}
	- form{"show_courses_form":null}
* deny
	- utter_tell_about_free_courses 
* free_course
	- utter_ask_interested
* affirm
	- utter_free_course_link
* thankyou
	- utter_noworries
* goodbye
	- utter_bye 

   

## bot challenge
* bot_challenge
  - utter_i_am_MissionEd_bot 

