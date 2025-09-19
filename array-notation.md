# Array Notation

---

Primary array notation, similar to Bowers' Exploding Array Function (BEAF), and created with the aim of achieving the highest number with the least amount of new characters.

Current Extensions

- Linear HSAN
- Multilayer HSAN
- Extended Multilayer HSAN
- Superextended Multilayer HSAN
- Hyperextended Multilayer HSAN
- Astral Multilayer HSAN

## TAD

- TAD
- Array - a set of elements
- Element - positive integer (linear arrays), array of previous type
- Base - first element of array
- Recursion - repeating of an array 'base' times.
- Iteration - repeating of elements of array 'base' times.
- \# - a part of an array that does not transformed (has forms for multilayer arrays (#x) and other extensions)
- % - a filled array that consists of all the arrays of the previous layers in quantity 'base' (like [3(2)1]=[3,3,3(1)3,3,3(1)3,3,3])
- $ -repeating of element

All rules from previous array types is applicable to arrays of follow types, which contain arrays of previous type.

Superscript for braces equal to the number of braces

## Definition

### Linear HSAN

Basic arrays

\([a] = a+1\)
\([a, b+1, \#] = [\dots, b, \#]\)
\([\#, 1] = [\#]\)
\([\#, 1, b+1, \#] = [\#, \dots, b, \#]\)

### Multilayer HSAN

Arrays have become multidimensional

\([a(1)1] = [a, a, a, \dots]\)
\([a(b)1] = [\%]\)
\([a(c)b+1(c)\#_c] = [\%(c)b(c)\#_c]\)
\([\#_c(c)\$^1_{b+1}] = [\#_c(c)\$^\%_b]\)
\([\#_c(c)1(c)b+1(c)\#_c] = [\#_c(c)\%(c)b(c)\#_c]\)

### Extended Multilayer HSAN

\([a(1 \backslash 1)1] = [\%]\)
\([a(b \backslash 1)1] = [\%]\)
\([a(1, 1, \dots \backslash 1)1] = [a(\dots, \dots \backslash 1)1]\)
\([a(\#, 1, b+1, \# \backslash 1)1] = [a(\#, \dots, b, \# \backslash 1)1]\)
\([a(1 \backslash b+1)1] = [a(\% \backslash b)1]\)
\([a(1 \backslash \$^1_{x+1} \backslash b+1)1] = [a(\% \backslash \$^\%_{x} \backslash b)1]\)
\([a(1 \backslash \$^1_{x+1})1] = [a(\% \backslash \$^\%_{x})1]\)

### Superextended Multilayer HSAN
Backslash can be indexed with number

### Hyperextended Multilayer HSAN
Backslash can be indexed with array