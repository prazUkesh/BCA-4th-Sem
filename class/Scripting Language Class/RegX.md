# regular expression

i - perform case sensitive matching
m - global matching
[...] - any character between the bracket
eg. [a-z], [A-Z], [a-Z], [0-9]

[^...] - any haracter not between the brackets

p* zero or more p
p+ one or more p
p> atmost one p

p{n} p character with occurance of n
p{m,n} p character with occurence of either m or n

\d represent sigits
\w represents string
p$ ends with p
^p begin with p
var regexp = /^ -> start of pattern     $/ <- end of pattern
