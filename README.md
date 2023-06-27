# bettermathops.ix
Fixing JavaScript out of Insitux

## use
Do:
```clj
(import "FordArthur/better-math-ops")
```
To get access to the functions.

## Contains:

### Better basic operations

``sum``: better summing operation
``mul``: better multiplication operation

Note that subtraction and division can be easily defined by applying their respective inverse (i.e ``neg`` for summation and ``inv`` for division)

``inv``: multiplicatively inverts a number
``safe-inv``: same as ``inv``, but, when 0, the output is 0

### Better trig operations

``sine``: better sine
``cosine``: better cosine
``tangent``: better tangent

### Extra trig operations

``cosecant``, ``secant``, ``cotangent``, their respective trig operation, but the output is inverted

### Trig variables shorthands

``PI/2``: Pi halves
``2PI``: Tau (2 times PI)
