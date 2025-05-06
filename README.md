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
# Questao 3
```java
public class ExerciciosMetodos {

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
# Questao 4
```java
package desafio7;


public class Desafio7 {

    public static void main(String[] args) {
        Scanner ler = new Scanner(System.in);
        int n1, n2;
        System.out.println("Digite o primeiro valor:");
        n1 = ler.nextInt();
        System.out.println("Digite o segundo valor:");
        n2 = ler.nextInt();
        NumerosInteiros(n1, n2);
    }

    public static void NumerosInteiros(int n1, int n2) {
        if (n1 < n2) {
            System.out.println("Primeiro valor e menor:" + n1);
        } else {
            System.out.println("Segundo valor e menor:" + n2);
        }
    }
}
```
# Questao 5
```java
package desafio7;

public class Desafio7 {

    public static void main(String[] args) {
        Scanner ler = new Scanner(System.in);
        String s1, s2;
        System.out.println("Digite uma palavra:");
        s1 = ler.nextLine();
        System.out.println("Digite uma palavra:");
        s2 = ler.nextLine();
        imprimirTexto(Compara(s1, s2));

    }

    public static String Compara(String x, String y) {
        String resp="Os nomes nao são iguais";
        if (x.equals(y)) {
            resp="Os nomes sao iguais";
        }
        return resp;
    }
    public static void imprimirTexto(String texto) {
        JOptionPane.showMessageDialog(null, texto);
    }
}
```
# Questao 6
```java
package desafio7;
public class Desafio7 {

    public static void main(String[] args) {
        Scanner ler = new Scanner(System.in);
        double celsius, formulaF;
        System.out.println("Digite um valor:");
        celsius = ler.nextDouble();
        conversor(celsius);
    }

    public static double conversor(double c) {
        double formulaF = (c * 1.8) + 32;
        System.out.println("A temperatura de Celsius para Fahrenheit:" + formulaF + "°F");
        return formulaF;
    }

}
```
#Questao 7
```java
package desafio7;
public class Desafio7 {

    public static void main(String[] args) {
        Scanner ler = new Scanner(System.in);
        double raio;
        System.out.println("Digite o raio do círculo:");
        raio = ler.nextDouble();
        areaCirculo(raio);

    }

    public static double areaCirculo(double r) {
        DecimalFormat df = new DecimalFormat("0.00");
        double areaC = Math.PI * (Math.pow(r, 2));
        System.out.println("A área do círculo é:" + df.format(areaC));
        return areaC;
    }

}
```
# Questao 8
```java
package desafio7;
public class Desafio7 {

    public static void main(String[] args) {
        Scanner ler = new Scanner(System.in);
        double nota1, nota2, nota3;
        System.out.println("Digite a primeira nota:");
        nota1 = ler.nextDouble();
        System.out.println("Digite a segunda nota:");
        nota2 = ler.nextDouble();
        System.out.println("Digite a terceira nota:");
        nota3 = ler.nextDouble();
        mediaPonderada(nota1, nota2, nota3);

    }

    public static double mediaPonderada(double n1, double n2, double n3) {
        double mediaP = (n1 * 3 + n2 * 3 + n3 * 4) / 10;
        System.out.println("Sua média ponderada é:" + mediaP);
        return mediaP;
    }

}
```
