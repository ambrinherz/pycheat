# pycheat

Help usage:

```
pycheat -h
```

Output:
```
Options:
	- list
	- dict
	- counter
	- set
	- tuple
	- range
	- enumerate
	- iter
	- itertools
	- generator
	- type
	- string
	- regex
	- format
	- numbers
	- random
	- combinatronics
	- datetime
  ...
```

Usage:

```
pycheat list
```

Output:
```
List:
<list> = <list>[from_inclusive : to_exclusive : ±step_size]

<list>.append(<el>)            # Or: <list> += [<el>]
<list>.extend(<collection>)    # Or: <list> += <collection>

<list>.sort()
<list>.reverse()
<list> = sorted(<collection>)
<iter> = reversed(<list>)

sum_of_elements  = sum(<collection>)
elementwise_sum  = [sum(pair) for pair in zip(list_a, list_b)]
sorted_by_second = sorted(<collection>, key=lambda el: el[1])
sorted_by_both   = sorted(<collection>, key=lambda el: (el[1], el[0]))
flatter_list     = list(itertools.chain.from_iterable(<list>))
product_of_elems = functools.reduce(lambda out, el: out * el, <collection>)
list_of_chars    = list(<str>)

<int> = <list>.count(<el>)     # Returns number of occurrences. Also works on strings.
index = <list>.index(<el>)     # Returns index of first occurrence or raises ValueError.
<list>.insert(index, <el>)     # Inserts item at index and moves the rest to the right.
<el> = <list>.pop([index])     # Removes and returns item at index or from the end.
<list>.remove(<el>)            # Removes first occurrence of item or raises ValueError.
<list>.clear()                 # Removes all items. Also works on dictionary and set.
```
