# Hyperstar Hard X-Notation

Complexed and very powerful notation with an unimaginable growth speed. New version of X-Notation.

**Current Extensions**
- Hard X-Notation
- Extended Hard X-Notation (HCCF)
- Superextended Hard X-Notation (EHCCF + NHCCF)
- Hyperextended Hard X-Notation (HEHCCF)

## TAD

- **Iterator** - a chain of elements or other iterators (denoted as [...])
- **Element** - positive natural number
- **Chain** - a set of iterators and elements
- **Base** - first element
- **Recursion** - repeating of an array 'base' times. '<...>'
- **Iteration** - repeating of elements of array 'base' times. '...'
- **...(c)** - repeating of elements of array 'c' times.
- **::** - a part of a chain that does not transformed.

All rules from previous array types is applicable to arrays of follow types, which contain iterators of previous type.

Superscript for braces - count of braces.

## Hard X-Notation

1. $ X^{HD}\{n\} = n + 1 $
2. $ X^{HD}\{\# ' 1\} = X\{\#\} $
3. $ X^{HD}\{n ' c + 1\} = X\{<…> ' c\} $
4. $ X^{HD}\{\# ' 1 ' c + 1 ' \#\} = X\{\# ' <…> ' c ' \#\} $
5. $ X^{HD}\{n[1]\} = X\{n ' n ' …\} $
6. $ X^{HD}\{n[1] ' …(d) ' 1\} = X\{n ' n ' …[1] ' …(d)\} $
7. $ X^{HD}\{n[1] ' …(d) ' c + 1\} = X\{n ' n ' …[1] ' …(d) ' c\} $
8. $ X^{HD}\{n[1] ' …(d) ' \# ' 1 ' c + 1 ' \#\} = X\{n[1] ' …(d) ' \# ' <…> ' c ' \#\} $
9. $ X^{HD}\{n[1] ' …(d) ' 1 ' 1 ' …(c + 1)\} = X\{n[1] ' …(d) ' n ' n ' …(c)\} $
10. $ X^{HD}\{n[1] ' …(d) ' [1]\} = X\{n[1] ' …(d) ' n ' n ' …\} $
11. $ X^{HD}\{n[c + 1 ' \#]\} = X\{n[c ' \#] ' [c ' \#] ' …\} $
12. $ X^{HD}\{n[c + 1 ' \#] ' …(d) ' 1\} = X\{n[c + 1 ' \#] ' …(d)\} $
12. $ X^{HD}\{n[c + 1 ' \#] ' …(d) ' 2\} = X\{n[c ' \#] ' [c ' \#] ' …[c + 1 ' \#] ' …(d)\} $
13. $ X^{HD}\{n[c + 1 ' \#] ' …(d) ' e + 1\} = X\{n[c ' \#] ' [c ' \#] ' …[c + 1 ' \#] ' …(d) ' e\} $
14. $ X^{HD}\{n[c + 1 ' \#] ' …(d) ' \# ' 1 ' e + 1 ' \#\} = X\{n[c + 1 ' \#] ' …(d) ' \# ' <…> ' e ' \#\} $
15. $ X^{HD}\{n[c + 1 ' \#] ' …(d) ' 1 ' 1 ' …(e + 1) ' 2\} = X\{n[c + 1 ' \#] ' …(d) ' n ' n ' …(e)\} $
16. $ X^{HD}\{n[c + 1 ' \#] ' …(d) ' [e + 1 ' \#]\} = X\{n[c + 1 ' \#] ' …(d) ' [e ' \#] ' [e ' \#] ' …\} $
17. $ X^{HD}\{n[\# ' 1]\} = X\{n[\#]\} $
17. $ X^{HD}\{n[1 ' 2]\} = X\{n[n]\} $
18. $ X^{HD}\{n[\# ' 1 ' c + 1 ' \#]\} = X\{n[\# ' <…> ' c ' \#]\} $
19. $ X^{HD}\{n[1 ' 1 ' …(c + 1) ' 2]\} = X\{n[n ' n ' …(c)]\} $

## Hash Chain Collapse Function

*Note: γ - base of HSHXN expression. At the end of recursion: 0. Recursion of #_ξ = <...>_ξ. #_0 = #*

1. $ \#(0) = γ $
2. $ \#(c + 1 ' ::) = \#(c ' ::) ' \#(c ' ::) ' …(γ) $
3. $ 2 ' \#(0) = \#^γ(0) $
4. $ c + 1 ' :: ' \#(0) = c ' :: ' \#^γ(0) $
5. $ \# ' 2(0) = <…> ' \#(0) $
6. $ \# ' c + 1 ' ::(0) = <…> ' \# ' c ' ::(0) $
7. $ \# ' …(d) ' \#(0) = \# ' …(d) ' <…>(0) $
8. $ \# ' …(d) ' \# ' 2(0) = \# ' …(d) ' <…> ' \#(0) $
9. $ \# ' …(d) ' \# ' c + 1 ' ::(0) = \# ' …(d) ' <…> ' \# ' c ' ::(0) $

## Extended Hash Chain Collapse Function

*Note: γ - base of HSHXN expression. At the end of recursion: 0. Recursion of #_ξ = <...>_ξ. #_0 = #*

1. $ \#_{c + 1}(0) = \#_c $
2. $ \#_c(e + 1 ' ::) = \#_c(e ' ::) ' \#_c(e ' ::) ' …(γ) $
3. $ \#_c(\#) = \#_c(<…>) $
4. $ \#_c(\#_d) = \#_c(<…>_d) $, d < c
5. $ 2 ' \#_c(\#) = \#_c^γ(0) $
6. $ e + 1 ' :: ' \#_c(\#) = e ' :: ' \#_c^γ(0) $
7. $ \# ' \#_c(\#) = <…> ' \#_c^γ(0) $
8. $ \#_d ' \#_c(\#) = <…>_d ' \#_c^γ(0) $, d < c
9. $ \#_c ' 2(\#) = <…>_c ' \#_c(0) $
10. $ \#_c ' e + 1 ' ::(\#) = <…>_c ' \#_c ' e ' ::(0) $
11. $ \#_c ' \#_d(\#) = \#_c ' <…>_d(0) $, d < c
12. $ \#_c ' \#_c(\#) = \#_c ' <…>_c(0) $

## Nested Hash Chain Collapse Function

*Note: γ - base of HSHXN expression. At the end of recursion: 0. Recursion of #_ξ = <...>_ξ. #_0 = #*

1. $ \#_\#(0) = \#_{<…>} $
2. $ \#_{\# ' 2}(0) = \#_\# $
3. $ \#_{\# ' \#}(0) = \#_{\# ' <…>} $
4. $ \#_{\#_1}(0) = \#_{<…>_0} $
5. $ \#_{\#_2}(0) = \#_{<…>_1} $
6. $ \#_{\#_3}(0) = \#_{<…>_2} $
7. $ \#_{\#_\#}(0) = \#_{\#_{<…>}} $


And etc.


