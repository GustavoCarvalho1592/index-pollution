# index-pollution
import java.util.Scanner;

class Main {

    public static void main(String[]args) {

    Scanner leia = new Scanner (System.in);

    double numero;
        
    System.out.println("Informe o índice da poluição medido no momento: ");      
    numero = leia.nextDouble();
      
    if (numero >0.05 && numero <= 0.25){
    System.out.println("Grupo 1 e Grupo 2 - podem continuar suas atividades: "+ numero);
    
    }else{

    if (numero >0.25 && numero < 0.3){
    System.out.println("Grupo 1 - Deve suspender suas atividades: "+ numero);
    
    }else{
         
    if (numero > 0.4 && numero < 0.5)
    {
  
    }else{
   
    System.out.println("Grupo 1 e 2 - Devem suspender suas atividades: "+ numero);
      
      }    
    }
   }
  }
}
