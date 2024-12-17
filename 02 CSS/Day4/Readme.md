

# specificity
- when multiple rules are applied with different selectors to the same element, which one wins here ?

## Specificity order
1. Inline style
2. id
3. class / attribute/ pseudo class
4. element selectors least specific


### Specificity Calculation

div a 

id :0    class:0   element :2

# ex : 

.pid span  : 011

# ex : div p .pclass   vs   .special + .mail

012  vs  020(wins)

# ex : #nav  vs .main .pclass .sclass
100 030

# ex : .main + .sub   vs .pclass a:hovor
020    021  (hovor is a class)

# Important
We can make a declaration as important using 

# colors
-    colors
-    hex value
-    RGB(Red, Blue,Green) 0-255
-    RGBA(Alpha)



