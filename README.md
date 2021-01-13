diceset
--

[diceset](https://github.com/gradinarualex/diceset) is a simple dice set creator and roller for fun or usage in a bigger project.

Quickstart
-- 

### **Install**

```
pip install diceset
```

### **Code Example**

```python
>>> from diceset import DiceSet

>>> dice_set = DiceSet(4, 6) # four 6-sided dice
>>> first_roll = dice_set.roll() # returns a list of rolls for each die
 [3, 1, 5, 6]
```