# Robert Bosch 

## 1st Round
Basic C questions to check our proficiency on C-language

1. set a bit using macro
```
#define SET_BIT(in_uiNumber,in_ucPos) (in_uiNumber |= 1 << in_ucPos)
```

2. Clear a bit using macro
```
#define CLEAR_BIT(in_uiNumber, in_ucPos) (in_uiNumber &= (~(1 << in_ucPos)))
```
3. Toggle a bit using macro
```
#define TOGGLE_BIT(in_uiNumber, in_ucPos) (in_uiNumber ^= (1 << in_ucPos))
```

