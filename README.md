network-motif 
=============

Network Motif analysis using ESU algorithm (Java)
Adopted to Win64, but you have to use cygwin1.dll (install cygwin)

## Test Drive



## Data File Format

Text file, with each line containing a "from" node and a "to" node, as indicated by the string. These are interpreted to be undirected connections, so the ordering does not actually matter.

Example:

```
a b
b c
b d
d e
```

This represents the following graph:

```
 ___        ___        ___
| a | ---- | b | ---- | c |
 ---        ---        ---
             |
             |
            ___        ___
           | d | ---- | e |
            ---        ---
```
