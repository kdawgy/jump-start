# Practice problems
_Jump start: Lesson 9_

## Overview
Complete each section by hand, then check your answers using `irb`

## Variables and assignment practice

```ruby
x = 5
# what value does x now hold? 5 

z = "Hello"
# what value does z now hold? "Hello"

a = 5
b = 3.2
c = a + b
# what values does c now hold? 8.2

var1 = "lawl"
var2 = "brb"
# what value does var2 now hold? "brb"

e = 6 + 3
# what values does e now hold? 9

f = 3.5
f = f + 2
# what value does f now hold? 5.5

poodle = 4
pitbull = 3
# what value does boxer now hold? n/a

h = 5
h = h + h
# what values does h now hold? 10

j = 1
k = 2
m = 3
n = j + k + m
# what value does n now hold? 6

p = "moo"
q = "quack"
p  = q
# what value does p now hold? "quack"

r = "moo"
s = "quack"
t = "woof"
r = t
# what value does r now hold? "woof"

u = 5
u = u * 2
u = u * 2
u = u * 2
# what value does u now hold? 40

v = "b"
z = "a"
# what value does v now hold? "b"


aa = 3234
bb = 2398
cc = 0
dd = (aa + bb) / cc
# what value does dd now hold? 0

yy = 7
zz = yy % 2
# what value does zz now hold?

ee = 12
ff = ee % 4
# what value does ff now hold?


zz = 17
hh = zz % 3
# what value does hh now hold? 2
```

## Operators practice
Consider the following variable assignments and then fill in the tables

```ruby
d = 10
e = 5.0
f = 2
g = 11.0
h = 3
i = 1.5
```

| Operation | Result | Data type of result |
| :---: | :---:| :---: |
| `d + e` | 15.0| floating |
| `f + h` | 5 | fixnum |
| `g + h` | 14.0 | floating |
| `d - f` | 8 | fixnum |
| `g - e` | 6.0 | floating |
| `(h + i) - f` | 2.5|  floating|
| `(d - f) + e` | 13.0 |  floating|
| `d * f` | 20| fixnum | |
| `g * i` | 16.5|  floating | |
| `f * g` | 22.0| floating  | |
| `d / f` |  5 |fixnum|  |
| `d / e` | 2.0 | floating  | |
| `e / f` |2.5  | floating |  |
| `(g * f) / f` | 11.0| floating  | |
| `(d / f) * e` | 25.0 | floating  | |
| `21 / 5` | 4| fixed  |  |
| 14 / 5 | 2 | fixed  | |
| 10 % 3 | 1 | fixed  | |
| 20 % 2 | 0 | fixed  | |
| 4 % 5 | 4| fixed |  |
| 8 % 1 | 0 | fixed  | |

## String practice
Determine the output of slice on your own and then check your answer using `irb`
 
```ruby
# problem 1
my_string = "I love Seattle"
my_string.slice(7) 

S

# problem 2
my_string = "I love Seattle"
my_string.slice(2, 4)

lo

# problem 3
my_string = "I love Seattle"
my_string.slice("Seattle")

Seattle

# problem 4
my_string = "Ada"
my_string + " Lovelace"

# problem 5
my_string = "Ada"
my_string << " codes" << " it!"

# problem 6
my_string = "Ada"
my_string.concat(" likes to code").slice(4...9)

# problem 7
my_string = "Hello world"
"Goodbye " + my_string.slice(6, 5) << "!"

# problem 8
my_string = "Hello world!"
my_string.slice(0...5).concat(", goodbye!")

# problem 9
my_string = "Hello world!"
my_string.slice(0) << "i" + "!"

# problem 10
my_string = "I love ruby"
my_string.slice(7, 4).concat(my_string.slice(2...6)) + my_string.slice(0)

# problem 11
my_string = "I love ruby"
"R".concat(my_string.slice(8, 3) + " rocks!")

# problem 12
my_string = "I love ruby"
my_string.slice(2, 4) << my_string.slice(7...11).concat(my_string.slice(2...6))
```
