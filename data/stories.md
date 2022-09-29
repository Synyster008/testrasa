## greeting path 1
* greet
- utter_greet

## fine path 1
* fine_normal
- utter_help

## fine path 2
* fine_ask
- utter_reply

## thanks path 1
* thanks
- utter_thank

## bot challenge
* bot_challenge
  - utter_iamabot

## fallback
- utter_default


## exercise_ask
* exercise_per{"yoga": "exercise"}
- slot{"yoga": "exercise"}
- utter_exercise_per

## New Story

* greet
    - utter_greet
* fine_ask
    - utter_reply

## New Story

* greet
    - utter_greet
* fine_normal
    - utter_help
* exercise_per{"body": "exercise"}
    - utter_exercise_per


## interactive_story_1
* greet
    - utter_greet
* fine_normal
    - utter_help
* exercise_per{"yoga": "exercise"}
    - utter_proceed
* yes
    - utter_exercise_per