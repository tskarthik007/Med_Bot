## happy path
* greet
  - utter_greet
* mood_great
  - utter_happy

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

## say goodbye
* goodbye
  - utter_goodbye

## bot challenge
* bot_challenge
  - utter_iamabot

## regulation_information
* regulation_information
  - utter_regulation_information

## system_uses
* system_uses
  - utter_system_uses

## Dose_Check
* Dose_Check
  - utter_Dose_Check

## Dose_check_use
* Dose_check_use
  - utter_Dose_check_use

## Setting_Dose_Administrator_Role
* Setting_Dose_Administrator_Role
  - utter_Setting_Dose_Administrator_Role

## Setting_AV_Exceeding_User_Role
* Setting_AV_Exceeding_User_Role
  - utter_Setting_AV_Exceeding_User_Role

## Configure_the_system_for_dose_checking
* Configure_the_system_for_dose_checking
  - utter_Configure_the_system_for_dose_checking

## Configure_the_system_for_alert_value_by_age_threshold
* Configure_the_system_for_alert_value_by_age_threshold
  - utter_Configure_the_system_for_alert_value_by_age_threshold

## Configure_the_system_for_protocol_change_control
* Configure_the_system_for_protocol_change_control
  - utter_Configure_the_system_for_protocol_change_control