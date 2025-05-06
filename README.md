# Desafio7
# Questao 1
```java
public class ExerciciosMetodos {

    public static void main(String[] args) {
        int n;
        Scanner ler = new Scanner(System.in);
        System.out.println("Digite um numero");
        n = ler.nextInt();
        Tabuada(n);
    }
    public static void Tabuada(int x) {
        int i = 1;
        int fim = 10;
        while (i <= fim) {
            System.out.println(x + " x " + i + " = " + (x * i));
            i++;
        }
    }
}
```
# Questao 2
```java
public class ExerciciosMetodos {

    public static void main(String[] args) {
        Scanner ler = new Scanner(System.in);
        int n1, n2;
        System.out.println("Digite o primeiro valor");
        n1 = ler.nextInt();
        System.out.println("Digite o segundo valor");
        n2 = ler.nextInt();
        NumeroInteiro(n1, n2);
    }

    public static void NumeroInteiro(int n1, int n2) {
        if (n1 > n2) {
            System.out.println("Primeiro valor e maior" + n1);
        } else {
            System.out.println("Segundo valor e maior" + n2);
        }
    }
}
```
```java
public class ExerciciosMetodos {

    public static void main(String[] args) {
  
public class Desafio7 {

    public static void main(String[] args) {
        Scanner ler = new Scanner(System.in);
        String s1, s2;
        System.out.println("Digite uma palavra:");
        s1 = ler.nextLine();
        System.out.println("Digite uma palavra:");
        s2 = ler.nextLine();
        Compara(s1, s2);

    }

    public static void Compara(String x, String y) {
        if (x.equals(y)) {
            System.out.println("Sao iguais");
        } else {
            System.out.println("Nao sao iguais");
        }

    }
}
```
