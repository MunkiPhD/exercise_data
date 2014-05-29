#Exercise Data
===

This data has been scrapped from the web and is in JSON format

Each entry has the following:
```
name  
rating  
also_known_as  
type  
main_muscle_worked  
other_muscles  
equipment  
mechanics_type  
level  
sport  
force  
directions  
```

`name` : The name of the exercise  
`rating` : A float with the rating assigned by users  
`also_known_as` : comma delimited string of names the exercise is also known as*  
`type` : The type of exercise, Cardio, Strength, Powerlifting, etc  
`main_muscle_worked` : The main muscle used in the movement*  
`other_muscles` : Array of other muscles that are used. This attribute is not present in all entries  
`equipment` : The main piece of equipment used  
`mechanics_type` : The movement type (e.g. Isolation, Compound)  
`level` : The level of expertise that was assigned to the exercise (e.g. "Beginner", "Intermediate")  
`sport` : Whether the exercise is part of an athletic competition  
`force` : The direction of the movement (e.g. "Push", "Pull")  
`directions` : Array of strings of the directions for perfoming the exercise  
  
*may not show property if it does not exist

