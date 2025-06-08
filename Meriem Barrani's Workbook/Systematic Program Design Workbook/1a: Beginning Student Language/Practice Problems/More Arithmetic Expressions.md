BSL P1 - More Arithmetic Expressions
-

|Problem| Solution|
|:---------:|:-----------|
|Write two expressions that multiply the numbers 3, 5 and 7. 
The first should take advantage of the fact that * can accept more than 2 arguments. 
The second should build up the result by first multiplying 3 times 5 and then multiply the result of that by 7. | 1- `(* 3 5 7)`
2- `(* (* 3 5) 7)`
