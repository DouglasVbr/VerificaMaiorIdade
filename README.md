# VerificaMaiorIdade


package verificamaioridade;
import java.util.Scanner;

public class VerificaMaioridade {

    
    public static void main(String[] args) {
     
  Scanner Scanner = new Scanner(System.in);
  
  // solicita ao usuario que insira a idade
  
        System.out.println("Digite sua idade:");
        int idade = Scanner.nextInt();
        // verifica se a pessoa é maior de idade 
        if(idade >=18){
            System.out.println("voce é maior de idade.");
        }else{
            System.out.println("voce é menor de idade.");
            }
        //fecha o Scanner
        Scanner.close();
        
    }
    
}
