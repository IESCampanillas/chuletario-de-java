# chuletario-de-java
Java: trucos, consejos y curiosidades


## :computer: [�C�mo leer arrays con for each correctamente?](#for-each)


<a name="for-each"></a>�C�mo leer arrays con for each correctamente?
Arrays de una dimensi�n
```console
    String[] palabras = {"uno", "dos", "tres", "cuatro"};
    for (String p : palabras) {
      System.out.print(p + " ");
    }
```
Arrays Bidimensionales
```console
int[][] arrayBidimensional = {{1, 2, 3, 4}, {5, 6, 7, 8}, {9, 10, 11, 12}};
    for (int[] arrayUnidimensional : arrayBidimensional) {
      for (int n : arrayUnidimensional) {
        System.out.print(n + " ");
      }
      System.out.println();
    }
```