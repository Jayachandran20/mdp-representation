# MDP REPRESENTATION

## AIM:
```
To represent a Markov Decision Process(MDP) problem in the following ways.

1)Text representation
2)Graphical representation
3)Python - Dictonary representation
```
## PROBLEM STATEMENT:
To find wheather it is a profit or loss on buying and selling of a particular product in a grocery shop

### State Space
biscuts and chips

### Sample State
chips

### Action Space
buying and selling

### Sample Action
move right (selling)
### Reward Function
```
R = { +1 , if we come closer to the expected temperature
       0 , otherwise
```
### Graphical Representation
![rein](https://github.com/Jayachandran20/mdp-representation/assets/118447015/269f73a0-a70e-4c6a-941c-2a810f762b96)


## PYTHON REPRESENTATION:
```
NAME: M.JAYACHANDRAN
REG NO: 212222240038

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
```
{0: {0: [(1.0, 0, 0.0, True)], 1: [(1.0, 0, 0.0, True)]},
 1: {0: [(1.0, 0, 0.0, True)], 1: [(1.0, 2, 1.0, True)]},
 2: {0: [(1.0, 2, 0.0, True)], 1: [(1.0, 2, 0.0, True)]}}
```
## RESULT:
```
Thus the given Markov Decision Process(MDP) problem is represented in the following ways.
#1)Text representation
#2)Graphical representation
#3)Python - Dictonary representation
```

