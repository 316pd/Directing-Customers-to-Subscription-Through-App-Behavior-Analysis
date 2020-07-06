Directing customers to subscription through app behavior analysis dataset

About the dataset :
user -> user_id
first_open -> user first time open the app
dayofweek -> sunday(0) to saturday(6)
hour -> time
age -> age
screen_list -> List every single screen name that user has visited in first 24 hrs
numscreens -> number of screen that appears in screen list
minigame -> if user play this game in first 24 hrs it will store as '1' else '0'
used_premium_feature -> if a user used only free feature and never used any premium feature then it is '0' else '1'
enrolled -> if user enrolled to any paid products it store as '1' else '0'
enrolled_date -> if enrolled
liked -> if user liked any feature then it store as '1' else '0'

Objective:
The main objective of the model is to predict which user will not subscribe to the paid membership, so that greater marketing efforts can go into trying to 'convert' them into paid users.
