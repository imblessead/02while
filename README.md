# 02while
02while

package exercicios;

//apresentar total da soma obtida dos cem 	primeiros numeros inteiros(1+2+3+4+...+98+99+100).
public class Exercicio02while {

	public static void main(String[] args) {

		int contadora = 1;
		int soma = 0;

		while (contadora < 101) {
			soma = soma + contadora;
			contadora++;

		}
		System.out.println("A soma dos cem primeiros numeros positivos e: " + soma);
	}

}

