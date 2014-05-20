#Exercise Data
===

This data has been scrapped from the web and is in JSON format

Each entry has the following:
'''
name
rating
type
main_muscle
other_muscles
equipment
mechanics
level
force
directions
'''

`name` : The name of the exercise
`rating` : A float with the rating assigned by users
`type` : The type of exercise, Cardio, Strength, Powerlifting, etc
`main_muscle` : The main muscle used in the movement
`other_muscles` : Array of other muscles that are used. This attribute is not present in all entries
`equipment` : The main piece of equipment used
`mechanics` : The movement type (e.g. Isolation, Compound)
`level` : The level of expertise that was assigned to the exercise (e.g. "Beginner", "Intermediate")
`force` : The direction of the movement (e.g. "Push", "Pull")
`directions` : Array of strings of the directions for perfoming the exercise

