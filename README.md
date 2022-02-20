package application;

public class Program {

	public static void main(String[] args) {
		
		String[] vect = new String[] {"Maria", "Bob", "Alex"};
		
		for (int i = 0; i < vect.length; i++) {
			System.out.println(vect[i]);
		}
		
		System.out.println("-------------------------------------------------------------------------------------------");
		
		// para cada objeto obj contido no vetor vect, faça.
		
		for (String obj : vect) {
			System.out.println(obj);
		}
	}

}
/*
 *  Essa estrutura é utilizada para iteração de listas, ou seja, é uma estrutura simplificada do laço for 
 *  quem tem por objetivo tornar o código mais legível e a codificação mais rápida.
 *  
 *  é uma sintaxe opcional e simplificada para percorrer coleções
 */
