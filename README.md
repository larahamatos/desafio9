# desafio9

# questao1
```java
        Scanner ler = new Scanner(System.in);
        int [] v = new int[10];
        int i, cn100 = 0;

        for (i = 0; i < v.length; i++) {
            System.out.println("Digite um número: ");
            v[i] = ler.nextInt();
            if (v[i] > 100) {
                cn100++;
            }
        }
        System.out.println("O vetor possui: "+cn100+" valores MAIORES que 100");
```
# questao2
```java
        int[] nInteiros = {1, 2, 3, 4, 5, 6, 7, 8, 9, 10};
        int soma = 0;
        for (int i = 0; i < nInteiros.length; i++) {
            soma += nInteiros[i];
        }
        System.out.println("A soma dos números armazenados nos vetores é: "+soma);
```
# questao3
```java
        int[] nInteiros = {1, 2, 3, 4, 5, 6, 7, 8, 9, 10};
        for (int numero : nInteiros) {
            System.out.println(numero);
        }
        for (int i = nInteiros.length - 1; i >= 0; i--) {
            System.out.println(nInteiros[i]);
```
# questao4
```java
        Scanner ler = new Scanner(System.in);
        int [] nInteiros = new int[10];
        int i, cN = 0;

        for (i = 0; i < nInteiros.length; i++) {
            System.out.println("Digite um número: ");
            nInteiros[i] = ler.nextInt();
            if (nInteiros[i] < 0) {
                cN++;
            }
        System.out.println("A quantidade de números negativos é: "+cN);
```
# questao5
```java
        int[] nI = {1, 2, 3, 4, 5, 6, 7, 8, 9, 10};
        for (int i = 0; i < nI.length; i++) {
            System.out.println(nI[i] + " x " + 2 + " = " + (nI[i] * 2));
```
# questao6
```java
        Scanner ler = new Scanner(System.in);
        int i;
        int[] nI = new int[10];
        for (i = 0; i < nI.length; i++) {
            System.out.println("Digite um número: ");
            nI[i] = ler.nextInt();
            if (nI[i] < 0) {
                nI[i] = 0;
            }
        }
        System.out.println("Resultado");
        for (i = 0; i < nI.length; i++) {
            System.out.println(nI[i]);
```
# questao7
```java
        }
