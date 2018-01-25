# chuletario-de-java
Java: trucos, consejos y curiosidades


## :computer: [¿Cómo leer arrays con for each correctamente?](#for-each)


<a name="for-each"></a>¿Cómo leer arrays con for each correctamente?
Arrays de una dimensión
```java
String[] palabras = {"uno", "dos", "tres", "cuatro"};

for (String p : palabras) {
    System.out.print(p + " ");
}
```
Arrays Bidimensionales
```java
int[][] arrayBidimensional = {{1, 2, 3, 4}, {5, 6, 7, 8}, {9, 10, 11, 12}};

for (int[] arrayUnidimensional : arrayBidimensional) {
    for (int n : arrayUnidimensional) {
        System.out.print(n + " ");
    }
    System.out.println();
 }
```
