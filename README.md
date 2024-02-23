# MDP REPRESENTATION

## AIM:
To represent a Markov Decision Process(MDP) problem in the following ways.

1.Text representation

2.Graphical representation

3.Python - Dictonary representation

## PROBLEM STATEMENT:

### Problem Description
To Develop an environment contain some dirt and the agent is going to detect and clean the environment using vaccum. The aim is to clean the dirty place.

### State Space
{Location A,Location B,Location C}

### Sample State
Location A

### Action Space

1.Moving Right

2.Moving Left

3.Suck Dirt

### Sample Action

Moving Right

### Reward Function
1.+1 - when an agent move to the right side and the dirt is cleaned using vaccum 

2.0 - Otherwise
### Graphical Representation
![img1](https://github.com/Bairav-2003/mdp-representation/assets/94154692/20fdfaf2-27a8-4c98-8e5b-0029b7a262e1)

## PYTHON REPRESENTATION:
```
# Developed by: Bairav Skandan Loha
# Register Number: 212221230010

P = {
    0:{
        0: [(1.0,0,0.0,True)],
        1: [(1.0,0,0.0,True)]
    },
    1:{
        0: [(1.0,0,0.0,True)],
        1: [(1.0,2,1.0,True)]
    },
    2:{
        0: [(1.0,2,0.0,True)],
        1: [(1.0,2,0.0,True)]
    }
}

```
## OUTPUT:
![Screenshot 2024-02-18 214941](https://github.com/Dhanudhanaraj/mdp-representation/assets/119218812/6eba07da-65b4-497d-92fd-426e48a17985)


## RESULT:
Thus the given real world problem is successfully represented in a MDP form.

