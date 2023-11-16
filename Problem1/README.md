# Problem 1: Sets

## Question 10
```
For the student database
U = {Alice,Bob,Carol,Darragh,Eileen,Frank,Oliver,Patsy,Ronan,Susan,Ted,Una}
with registrations for new modules as follows:
    Alice: CS200, CS201
    Bob: CS201, EC204
    Carol: EE101, FR105, MG201
    Darragh: CS201
    Eileen: EC204, FR105
    Frank: CS201, MG201
    Oliver: EC204, EE101
    Patsy: MG201
    Ronan: CS200
    Susan: EE101, EC204
    Ted: FR105, CS201, CS200
    Una: MG201
Write down the sets of students registered for each module.
```

### Answer

```
    U={Alice, Bob, Carol, Darragh, Eileen, Frank, Oliver, Patsy, Ronan, Susan, Ted,Una}

    CS200 = {Alice, Ronan, Ted}

    CS201 = {Alice, Bob, Darragh, Frank, Oliver, Ted}

    EC204 = {Bob, Eileen, Susan}

    EE101 = {Carol, Oliver, Susan}

    FR105 = {Carol, Eileen, Ted}

    MG201 = {Carol, Frank, Patsy, Una}
```

## Question 11

For the student database in Q10, write down the result of the following operations:
- (i) $CS200 \cup CS201$

- (ii) $MG201 \cap EE101$
- (iii) $EC204 \cap CS200$
- (iv) $CS200  \backslash CS201$
- (v) $CS201 \backslash CS200$

### Answer

    (i) {Alice, Ronan,  Bob, Darragh, Frank, Oliver, Ted}
    
    (ii) {Carol}
    
    (iii) {}
    
    (iv) {Ronan} 
    
    (v) {Bob, Darragh, Frank, Oliver}

## Question 12

```
Write down the following
    (i) P{a,b,c,d}
    
    (ii) P{apple}
    
    (iii) P{}
    
    (iv) P(CS200), where CS200 is the set you created in Q10
    
    (v) |P{a,b,c,d}|
    
    (vi) |P{apple}|
    
    (vii) |P{}|
```
### Answer

    (i) P{a,b,c,d} = = {{}, {a}, {b}, {c}, {d}, 
                        {a,b}, {a,c}, {a,d}, {b,c}, {b.d}, {c,d}
                        {a,b,c}, {a,b,d}
                        {b,c,d}
                        {a,b,c,d}}

    (ii) P{apple} = {{}, {apple}}

    (iii) P{} = P{{}}

    (iv) P(CS200) = {{}, {Alice}, {Ronan}, {Ted}
                        {Alice, Ronan}, {Alice, Ted}, {Ronan, ted}
                        {Alice, Ronan, Ted}}

    (v) |P{a,b,c,d}| = 2^4 = 16 
    
    (vi) |P{apple}| = 2^1 = 2

    (vii) |P{}| = 1, because this is the null set itself, so there is only 1.
