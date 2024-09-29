# 2024-09-28

## Machine Learning Model Types
- classification
- regression
- generative

[3Blue1Brown Neural Networks](https://youtube.com/playlist?list=PLZHQObOWTQDNU6R1_67000Dx_ZCJB-3pi&si=IxIIfvcGJkrXozES)

## Goals
0. 3d model is `.stl` file, make sure can recognize texture of hold
1. classify texture of hold
    - smooth
    - rough
    - dual tex
1. features for classification
    - incline of wall (changes as go up wall, maybe can do point a to b, or a fucniton)
    - average size of hold (nah, idk)
    - number of holds
    - hold 1 type, hold 2 type, etc. (not typical, unsure if possible)

1. classify hold type based on 3d model
    - jug / undercling
    - crimp
    - sloper
    - pinch
    - pocket
    - volume
2. classify hold type based on 3d model, axis aware
    - jugs
    - crimps
    - slopers
    - pinches
    - pockets
    - underclings
    - gastons / sidepulls
    - volumes
3. predict difficulty of climbs to a rating (regression)
4. generate a climb based on model of holds and wall
5. editable answers, with updating difficulty rating

## Other Notes
- aretes (prob not part of inital goals actually, its part of the wall, not a hold you put on the wall)
- file type / definiton for defining climbs
- we were talking about `.step` file instead of `.stl` file but its more complicated in a sense that for example if you import a `.step` file itsll save the feature the way you modeled it but we aren't even making it like that. -Bruno
- in future can look at how smooth / rough in a continuous way, regression not classification

https://chatgpt.com/share/66f8ab19-1dcc-8001-a442-c95f9a89fc9b