# Ejemplo 6. Loops y pseudocódigo: For

#### Este ejemplo elevará al cuadrado las primeros 10 entradas de un vector generado aleatóriamente de 20 entradas 
```R
w <- rnorm(20)              
print("Este loop calcula el cuadrado de los 10 primeros elementos del vector w")
```
#### inicializando la varialbe `wsq`
```R
wsq <- 0

for(i in 1:10) {
  # i-th element of `u1` squared into `i`-th position of `usq`
  wsq[i] <- w[i]**2
  print(wsq[i])
}
```

#### Pseudocódigo 
```R
if(<condicion>) {
  ## bloque de código
}

## Continue with rest of code
if(<condicion>) {
  ## bloque de código
} else {
  ## otro bloque de código
}

if(<condition1>) {
  ## bloque de código
} else if(<condicion2>) {
  ## otro bloque de código
} else {
  ## otro bloque de código
}
```
De este modo estamos asignando un valor a una variable en función del valor de otra. Lo que se debe tener en cuenta es que la condición debe retornar un valor TRUE o FALSE.
```R
x <- runif(1, 0, 10) ## creamos un nro aleatorio entre 0 y 10
if(x > 5) {
  y <- TRUE
} else {
  y <- FALSE
}
```
