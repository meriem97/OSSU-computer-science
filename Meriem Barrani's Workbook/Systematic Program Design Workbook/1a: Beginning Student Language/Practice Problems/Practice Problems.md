<h1>Recommended Problems</h1>

Before going on to the module quiz you should complete the practice problems shown below.


<details>
<Summary> <h2>BSL P1 - More Arithmetic Expressions</h2></Summary>
<br>

<h4>PROBLEM</h4>

Write two expressions that multiply the numbers 3, 5 and 7. 
The first should take advantage of the fact that * can accept more than 2 arguments. 
The second should build up the result by first multiplying 3 times 5 and then multiply the result of that by 7. 

<h4> SOLUTION </h4>
<br>

1- `(* 3 5 7)`
<br>
2- `(* (* 3 5) 7)`
</details>

<details>
<Summary> <h2>BSL P3 - Tile</h2></Summary>
<br>

<h4>PROBLEM</h4>

Use the DrRacket square, beside and above functions to create an image like this one:

![image](https://github.com/user-attachments/assets/748e1293-cee8-46d6-baa0-0b304afc7807)



If you prefer to be more creative feel free to do so. You can use other DrRacket image 
functions to make a more interesting or more attractive image.


<h4>SOLUTION</h4>
<br>

```
(beside(above
 (square 30 "solid" "red")
 (square 30 "solid" "green"))
(above
 (square 30 "solid" "green")
 (square 30 "solid" "red")))
```

<br>

![image](https://github.com/user-attachments/assets/373a05ec-74ab-4508-b485-bd5ffe3b9a64)


<br>
</details>

