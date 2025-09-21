# Hyperstar X-Notation
--------------------

Complexed and very powerful notation with an unimaginable growth speed.

**Current Extensions**

*   X-Notation
*   Extended X-Notation
*   Superextended X-Notation
*   Hyperextended X-Notation

## TAD

- **Iterator** - a chain of elements or other iterators (denoted as [...])
- **Element** - positive natural number
- **Chain** - a set of iterators and elements
- **Base** - first element
- **Recursion** - repeating of an array 'base' times. '<...>'
- **Iteration** - repeating of elements of array 'base' times. '...'
- **...(c)** - repeating of elements of array 'c' times.
- **#** - a part of a chain that does not transformed.

All rules from previous array types is applicable to arrays of follow types, which contain iterators of previous type.

Superscript for braces - count of braces.

## X-Notation

1. $ X\{n\} = n + 1 $
2. $ X\{\# ' 1\} = X\{\#\} $
3. $ X\{n ' c + 1\} = X\{<…> ' c\} $
4. $ X\{\# ' 1 ' c + 1 ' \#\} = X\{\# ' <…> ' c ' \#\} $
5. $ X\{n[1]\} = X\{n ' n ' …\} $
6. $ X\{n[1] ' …(d) ' 1\} = X\{n ' n ' …[1] ' …(d)\} $
7. $ X\{n[1] ' …(d) ' c + 1\} = X\{n ' n ' …[1] ' …(d) ' c\} $
8. $ X\{n[1] ' …(d) ' \# ' 1 ' c + 1 ' \#\} = X\{n[1] ' …(d) ' \# ' <…> ' c ' \#\} $
9. $ X\{n[1] ' …(d) ' 1 ' 1 ' …(c + 1)\} = X\{n[1] ' …(d) ' n ' n ' …(c)\} $
10. $ X\{n[1] ' …(d) ' [1]\} = X\{n[1] ' …(d) ' n ' n ' …\} $
11. $ X\{n[c + 1 ' \#]\} = X\{n[c ' \#] ' [c ' \#] ' …\} $
12. $ X\{n[c + 1 ' \#] ' …(d) ' 1\} = X\{n[c + 1 ' \#] ' …(d)\} $
12. $ X\{n[c + 1 ' \#] ' …(d) ' 2\} = X\{n[c ' \#] ' [c ' \#] ' …[c + 1 ' \#] ' …(d)\} $
13. $ X\{n[c + 1 ' \#] ' …(d) ' e + 1\} = X\{n[c ' \#] ' [c ' \#] ' …[c + 1 ' \#] ' …(d) ' e\} $
14. $ X\{n[c + 1 ' \#] ' …(d) ' \# ' 1 ' e + 1 ' \#\} = X\{n[c + 1 ' \#] ' …(d) ' \# ' <…> ' e ' \#\} $
15. $ X\{n[c + 1 ' \#] ' …(d) ' 1 ' 1 ' …(e) ' 2\} = X\{n[c + 1 ' \#] ' …(d) ' n ' n ' …(e)\} $
16. $ X\{n[c + 1 ' \#] ' …(d) ' [e + 1 ' \#]\} = X\{n[c + 1 ' \#] ' …(d) ' [e ' \#] ' [e ' \#] ' …\} $
17. $ X\{n[\# ' 1]\} = X\{n[\#]\} $
17. $ X\{n[1 ' 2]\} = X\{n[n]\} $
18. $ X\{n[\# ' 1 ' c + 1 ' \#]\} = X\{n[\# ' <…> ' c ' \#]\} $
19. $ X\{n[1 ' 1 ' …(c) ' 2]\} = X\{n[n ' n ' …(c)]\} $

## Extended X-Notation

1. $ X\{n[[1]]\} = X\{n[n ' n ' …]\} $
2. $ X\{n[[[1]]]\} = X\{n[[n ' n ' …]]\} $
3. $ X\{n[[[[1]]]]\} = X\{n[[[n ' n ' …]]]\} $

And etc. Note: all rules from X-Notation applicable inside iterator. Iterators are independent objects, and expansion X-Notation rules 6-19 working inside other iterators. like: X{n&#91;&#91;&#91;1'1&#93;&#93;&#93;} = X{n&#91;&#91;&#91;n&#93;&#93;&#93;}

Calculation order: from external to internal chains.

...&#91;&#91;1&#93;&#93;... = ...&#91;1&#91;1&#93;&#93;... .

**Common recursive rule:**

1. $ X\{n[^c[1]]^c\} = X\{n[^c n ' n ' …]^c\} $

## Superextended X-Notation

*Note: in rule 3 of SEHSXN, ... used for a chain with repeating iterators.*

1. $ X\{n[1 \backslash 1]\} = X\{n[1]^n\} $
2. $ X\{n[\# \backslash 1 \backslash c + 1 \backslash \#]\} = X\{n[\# \backslash [<…>] \backslash c \backslash \#]\} $
3. $ X\{n[1 \backslash 1 \backslash …(c + 1)]\} = X\{n[[<…>] \backslash [<…>] \backslash …(c)]\} $

## Hyperextended X-Notation

*Note: in all rules of HEHSXN, ... used for a chain with repeating iterators.*

1. $ X\{n[1 \backslash_2 1]\} = X\{n[[<…>] \backslash [<…>] \backslash …]\} $
2. $ X\{n[1 \backslash_{s + 1} 1]\} = X\{n[[<…>] \backslash_s [<…>] \backslash_s …]\} $
3. $ X\{n[1 \backslash_{1 ' 2} 1]\} = X\{n[1 \backslash_n 1]\} $
4. $ X\{n[1 \backslash_{1 → 1} 1]\} = X\{n[1 \backslash_{<…>} 1]\} $
5. $ X\{n[1 \backslash_{1 → c + 1} 1]\} = X\{n[1 \backslash_{<…> → c} 1]\} $
6. $ X\{n[1 \backslash_{\# → 1 → c + 1 → \#} 1]\} = X\{n[1 \backslash_{\# → <…> → c → \#} 1]\} $
7. $ X\{n[1 \backslash_{1 →_2 1} 1]\} = X\{n[1 \backslash_{n → n → n → …} 1]\} $
8. $ X\{n[1 \backslash_{1 →_{c + 1} 1} 1]\} = X\{n[1 \backslash_{n →_c n →_c n →_c …} 1]\} $

9. $ X\{n[1 \backslash_{1 →_{1 → 1} 1} 1]\} = X\{n[1 \backslash_{1 →_{<…>} 1} 1]\} $




