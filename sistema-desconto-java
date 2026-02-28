package TreinamentosERevisoes;
import java.util.Scanner;


public class Treino2 {

	public static void main(String[] args) {
		
		Scanner scanner = new Scanner(System.in);
		
		System.out.println("Quantidade de alunos da turma: ");
		int quantalunos = scanner.nextInt();
		scanner.nextLine(); // limpa o Enter pendente
		
		double somanotas = 0;
		double maiornota = 0;
		double menornota = Double.MAX_VALUE;
		int aprovados = 0;
		String nomeMaiorNota = "";
		double mediaSala = 0;
		
		for (int i = 1; i <= quantalunos; i++) { 
		  
		  System.out.println("Digite o nome do aluno: ");
		  String aluno = scanner.nextLine();

          System.out.println("Digite a nota do aluno: ");
		  double nota = scanner.nextDouble();
		  scanner.nextLine(); // limpa o Enter depois da nota
          
          somanotas += nota;
          
            if (maiornota < nota) {	  
               	maiornota = nota;           
               	nomeMaiorNota = aluno;
          }
            if (menornota > nota) {
                menornota = nota;
            }
            
            if (nota >= 6) {
            	   aprovados++;
            	}

            
		}
		
		 mediaSala = (somanotas / quantalunos);
		
		 System.out.printf("Média da turma: %.2f%n", mediaSala);
         System.out.printf("Maior nota: %.2f%n", maiornota);
         System.out.printf("Menor nota: %.2f%n", menornota);
         System.out.printf("Aprovados: %d%n", aprovados);
         System.out.printf("Aluno com a maior nota: %s%n", nomeMaiorNota);
         
         scanner.close();
	}

}
