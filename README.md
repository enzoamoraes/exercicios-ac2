# exercicios-ac2
Exercicio 2 ac2 Calculo Fundamental import java.util.Scanner;

public class HelloWorld { public static void main(String[] args) { Scanner ler= new Scanner(System.in); // inicializar um Scanner int ra; double n1, n2, n3, m; int i, cont = 0; for (i = 0; i < 10; i++){ cont++; System.out.printf("Digite o RA do aluno, se nao houver digite 0: "); ra = ler.nextInt(); if (ra !=0 ){ System.out.printf("Digite a primeira nota: "); n1 = ler.nextDouble(); System.out.printf("Digite a segunda nota: "); n2 = ler.nextDouble(); System.out.printf("Digite a terceira nota: "); n3 = ler.nextDouble();

     m = (n1+n2+n3)/3;
     if (m>6) {
     System.out.printf("Voce foi reprovado " + m);
     }
     else if (m>6 && m < 8) {
         System.out.printf("voce esta de recuperacao " + m);
     }
     else if (m>8) {
        System.out.printf("Voce esta aprovado " + m);
     }
else {
      break;
        }
     }
}
} }

![image](https://user-images.githubusercontent.com/103973508/169727761-f4e2f65f-6d59-42fc-99bb-113618e3e375.png)
