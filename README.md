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
        Scanner ler = new Scanner(System.in);
        int[] nota = new int[10];
        int x, soma = 0, media;
        for (x = 0; x < nota.length; x++) {
            System.out.println("Digite a nota "+(x + 1)+":");
            nota[x] = ler.nextInt();
            soma += nota[x];
        }
        media = soma / nota.length;
        System.out.println("\nMédia das notas: "+media);
        System.out.println("As notas maiores que a média é");
        for (x = 0; x < nota.length; x++) {
            if (nota[x] > media) {
                System.out.println("nota "+(x + 1)+": "+nota[x]);
```
# questao8
```java
        int[] vetor = {7, 9, 10, 14, 23, 23, 1, 15, 16, 2};
        int contador = 0;
        int x = 0;
        while (x < 10) {
            if (vetor[x] == 5) {
                contador++;
            }
            x++;
        }
        System.out.println("O número 5 aparece "+ contador +" vezes no vetor.");
```
# questao9
```java
        int[] vetor = {7, 9, 10, 14, 23, 23, 1, 15, 16, 2};
        int[] multiplos = new int[10];
        int x = 0;
        int y = 0;
        int c = 0;

        while (x < 10) {
            if (vetor[x] % 3 == 0) {
                multiplos[y] = vetor[x];
                y++;
            }
            x++;
        }

        System.out.println("Valores múltiplos de 3:");
        x = 0;
        while (x < y) {
            System.out.println(multiplos[x]);
            x++;
```
# questao10
```java
        int[] A = {1, 8, 19, 9, 17, 4, 7, 11, 3, 0};
        int[] B = {7, 9, 10, 14, 23, 23, 1, 15, 16, 2};
        int[] C = new int[10];
        int i = 0;

        while (i < 10) {
            if (A[i] > B[i]) {
                C[i] = A[i];
            } else {
                C[i] = B[i];
            }
            i++;
        }

        System.out.println("Vetor C com os maiores valores entre A e B: ");
        i = 0;
        while (i < 10) {
            System.out.println(C[i]);
            i++;
```
