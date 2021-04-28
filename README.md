# Calculo.java
Exercicio Aula JAVA Fuctura

import java.util.Scanner;

public class Calculo {

	public static void main(String args[]){

		double numeroUm;
		double numeroDois;

	System.out.println("************************");
	System.out.println("**** SEJA BEM-VINDO ****");
	System.out.println("************************");
	System.out.println();


	Scanner calc = new Scanner(System.in);

	System.out.println("Informe o primeiro número:");
	numeroUm = calc.nextDouble();

	System.out.println("Informe o segundo número:");
	numeroDois = calc.nextDouble();

	System.out.println();
	System.out.println("**********************");
	System.out.println("Soma: " + (numeroUm + numeroDois));
	System.out.println("Subtração: " + (numeroUm - numeroDois));
	System.out.println("Multiplicação: " + (numeroUm * numeroDois));
	System.out.println("Divisão: " + (numeroUm / numeroDois));
	System.out.println("**********************");


		
	}//end main
	
}//end class Calculo


